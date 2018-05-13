---
layout: project
type: project
image: images/gecko.jpg
title: SHA1
permalink: 
date: 2017-18-04
labels:
  - C
  - Crytography
  - Algorithms
summary: This is the final project for my ICS 212 class during the spring of 2017 at Kapiolani Community College. The algoritm used is an obsolete one, SHA-1.  The program inputs a file, processes it, and spits out out an alphanumeric string. I implemented SHA-1 using C.
---

This project first introduced me to the complex subjects and algorithms and cryptography and sparked my interest into computer security.  In the future, I hope to develop better algorithms and produce extremely effecient and secure hashes for passwords.

This program uses multiple functions.   My first function reads the entire file character by character and stores the contents in an array of unsigned integers. Second, I divide the bits of the file by 512 to determine the block count.  Once I have the block count, I covert the array of unsigned characters to an array of unsigned integers.  Finally, I compute message digest, which initializes the blocks according to the hashes standard, and loop through each of the blocks.  


