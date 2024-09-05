---
layout: project
type: project
image: img/proj2pic.png
title: "Secure Hash Standard"
date: 2023
published: true
labels:

  - Algorithm Implementation
  - Hash Function
  - Bit Manipulation
  - C
  - C++
summary: "My from-scratch implementation of the SHA-1 hashing algorithm"
---

<div class="text-center p-4">
  <img width="200px" src="../img/sha1.png" class="img-thumbnail" >
  
</div>

The algortihm I implemented in my code is used to create a compact representation of a message, known as a message digest. It is a requirement when using the Digital Signature Algorithm (DSA), as defined by the Digital Signature Standard (DSS), and is mandated for Federal applications that need a secure hash function. Both the sender and receiver utilize SHA-1 for generating and verifying digital signatures. This standard applies to all Federal agencies for protecting unclassified information, and private and commercial entities are encouraged to adopt it as well.

Applications: SHA-1 can be used with DSA in scenarios such as email, electronic funds transfer, software distribution, data storage, and other areas where data integrity and authentication are critical. It is also suitable for generating a compact representation of a message whenever needed. For my specfic implementation, I gathered 3 files named a.txt, abc.txt, alpha.txt which all contained strings. My job was to convert these strings into hexadecimal, binary, and/or individual bits. Different files digest different messages. 



You can learn more about the SHA-1 hashing algorithm [here](https://manoa.hawaii.edu/news/article.php?aId=2857](https://csrc.nist.gov/pubs/fips/180-1/final)).
