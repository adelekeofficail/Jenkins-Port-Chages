# Jenkins-Port-Chages
Charging Port In Jenkins
1. Go to /etc/default folder --> Open the file "jenkins"
2. Modify the line HTTP_PORT=8080 as HTTP_PORT=80
3. Start jenkins by command: /etc/init.d/jenkins start
4. Open a browser and browse as localhost:80
systemctl edit jenkins then then go # Environment="JENKINS_PORT=8080"
to chnage port 
