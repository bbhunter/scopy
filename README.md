```
  ____ ____ ____ ___  _   _ 
  [__  |    |  | |__]  \_/  
  ___] |___ |__| |      |    ᴍᴀᴅᴇ ʙʏ ᴀʟᴘʜᴀʀᴀᴏʜ    

```
# Scopy 
Collects all valid scopes from hackerone programs
Can collect multiple scopes at once and output their scopes 

# Disclaimer 
This tool only collects in-scope URLS.

"*." is removed from scope text e.g. *.api.example = api.example

## Installation

1) git clone https://github.com/AkaamS/scopy.git
2) cd scopy
3) python3 scopy.py -h

## Example Usage

Single Program:
```
python3 scopy.py -u NAME
```
List of Programs:
```
python3 scopy.py -u NAME,NAME1,NAME2,NAME3
```
## Options

```
Usage: scopy.py [-u NAME] [-o] [-t TIME] [...]

Optional Args:
    -h                  Displays this message
    -u URL(s)           Name of program (hackerone.com/NAME)
                        -u NAME,NAME1,NAME2 (Make sure to have no spaces between , )
    -o                  Output only results
    -t TIME             Time to allow javascript to load (Default: 4)
    -s                  Add "https://" to scopes

```
