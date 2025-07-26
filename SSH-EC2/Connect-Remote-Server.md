## How to SSH (Secure Shell) into EC2 Instance?
SSH allows you to control/access a remote machine.

## WAY 1 - Directly on AWS Interface
Go to instances--> On top (click Connect)
<img width="931" height="681" alt="image" src="https://github.com/user-attachments/assets/8fe2f8e2-b4d1-4645-bdd2-b7b32b3d29a5" />

<img width="954" height="664" alt="image" src="https://github.com/user-attachments/assets/951b91ec-510a-4007-9eb8-c6efd8e88893" />
Now click "connect"

Here your new window is open
<img width="953" height="507" alt="image" src="https://github.com/user-attachments/assets/0a841809-402a-42bc-b8f3-35a43bcb39ae" />


## WAY 2 - Through your windows
Go to connect --> SSH Client
<img width="950" height="683" alt="image" src="https://github.com/user-attachments/assets/ff8eb415-b8fb-4534-ba52-2c2a817de4b9" />

Download Putty as a SSH Client

Open PuttyGen--> Load --> Select the .pem file downloaded
<img width="864" height="615" alt="image" src="https://github.com/user-attachments/assets/3ba379c7-02d9-4ce3-a7a8-870e15917d49" />

Then click save private key.
<img width="1035" height="689" alt="image" src="https://github.com/user-attachments/assets/682013fd-2eb2-4953-b79f-85e9e1d35b00" />s
save in .ppk format


Now open the main Putty app.
<img width="781" height="619" alt="image" src="https://github.com/user-attachments/assets/c1861a34-6f9f-4bd1-9f01-6cce4a9cdb36" />

In this it is asking for host name
in this add the public ip as listed 
<img width="949" height="670" alt="image" src="https://github.com/user-attachments/assets/072d6914-af55-4cff-b18e-dd14233464cb" />

Then on Putty app 
Go to SSH --> auth--> credentials 
<img width="636" height="560" alt="image" src="https://github.com/user-attachments/assets/a6d31cdc-b162-48c5-9f50-aeee91616861" />

For private key for authentication--> go to browse--> select the.ppk file -->
<img width="656" height="588" alt="image" src="https://github.com/user-attachments/assets/bba14db6-c711-486c-a8cd-7b41f932bf4d" />

Again go to the sessions1  
save the session
<img width="986" height="724" alt="image" src="https://github.com/user-attachments/assets/c7fd2ab0-6a3a-46bb-b03e-71c43aaa44a6" />
after entering your username(same in the interface)
<img width="965" height="859" alt="image" src="https://github.com/user-attachments/assets/7df4c2d3-2863-4fe6-a0fc-64366ee36447" />


Now everytime when you open the putty go to saved ones.
Do this to save the session for everytime so no need to login.
<img width="876" height="733" alt="image" src="https://github.com/user-attachments/assets/413c06a6-8b0d-4796-8c7e-c2ff9eaeda65" />



## PURCHASING OPTIONS:
<img width="708" height="416" alt="image" src="https://github.com/user-attachments/assets/f445c6b1-6fd8-4721-8ca1-a96de3ebc6ee" />
<img width="704" height="415" alt="image" src="https://github.com/user-attachments/assets/cb869955-e970-4bb1-9cb5-cb8b8c7fb5c6" />
