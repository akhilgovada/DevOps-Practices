﻿# My AWS EC2 Instance Setup
step-1 : Create an aws account, login to account
         create an Ec2 instance with the region N.verginia(my choice)
         instance type t2.micro
         select the machine with 8gb volume
         Give the name of your choice
         select the machine      #amazon linux in my case
         Generate the keypair    #in my case it is gitpractice
         It will automatically download the keypair into your local
         Allow SSH traffic

Step-2 : open visual studio code 
        dowload the remote-ssh extension
        connect the remote system with this extension
        give host # name (myec2)
             hostname  #IP address from the ec2 instace you have created
             user  #name from the instance (ec2user)
             identityfile #location of the keypair you have downloaded

        save this data and connect to the host

step-3 : download git in your remote system
        to download "sudo yum install git -y"
        Initialize git "git init"
        Verify Remote Repository # to verify that your local repository is linked "git remote -v" this command will list the remote repositories
Step -4 : Commit the changes "git commit"
      
step-5 :Push Your Code to the Remote Repository #"git push -u origin main"
        you can check your code in github in your repository (master branch)
        
