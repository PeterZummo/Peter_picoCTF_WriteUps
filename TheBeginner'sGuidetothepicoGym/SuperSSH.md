# Obedient Cat #

**CTF Name** - picoCTF 

**Challenge Name** - SuperSSH Using a Secure Shell (SSH) is going to be pretty important.
Additional details will be available after launching your challenge instance.

**Challenge category** - General Skills 

**Challenge points** - Easy 

**CTF Year and Date** - 2024

## Overview
<details>
  
  <summary>Click for a Simple Step By Step</summary>
ssh ctf-player@titan.picoctf.net -p 63345 <br> <br>
yes (yes to ED25519 Key Fingerprint) <br> <br>
Enter Password 1ad5be0d <br> <br>

</details>

<details>
  <summary>Click to reveal the solution</summary>
picoCTF{s3cur3_c0nn3ct10n_8306c99d}
</details>


## Step 1 of 1 | SSH or Secure Somthing
This challenge just presents us with our first use of SSH, a fundemntal compmennt of not only CTFs, but computers! SSH, or 
Secure Shell, is a secure protocol for connecting to remote servers and executing commands over a network. 
A shell or CLI (Command Line Interface) is a command-line interface that allows users to interact with the operating system by 
entering and executing commands.

For this challage we are asked to ssh as ctf-player to titan.picoctf.net at port 63345 to get the flag. Simple Enough
all we have to do is open our Terminal or _shell_ on our machine or a linux machine and enter the command ssh command.
Remeber to use the -p flag to specify the port we want to ssh at, as if not we will attempt to ssh to the Secure Shell's Defualt port of 22






![image](https://github.com/user-attachments/assets/3e3e02ef-9968-4352-9aa2-16ad33ea3311)




