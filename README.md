# img.doxxer
img.doxxer

The images for this project are created with .js and they all have 
embedded data that is encrypted. psswd for all the img.doxxer 
images =  dox
The embedded data is mostly sensitive information gathered with OSINT 
software about internet related issues and vulnerabilities.

Using steghide to encrypt and decrypt images with files:
Download or install steghide: http://steghide.sourceforge.net/

On linux distro use: $ sudo apt-get install steghide

TO EMBED PIX: steghide embed -cf theImg.jpg -ef theTxt.txt

TO EXTRACT THE EMBEDDED DATA FROM JPG: steghide extract -sf theImg.jpg
