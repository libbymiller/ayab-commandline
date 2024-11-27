Forked from https://github.com/AllYarnsAreBeautiful/ayab-commandline

 * updated to python3
 * created a version that reads csv files

# INSTALL

for ayab_commandline.py

`pip3 install serial Pillow`

for ayab_commandline_csv.py

`pip3 install serial numpy Pillow`


# RUN

```
Usage: ayab_commandline.py [filename] [options]

AYAB Control Commandline Version

Options:
  -h, --help            show this help message and exit
  -p PORT, --port=PORT  Serial Port used for communication with the machine
                        [default: /dev/ttyACM0]
  -c COLORS, --colors=COLORS
                        Number of Colors of your image [default: 2]
  -t TYPE, --type=TYPE  Set the type of the machine (single/double bed)
                        [default: single]
  -l, --list            List all available serial ports and exit [default:
                        False]
```
or

```
Usage: ayab_commandline_csv.py [filename] [options]

AYAB Control Commandline Version with added csv

Options:
  -h, --help            show this help message and exit
  -p PORT, --port=PORT  Serial Port used for communication with the machine
                        [default: /dev/ttyACM0]
  -c COLORS, --colors=COLORS
                        Number of Colors of your image [default: 2]
  -t TYPE, --type=TYPE  Set the type of the machine (single/double bed)
                        [default: single]
  -l, --list            List all available serial ports and exit [default:
                        False]
  -x CSV, --csv=CSV     Use a csv file not an image [default: none]
  -i IMAGE, --image=IMAGE
                        Use an image not a csv file[default: none]
```


