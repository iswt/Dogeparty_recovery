You can use this script to dump address information from your dogeparty 
seed.

You will need to use a custom fork of the bip32utils library which you 
can find at https://github.com/iswt/bip32utils

## Usage

```
usage: dump_info.py [-h] [-i] [-d DEPTH | -r DEPTH_RANGE] [-o 
OUTPUT_FILE]

Dump address information from your dogeparty seed

optional arguments:
  -h, --help            show this help message and exit
  -i, --information     Dump wallet information and exit
  -d DEPTH, --depth DEPTH
                        Depth of address information to dump (e.g. 0)
  -r DEPTH_RANGE, --depth-range DEPTH_RANGE
                        Depth range of addresses to dump (e.g. 
dump_info.py -r
                        0,10)
  -o OUTPUT_FILE, --output-file OUTPUT_FILE
                        dump output to file
```

## Install

```
git clone https://github.com/iswt/Dogeparty_recovery.git
cd Dogeparty_recovery/
pip install -r requirements.txt
```

## Donate

Did this script help you recover some coins? Awesome. If you feel like 
leaving a little something you can donate some crypto :)

```
Bitcoin: 3AXgwnUhEqunTHS7Jzs4iSs2dSd6hu1Cxe
```
