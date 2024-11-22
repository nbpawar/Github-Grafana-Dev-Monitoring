# Github-Grafana-Dev-Monitoring
This is the DevOps monitoring github repo in grafana
Firstly creating the Ubuntu instance having 25 gb storage and the security group port 
1000-11000
80
500-1000
443
22
attach the key pair and launch the instance.

Connect the Ec2 instance by using ssh
after fetch some commnad to install the grafana monitoring tool
#sudo apt update
#sudo apt-get install -y adduser libfontconfig1 musl
#wget https://dl.grafana.com/enterprise/release/grafana-enterprise_11.3.1_amd64.deb
#sudo dpkg -i grafana-enterprise_11.3.1_amd64.deb

start the grafana 
enable the grafana

 localhost:3000/login

go to the github setting and generate the token for the grafana 
tokan id put on grafana 
after that its dashboard taking lot of time 
so go to google chrome and github dashboard grafana copy the id and paste on the grafana server dashboard to display as early as possible showing the pull request mearge push pull pending etc


 

