**Basic commands:**

1.pwd:The pwd command is used to display the current working directory or identify your current location in the file system.




2.ls(list):Displays only file and directory names.

<img width="1640" height="59" alt="image" src="https://github.com/user-attachments/assets/cff9697b-14b5-483f-a5fa-fc7fff4bff52" />

3.ls -l / ll (both are same) :Long listing:Shows detailed information such as permissions, owner, group, size, and modification date.
file names in ascending order

<img width="569" height="411" alt="image" src="https://github.com/user-attachments/assets/050a67b8-b142-4192-b31d-9c0ed9bb5f6b" />




drwxr-xr-x
│││


││└── Permissions
│└──── Directory (d)
└───── File type




3          -> Number of links

idsldtst   -> Owner

mwis       -> Group

228        -> Size (bytes)

Sep 12 2023-> Last modified date

idsLoader_crvws -> File/Directory name

4.ls -lrt :Long listing + reverse time sort
Sorts files by modification time (oldest first because of -r).
latest file which we created can be given at last

<img width="601" height="407" alt="image" src="https://github.com/user-attachments/assets/dcf5d8e5-d38d-46a3-8c67-02b9abb2e50f" />

5.ls -a:All files.Shows all files, including hidden files (those beginning with .).

<img width="1548" height="76" alt="image" src="https://github.com/user-attachments/assets/5c1f1ec4-d584-433c-8d5b-5247da94d9ce" />

6.Uname:The uname command is used to display system information.

<img width="492" height="61" alt="image" src="https://github.com/user-attachments/assets/21fdf7a0-d37e-48e6-a130-ee36b3b66246" />

<img width="552" height="60" alt="image" src="https://github.com/user-attachments/assets/f9bfab69-cbf4-42eb-a752-087178e9b930" />

Note: uname -r shows the kernel release version.

7.cd:The cd command is used to change the current directory.

8.clear:The clear command clears the terminal screen, providing a clean workspace.

9.whoami:The whoami command displays the current logged-in user.

<img width="523" height="58" alt="image" src="https://github.com/user-attachments/assets/19108d71-33e8-40f0-95c9-fe309d5b1624" />

10.History
The history command shows previously executed commands.

<img width="858" height="284" alt="image" src="https://github.com/user-attachments/assets/8267caee-6111-4ac1-85b1-6c5875024a04" />

11.Free:The free command is used to check memory usage.

<img width="1038" height="99" alt="image" src="https://github.com/user-attachments/assets/7e1c53bb-f0c8-4be7-85d1-0b8446ef81fa" />

12.nslookup:it is used to obtain information for DNS server.It stands for Name Server Lookup.

command:nslookup <domain name>
<img width="882" height="271" alt="image" src="https://github.com/user-attachments/assets/db1e7ad0-d8fc-4aed-ab78-f05402123acf" />

13.ssh-keygen -t rsa :The ssh-keygen command generates SSH public/private key pairs.

14.Curl:The curl command is used to transfer data from or to a server.

command:curl [options] [URL]
15.curl -o:curl -o flag saves the data into a file on the local machine.

command:curl -o [file_name] [URL...]

16.du:du command is used to check disk usage space.

17.df:df command is used to check the available disk space in system.

command:df -h

18.ifconfig :it is used to view the information about your network interface.
you will check the ip address from here

19.ip










