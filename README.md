This repo will contain all the CTFs I have done and what I learned from each one.


Current setup:

1. [Challenge Name & Category]
2. [Summary]
3. [Steps Taken]
4. [Key Takeaways]



Example:

# picoCTF - Vault Door Training (Binary Exploitation)

## Description
Simple binary reversing challenge where the password is hard-coded in the source.

## Steps
1. Downloaded source code and opened in VS Code.
2. Found the password inside the `checkPassword` function.
3. Entered password to unlock flag.

## Tools Used
- strings
- grep

## Key Takeaway
Learned how to use `strings` to quickly extract hard-coded values from binaries.
