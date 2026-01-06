# Active-Directory-Lab-Part-3
In this part of the lab I will be exploiting a system vulnerability and checking the logs that it creates in splunk. I will be performing a brute force attack that will expose the windows 10 machines and allow access.

The fist thing we will do is turn on the Kali Linux virtual machine. Then we are going to open the terminal and make a directorty with mkdir <directory-name>. Then we will install crowbar with the command sudo apt-get install -y crowbar and type in the defalut Kali Linux password. Now we are going to get a list of common passwords from our newly downloaded crowbar software. To do this we will enter in the command cd /usr/share/wordlists/ 

<img width="641" height="252" alt="image" src="https://github.com/user-attachments/assets/3ef90290-40f5-411e-830b-b4b45f2153a6" />

Then we will unzip the rockyou.txt.gz with gunzip. The command is sudo gunzip rockyou.txt.gz and the output will be rockyou.txt. Moreover, we will copy the rockyou.txt file to our newly created directory using the command cp rockyou.txt ~/Desktop/ad/. Now we will cd into our newly created directory with the command cd ~/Desktop/ad. Then we will take the first 20 entries in the file and copy it over to password.txt with the command head -n 20 rockyou.txt > password.txt. 

<img width="642" height="515" alt="image" src="https://github.com/user-attachments/assets/31e07e75-075f-4322-ae3f-feef11a6785a" />
