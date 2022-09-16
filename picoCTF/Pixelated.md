# Pixelated
## Category
Cryptography
## Problem Description
I have these 2 images, can you make a flag out of them? [scrambled1.png](https://mercury.picoctf.net/static/75e646e4ad19967ca1811f895fb40465/scrambled1.png) [scrambled2.png](https://mercury.picoctf.net/static/75e646e4ad19967ca1811f895fb40465/scrambled2.png)
## Approach
I used [stegsolve](https://wiki.bi0s.in/steganography/stegsolve/) to overlay scrambled2.png over scrambled1.png.<br>

![scrambled1](https://github.com/caligo-phantom/writeups/blob/main/picoCTF/assets/scrambled1.png)<br>

![scrambled2](https://github.com/caligo-phantom/writeups/blob/main/picoCTF/assets/scrambled2.png)<br>

I went through various add methods to obtain the flag.<br>

![solved](https://github.com/caligo-phantom/writeups/blob/main/picoCTF/assets/solved.bmp)

## Flag
picoCTF{d562333d}
