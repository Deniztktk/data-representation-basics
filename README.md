# data-representation-basics
This note is about data representation , a topic i learned about in my certificate program and courses. how computers represent data using binary. 

# Data Representation

##  What is data representation?
Computers are **not intelligent.** 😑🧠
A computer works completely with **electricity**⚡️, and computer do *not understand numbers*😒, *they understand electricity.*😏.
Because of this, **the best way to communicate in an electrical system is to control the electricity/voltage state of a line.**🗣️

## This state has two possibilities:
- No electricity = 0
- Electricity exists = 1

    **These 0 and 1 values are one of the most elegant solutions in engineering and physics. We can think of this as a yes/no system.**👀
  - 0 = NO 👎 
  - 1 = YES 👍

 ## If computers only understand 0 and 1, what do we see?
 A computer understands only 0 and 1, meaning yes or no. But as humnas, we see:
 - text
 - numbers
 - ımages...
      **Data representation** explains how all this information is converted into **0 and 1.**
       In short, data representation shows how information is represented inside a computer.

## Binary Number System.
The system that uses only 0 and 1 is called the binary system.
-Binary is a base 2 system
-It uses only the digits 0 and 1
-Computers store all numbers in **binary from**

## Why Base 2? 
In daily life, we used the decimal system (base 1o):
` 0 1 2 3 4 5 6 7 8 9 `
But inside computers, there are transistors. A transistors has only two states:
- On (electricity exists)
- Off (no electricity)

**So computers work with: 🖥️ 
On/Off
Yes/No
1/0**

⭐️ Because of this, binary (base 2) is the most logical and reliable system for computers. 

**Okey but how does binary work?**
## How does binary work? 2️⃣ 
*Example:*
  `1001`
This means:
  `1x8
  0x4
  1x2
  1x1`

If we add them
  `8+0+2+1=11`
So:
`1011(binary) = 11 (decimal)`

**For comparison, in decimal system:**
  `123= 1x100 + 2x10 + 3x1`

## Text representation how does a letter become a number?
Computers do not understand letters. ✍️ 
Because of this, a standart system is used to convert letters into numbers. 2️⃣ 

-This systen is called **ASCII** ‼️ 

**in the ASCII table:
A = 65
B=66
a= 97..**

⚠️ You see the letter "a" on the screen, but the computer stores it as a number in memory.
*For example:*
  `a = 97`

## Okey we understand but how does "a" become binary? ⛔️
*The computer stores the number 97 in binary form. So we need to convert 97 into base 2.* 👀 

🔥**Rule: divide by 2 continuously and write the remainders**🔥

💨💨*Step by step conversion*
  `97 / 2 = 48 remainder 1 (48,5)
  48 / 2 = 24 remainder 0 
  24 / 2 = 12 remainder 0
  12 / 2 = 6 remainder 0
  6 / 2 = 3 remainder 0 
  3 / 2 = 1 remainder 1 (1,5)
  1 / 2 = 0 remainder 1 (0,5)`💨💨

**Now we read the remainders from bottom to top:**
Like:
`1100001`

**This is 7 bits. But in computers, the smallest standard unit is 8 bits (1 bytes). 🧩🧩 So we add one 0 to the beginning:**
`01100001`
💿**Final result:**
  `a = 97 = 01100001`


🤩🤩🤩# Summary
-Computers work with electricity 
- Electricity is represented as 0 and 1
- 0 and 1 from the binary system
- Numbers, text, sound, and images are stored as binary
- ASCII converts letters into numbers
- Numbers are converted into binary 🥳🥳🥳











  

