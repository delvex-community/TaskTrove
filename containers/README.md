#  Containers_assignments 

###  Container data copy 

<details><summary>show</summary>
<p>

```bash
  1. Create two containers named with  <yourname>c1 and <yourname>c2
  2. choose whatever docker image you want to 
  3. choose whatever parent process 
  4. In container 1st create a file called  helloc1.txt , file must contain some data 
  5. now copy helloc1.txt to  2nd container 
```

</p>
</details>
  
  
 ###  Container with Cgroups

<details><summary>show</summary>
<p>

```bash
  1. Create one container named with  <yourname>cg1 
  2. choose busybox as docker image
  3. choose any parent process that must run for atleast 20 minutes 
  4. container must not exceed more than 30% of single core CPU 
  5. after container creation update max use RAM usage to 300MB for this container 
  6. After RAM update  in this container also update restart policy to always for this container 
```

</p>
</details>
  
  
 ###  From Container to Docker image 

<details><summary>show</summary>
<p>

```bash
  1. Create a container named  <yourname>cimg 
  2. choose oraclelinux:8.4 as docker image
  3. Install vim and httpd software inside a running container 
  4. Now create a docker image from this running container 
  5. make docker image and be sure this docker  image name must be  <yourname>cimg:v007  
  6. check it by docker images
  7. create a container from this imaeg  by whatever name 
  8. choose any process so that container can keep running 
  9. after container creation change its restart policy to "always"
  10. check restart policy that it got updated 
  11. if all setup then push this image to dockerhub on your personal account 
```

</p>
</details>

 ###  Container with output check 

<details><summary>show</summary>
<p>

```bash
  1. Create one container named with  <yourname>cg1 also use "-d" option to put container in background 
  2. choose busybox as docker image
  3. choose  parent process of container as  "uname -r" 
  4. now check the output of process which you given in  your container 
  5. store that output in a file <yourname>task1.txt in /tmp/<yourname>task1.txt in docker host machine 
 
```

</p>
</details>
  


# docker_assignments

## Image building assignment 

### Build and Image 

<details>
<summary>show</summary>
 <p>

  ```bash
      1. Create a dockerfile named alpine.dockerfile 
      2. use alpine as base image 
      3. install python3 
      4. create a directory called /pycodes
      5. copy sample python code into above created directory 
      6. maintainer parent process by CMD 
      7. build image by the name  <yourname>alp:pycodev1 
      8. create a container from the build image and check the output of your python program
      9. make sure you push this image under your dockerhub account 
  ```
 </p>  
 
### python code link 
[pythoncode](https://raw.githubusercontent.com/redashu/pythonLang/main/while.py)
</details>


### Multi stage Image build 

<details>
<summary>show</summary>
 <p>

  ```bash
      1. Create a dockerfile named alpine.dockerfile 
      2. use alpine as base image 
      3. install python3 
      4. create a directory called /pycodes
      5. copy sample python code into above created directory 
      6. maintainer parent process by ENTRYPOINT 
      7. build image by the name  <yourname>alp:pycodev1 
      8. create a container from the build image and check the output of your python program
  ```
 </p>  
 
### python code link 
[pythoncode](https://raw.githubusercontent.com/redashu/pythonLang/main/while.py)
</details>



