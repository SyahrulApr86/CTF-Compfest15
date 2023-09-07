# E2EBleed [495 pts]

**Category:** Forensics
**Solves:** 7

## Description
>Someone in my house seems to be doing something fishy again\xe2\x80\xa6 Maybe this time I will investigate. I\xe2\x80\x99ve tapped into the connection of said person\xe2\x80\x99s internet, perhaps you could help me find what they\xe2\x80\x99re doing?\r\n\r\nThe (compiled) code and docker files required to run the set up locally are provided.\r\n\r\nTo deploy locally, simply run `docker compose up --build -d`. You can go to http://localhost:444/ to access the site.\r\n\r\nExample usage of the website: [Video](https://cdn.discordapp.com/attachments/1147374328732713000/1147388640805261392/simplescreenrecorder-2023-09-02_11.31.52.mp4)\r\n\r\nNOTE: Use `chall-olddocker.zip` if you use docker 20, if you have newer version, `chall.zip` should work just fine.\r\n\r\n**Author: rorre**

**Hint**
* b"Browsers devtools is an amazing tool. Maybe look at the source and network tab to figure things out?\n* Try looking at the lifecycle of the chat, its also using a common cryptography technique in CTF challenges."

## Solution

### Flag

