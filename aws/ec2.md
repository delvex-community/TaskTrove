# AWS VM  task 
<details>
<summary>View</summary>

```bash
1. create amazon linux machine with t2.micro type .
2. setup apache httpd server in this machine .
3. Here are few changes you have to do in httpd config file.
    - change port number of 1234
    - change documentroot to /opt/data/html/
4. create user named "delvex" with home directory  /opt/data/html/
5. make sure user can login with password "Hello@123" using ssh
6. in your laptop clone this github repo "https://github.com/redashu/ashu-webui-bmoapp.git" 
7. scp this directory to /opt/data/html/ using delvex user
8. now finally verify that you are able access web page which you have transfered to above directory
```
</details>



# AWS VM  disk task  
<details>
<summary>View</summary>

```bash
1. create amazon linux machine with t2.micro type and attach 10GB EBS disk also mount this DISk to /opt/data/web/
2. setup apache httpd server in this machine .
3. Here are few changes you have to do in httpd config file.
    - change port number of 1235
    - change documentroot to /opt/data/web/
4. create user named "delvex" with home directory  /opt/data/web/
5. make sure user can login with password "Hello@123" using ssh
6. in your laptop clone this github repo "https://github.com/redashu/ashu-webui-bmoapp.git" 
7. scp this directory to /opt/data/web/ using delvex user
8. now finally verify that you are able access web page which you have transfered to above directory
```
</details>

