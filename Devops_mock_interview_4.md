GIT
---------------
1. What is git reset ? Types of reset ?
           
3. How to delete local branch  and remote branch in git ? 

     git brach - a ( to show all branches)
     git branch -D (name of the branch)
5. Difference between git diff and git status ?
   git diff -compare
   git status - status e.g staging, commit
7. What are hooks in git? 
 special commits that will be excuted after certain event
 

MAVEN
--------
5. What are things you need to set, if you want download dependency from private repository ?
6. What are the issues you faced while working on maven projects?
7. Command to skip the test cases in maven

JENKINS
----------
8. How to set Jenkins build to fail based specific word in console output ?
9. What are active and reactive parameters (Dynamic parameterization) in Jenkins ?
10. How to customize the build number display to something else in Jenkins job page?
11. What are multi branch pipeline?
12. What is shared library in Jenkins ?


UNIX & SHELL SCRIPTING
-----------
13. Command to find empty files in a given directory?
 
          -excute ssh -keygen
     -answer the promts 
      - cd ~/ .ssh/
      -ls (id rsa, id rsa.pub)
         -ssh-copy-id username then ip
     other files present 1) id rsa, id rsa.pub, kwnown-lost, Authorize -key
19. Commands you will use it for configuring ssh connectivity between 2 machines and what files will be present in .ssh folder?
               -excute ssh -keygen
     -answer the promts 
      - cd ~/ .ssh/
      -ls (id rsa, id rsa.pub)
         -ssh-copy-id username then ip
     other files present 1) id rsa, id rsa.pub, kwnown-lost, Authorize -key
21. How to schedule a shell script in unix machines?
     using crontab
                crontab -e (google crontab guru) enter the digits copy and enter in crontab -e editor
                choose one of the editors 
                
        
23. Command to get load average ?
         top    
25. Need to identify ip addresses in log file and count of ip addresses in log file?
 grep -E

       

ANSIBLE
------------
18. Why ansible ? What makes ansible powerful than other tools like chef and puppet?
19. 5 modules that you have worked on? Can we create custom module ?
20. What is dynamic inventory in ansible?
21. Lets say I have both Ubuntu and centos machines as nodes I want install application tree using same playbook, how would you approach this scenario? 
22. How to handle prompts with ansible playbook?

DOCKER
----------
23. What does ONBUILD instruction do in Dockerfile?
24. What is the use of .dockerignore file?
25. I have dockerfile that accepts arguments, if I supply value as “1” then it should use maven 2.x version for base image and if I supply “2” then it should take maven latest as base image 
26. What are docker compose and docker swarm?

KUBERNETES
---------
27. Components in kubernetes architecture?
28. What are stateful sets in kuberentes?
29. Command to find which container has failed in pod and command to get logs of container 
30. Tools to maintain kubernetes log files 

AWS
-----
31. Services used AWS and tasks performed in AWS
