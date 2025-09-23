---
layout: post
title: ASCII Whale 
thumbnail-img: /assets/img/ascii.png
tags: [C, ASCII]
author: <Peter Kane>
---

This literally just prints this whale line by line. Just used newline characters for separate lines (made by Riitta Rasimus -- found on https://www.asciiart.eu/animals/fish).
![ascii-output](/assets/img/ascii.png)

**Code (C):**
```c
// ascii.c
// prints ascii whale (Ritta Rasimus)

#include <stdio.h>

int main(void) {
    printf("       .        \n");
    printf("      \":\"       \n");
    printf("    ___:____     |\"\\/\"|\n");
    printf("  ,'        `.    \\  /\n");
    printf("  |  O        \\___/  |\n");
    printf("~^~^~^~^~^~^~^~^~^~^~^~^~\n");
    return 0;
}
```
