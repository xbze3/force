# Web-Force

A Multi-Threaded Python Web Directory Bruteforcer that can make use of a user specified wordlist for the purpose of bruteforcing.

## Usage

`python force.py -u URL -w WORDLIST`

### Flags

`-u | --url` - Target URL (Required)

`-w | --wordlist` - Path to wordlist file to be used for bruteforcing (Required)

`-c | --code` - Can be used to display directories which render a specific status code when visited (E.G. 200)

`-e | --extension` - Allows program to also enumerate for files with a specific extension

`-h | --help` - Diplays help screen

#### Important Libraries

All necessary libraries can be installed using the command: `pip install -r requirements.txt`