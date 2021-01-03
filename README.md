# hack_text
Watch Dogs inspired fake hacking text decoder

## Usage
### run from terminal:
python hack_text.py -t=0.01 test string

(-t is optional (defaults to 0.005) but if present must be formatted exactly as above)

### import as module:
import hack_text;

hack_text.run(timer=0.005, i_text="");

also hack_text.list_of_char(); provides list of valid input characters

TODO: regex to handle invalid characters
