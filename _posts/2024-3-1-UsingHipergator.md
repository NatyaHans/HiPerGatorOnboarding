---
layout: post
title:  Using the cluster (HiPerGator) 
categories: [HiPerGator,bash, linux, windows]
---

If this is your first time using the cluster, I would advice to learn some basic bash scripting. Navigating your way through different directories and cluster would be a lot easier with basic bash commands such as
pwd,cd, mkdir, ls. Please check the bash scripting [tutorials here]()


Creating Account on Hipergator
------
To use the HiPerGator, you first need to have an account with UF research computing. To request an account with Library HiPerGator Sponsorship Program, [submit the request here](https://arcs.uflib.ufl.edu/services/student-hipergator-access/). 

You can also request an account with research computing if/when you have funding by [submitting request here](https://www.rc.ufl.edu/access/account-request/)


Login to the HiPerGator
------
Depending on the operating system, logging in into the cluster can be easy or a bit tedious. 

For windows, download an SSH client such as [PuTTy](https://www.putty.org/) or [FireZilla](https://filezilla-project.org/).
Set up the SSH client. 
For PuTTy,
     
1. Download PuTTY to your local machine and start the program .
2. Next, connect to hpg.rc.ufl.edu.
3. When asked for the login prompt, type your username (which should be your GatorLink username)
4. Enter your password when prompted. You should be connected to the HiPerGator. 

If on Mac, open Terminal window, type

```bash 
ssh USERNAME@hpg.rc.ufl.edu
```

Replace USERNAME with your username. Your USERNAME is your GATORLINK ID. Enter the password when prompted. You should be connected to the HiPerGator.


Logging off from the HiPerGator
------
To log off from the HiPerGator, type in the terminal,
   
```bash 
exit
```
