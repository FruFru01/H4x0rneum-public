# Forensic

**Find Strings in file:**
strings

**Check filetype from header:**
file

**carve file for known file headers:**

 &nbsp;&nbsp; binwalk -e [automatic extract] -M [recursive] -dd='.\*' [extract all types]

 &nbsp;&nbsp; scalpel/foremost (define header/footers in /etc/scalpel/scalpel.conf)

**Brute forces jpg stego:**
https://github.com/Paradoxis/StegCracker

**Other Stego tools:**
https://github.com/DominicBreuker/stego-toolkit#tools

**PDF transformation:**
qpdf

**detect stegano-hidden data in PNG & BMP:**
zsteg -a [try all methods]

# Web

**Web vulnerability scanner:**
nikto 

**Web content scanner:**
dirb

**HTTPS virtual host enumeration:**
https://github.com/UnaPibaGeek/ctfr

**.DS_Store parser:**
 &nbsp;&nbsp; https://github.com/gehaxelt/Python-dsstore
 &nbsp;&nbsp; ./main.py .DS_Store


## Markdown cheatsheet

**asterisks**
[I'm an inline-style link](https://www.google.com)

Reference-style: 
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"

Inline `code`

```python
s = "Python syntax highlighting"
print s
```
