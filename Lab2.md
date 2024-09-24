# LAB 2
#### Student name: Nguyễn Huỳnh Quốc Bảo
#### Student ID: 22110010
## ctf
### Here we have the source code of ctf
![alt text](./Image/ctf.png)
### Stack frame in ctf
![alt text](./Image/stack-frame-ctf.png)
### Ways to do ctf
![alt text](./Image/how-to-do-ctf.png)
#### Create ctf.out file
![alt text](./Image/create-ctf.png)
#### Now we use objdump to get address of myfunc function. After that, we use gdb and make a breakpoint
![alt text](./Image/breakpoint-ctf.png)
#### The code shows that within the function myfunc, there's a check for the file flag1.txt. If we attempt to overwrite it at this point, the following will occur
![alt text](./Image/code-ctf.png)
#### If we want to advoid it, we must create flag1.txt file
![alt text](./Image/create-flag1.png)
#### Use r echo to modify the return address of vul and redirecting it
![alt text](./Image/return-add-ctf.png)
![alt text](./Image/return-add-ctf1.png)
#### Now we will need to set p and q value 
![alt text](./Image/set-pq-ctf.png)