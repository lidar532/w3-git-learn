# w3-git-learn
Companion to the w3 school git training.
* Thia added with the github editor.
* This added on remote system.

Added 2023-0402-0951 -ww


Added 2023-0402-1156 -ww Added from deb-1

## Setup on device for git use with ssh.

1. Generate an ssh key pair
   > ssh-keygen -t ed25519
  
1. Copy th pub key file to github
3. Run the ssh-agent as follows:
   > eval \`ssh-agent\`
5. Run ssh-add 
   > ssh-add  ~/.ssh/id_deb-1-dev-2023-0402-ww
7. run 
   > git clone git@github.com:lidar532/w3-git-learn.git


At this point you should have a clone of the repository on your system.

Small change here.
