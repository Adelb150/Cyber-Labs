# picoCTF - endianness

## Description
Know of little and big endian?
[Source](https://artifacts.picoctf.net/c_titan/119/flag.c)


## Steps
1. Downloaded .c file into my personal CTF folder using wget.
2. Nano flag.c to first check the code.
3. Identified that it will ask for little endian and big endian represenation of randomly generated word
4. Ran code, received word: rapwf
5. Converted rapwf to hex, given 72 61 70 77 66
6. This will be our big endian represenaion, while little is the opposite -> 66 77 70 61 72
7. Given flag --> >!picoCTF{3ndi4n_sw4p_su33ess_28329f0a}!<

## Tools Used
- ASCII conversion to hex

## Key Takeaway
Learned big and small endian of a string of letters.
