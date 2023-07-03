# BTCscan
Find traces of Bitcoin and *coins in a chunk of data - RAM/Disk/Image
BTCscan 0.9 by Chris COHEN (chris.w.cohen@gmail.com)

Website: https://gist.github.com/chriswcohen/7e28c95ba7354a986c34
Donations: 1BnvsBZcyVxF8L8HboUcDc2mAUu9K2qsTe
Accompanying Article: https://articles.forensicfocus.com/2015/01/16/forensics-bitcoin/

Searches a file or all files within a folder including sub folders for Bitcoin
related Base58Check encoded strings.


BTCscan.py [-i/--input=][drive:][path][filename] [args]

-i / --input       Specifies drive, directory, and/or files to search
-q / --quick       Quick mode, does not search BIP32 HD wallet keys
-u / --unicode     Unicode mode, only search for Unicode items
-n / --nonunicode  Non-Unicode mode, only search for non-unicode items
-h / --help        Prints this page

Examples:
   BTCscan.py -i JED-01.dd
   BTCscan.py -input="C:\folder\"
   BTCscan.py --quick -u -i memory.dat
   
If you find BTCscan to be of use to yourself, organization or company then I
politely ask that you write me a very short email letting me know how it
worked out for you. This information will never be published - it is solely
for my own personal interest.

--itsmeRiF
