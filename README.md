# docker-demo 

Docker Installation in Ubuntu Machine

Step1:

sudo apt-get install apt-transport-https ca-certificates   curl  software-properties-common
    
    
Step2:

Add Docker’s official GPG key:

$ curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -


Step3:

Add repository:


sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu  $(lsb_release -cs)  stable"
   
 
Step4:

Install docker 

sudo pt-get update

sudo apt-get install docker-ce
