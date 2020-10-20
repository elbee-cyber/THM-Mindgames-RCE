## Exploit for TryHackMe's 'Mindgames' Room
The room was created by [NinjaJc01](https://tryhackme.com/p/NinjaJc01) 

Here is the [room](https://tryhackme.com/room/mindgames)
 
 
The webserver in mindgames takes brainfuck input, upon further examination we see that the backend is executing brainfuck-encoded python code. We can abuse this for RCE.
The exploit provided was a script I made to automate RCE for this vulnerability. Be sure you understand what you're exploiting and read the code, it is very simple.
I even included comments in it, so don't be a **skid!**

![Action!](https://i.ibb.co/YZZNnmV/Screenshot-at-2020-10-20-12-30-32.png "usuage")
