# linux_permission 

## Solve the problem 

<details>
<summary>Click to Permission </summary>


```bash
# Steps to create and manage a user
1. Create a user named `<yournamep1>` with the following details:
    - Assign any user ID in the range of 9001 to 40001.
    - Set the shell for this user to `/bin/bash`.
    - Set the password for this user to `Hello@12345`.

2. Login with this user using the `su` command.

3. Perform the following actions:
    - Create folders custom_commands.
    - copy  date , cal , mkdir , rmdir commands to custom_commands folder.
    - add  custom_commands folder to your PATH variable permanently
    - Now modify permission of commands which you copied as given conditions.
    - yournamep1 must not able to run mkdir and rmdir commands 
    - make sure user can only run those command which you have copied except mkdir and rmdir 
    - 
```

</details>


## Create use case 

<details>
    <summary>Mind game</summary>

bash```

1. using root user  create a folder called /common/data and perform below steps
    -  create two users <yournameu11>   <yournameu22> 
    - create a group called manager 
    - change group of /common/data folder to manager 
    - both the users must be part of manager group 
    - owner of /common/data must be root 
2. Perform following action for permission 
    - make sure manager group members can do read write and execute in above directory
    - create some files and folder by each user 

```
</details>
