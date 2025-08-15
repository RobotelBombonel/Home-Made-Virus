Hello, in this file I'll show you a tutorial on how to open this virus, also here is how you can save your computer after it went to permanent BSOD

# How to open the virus?
- press right click on the file and press Run as administrator
- after that your PC will restart and it will BSOD Windows permanently

# How you fix it? 
- after some failed reboots your Windows will go in recovery environment 
- at automatic repair press advanced options -> troubleshoot -> advanced options -> command prompt 
- go and write diskpart, then list volume (now there will be some letters, in the right of them the storage) 
- now look at the disks with the most storage (and test them both), write exit 
- write (letter of diskpart): 
- go and write now: cd (letter of the storage, big letter):\Windows\System32\config 
- write dir and if on display there is a file called OSDATA your in correct disk/directory if not write exit and go with the other one, after you see a file named OSDATA you are in the good directory - write del OSDATA, then dir, if u don't see any OSDATA file name displayed there your good 
- after this reboot Windows

# What this virus does?
- creates a file OSDATA in directory: C:\Windows\System32\config\OSDATA
- OSDATA will have written in it the text T
- after the file OSDATA is in the directory your PC gets restarted
- and after the restart your Windows will BSOD permanently (until you fix it like I showed you on # hou you fix it?)

FOR MORE DETAIL CHECK: https://www.youtube.com/watch?v=G3VZV4rewuo
