# hack_text
Watch Dogs inspired fake hacking text decoder

shout out to Noah Caldwell-Gervais

https://www.youtube.com/watch?v=UaI1BgNTy8k

## Usage
### run from terminal:
python hack_text.py -t=0.01 test string

(-t is optional (defaults to 0.005) but if present must be formatted exactly as above)

### import as module:
import hack_text;

hack_text.run(timer=0.005, i_text="");

also hack_text.list_of_char(); provides list of valid input characters

TODO: regex to handle invalid characters

## Note:
this program uses ANSI escape codes and which must be manually enabled on Windows (and maybe mac as well)

these chould help:

https://superuser.com/questions/413073/windows-console-with-ansi-colors-handling

https://stackoverflow.com/questions/16755142/how-to-make-win32-console-recognize-ansi-vt100-escape-sequences
