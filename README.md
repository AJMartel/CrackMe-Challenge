# CrackMe-Challenge

A friend of mine wanted to learn reverse engineering, so I made this little script for him to try.

## To compile:

```
g++ -std=c++14 -o "anyname" "source.cpp" 
```

## Walkthrough

https://www.jamieweb.net/blog/radare2-cutter-part-3-solving-a-crackme-challenge/

## Python Helper
```
for i in "1824 1776 1840 1616 1568 1872 1600".split(" "):
    print(chr(int(i) >> 4))
```
