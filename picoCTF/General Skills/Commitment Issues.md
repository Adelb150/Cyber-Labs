# picoCTF - Commitment Issues

## Description
I accidentally wrote the flag down. Good thing I deleted it!
[Zip](https://artifacts.picoctf.net/c_titan/77/challenge.zip)


## Steps
1. Downloaded .zip file into my personal CTF folder using wget.
2. Given git repo, so I checked git log for previous commits
3. Found previous commit that says "Create flag" before the current master that deleted that flag in message.txt
4. Git checkout to old commit, and then cat into message.txt, finding the flag in the commit before it was removed.
<details>
  <summary>Given flag</summary>
  
  >!picoCTF{s@n1t1z3_30e86d36}
</details> 


## Tools Used
- git log
- git checkout

## Key Takeaway
Learned how to find previous commits and switch to them in order to find the flag. 
