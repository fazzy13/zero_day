# vagrant 

## Overview
This readme file provides instructions on how to create a new directory called 0x00-vagrant inside the zero_day repository and add a README.md file to it. Additionally, it provides instructions on how to SSH into an Ubuntu VM and run the uname command to check the output.

## Creating the 0x00-vagrant Directory
To create a new directory called 0x00-vagrant inside the zero_day repository, please follow these steps:

Open your terminal and navigate to the zero_day repository by running the cd command followed by the path to the repository.

Once you are inside the zero_day repository, run the following command to create a new directory called 0x00-vagrant:

`mkdir 0x00-vagrant`

Now that you have created the new directory, navigate into it by running the following command:


`cd 0x00-vagrant`
Finally, create a new README.md file inside the 0x00-vagrant directory by running the following command:


`touch README.md`
SSH into Ubuntu VM and Running uname Command
To SSH into an Ubuntu VM and run the uname command, please follow these steps:

Open your terminal and run the following command to SSH into the Ubuntu VM:

`vagrant ssh`
Once you are inside the Ubuntu VM, run the uname command without any option by typing the following command:


`uname`

The output of the uname command will print the name of the operating system you are using. Type the name of the operating system into a file in the 0x00-vagrant directory and push it to GitHub.

```
echo "Ubuntu" > operating_system.txt
git add operating_system.txt
git commit -m "Added operating system information"
git push
```
## Conclusion
These instructions should help you create a new directory called 0x00-vagrant inside the zero_day repository and add a README.md file to it. Additionally, it should help you SSH into an Ubuntu VM and run the uname command to check the output. If you have any questions or concerns, please feel free to reach out to your mentor or the support team.
