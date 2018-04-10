# Oops/Sl@ckers
## Week 13, Research, Altering NetBoot.xyz source code, Compiling...
### Pavel Danek

Hello everyone,
we have 2 major challenges ahead of us:
1. Get the TFTP server up and running
2. Get iPXE boot and connect to our server

I've been trying to work on the iPXE end and got a little further this week. I was abe to pinpoint _WHICH_ parts of NetBoot.xyz relate to us and _HOW_ to alter them, but I've also run into some challenges I wasn't able to crack yet.
This picture shows, what needs to be changed in the source code:
![Pic #1](/Pics2/IMG1.jpg)
Here's how image files are compiled:
![Pic #2](/Pics2/IMG2.jpg)
First of all, the script has to be run from its **superior** directory, in order for the hierarchy to work.
I tried to run it and my first **error** I've run into was on line 16: no such files existed. I took care of that, but then there were other **errors** _while_ compiling the directory... See below:
![Pic #3](/Pics2/IMG3.jpg)

![Pic #4](/Pics2/IMG4.jpg)

![Pic #5](/Pics2/IMG5.jpg)

Has anyone tried to research the same and got any further? Please let me know.

PS: When booting the NetBoot.xyz from the USB, my computer at home doesn't connect to the Internet, so I have to do any testing at school...

Good luck everyone & I'll see you in class!

-Pavel.

