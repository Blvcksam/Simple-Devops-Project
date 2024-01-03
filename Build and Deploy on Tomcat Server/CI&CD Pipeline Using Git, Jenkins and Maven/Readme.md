We Set up an Ec2 Instance , Logged in and Set up Java. I Connected to Ec2 instance using Mobaxterm.

We installed Java and Jenkins using Redhat Jenkins Procedure

A. we used a java code which is already available in our github account

B. we set up jenkins and maven as well

C. we integrated Github with jenkins:

- Installed Git on Jenkins Instance
- Installed Github Plugin on jenkins GUI
- Configured Git on Jenkins GUI

D. we integrated maven with Jenkins , so that we can pull the code unto jenkins and build with the help of maven

- we setup maven on jenkins server to reduce complexity
- we setup Environment Variables - maven is a java based application, Java is installed on jenkins server
- we set up java homepath and M2, M2_home( these are maven environment variables)
- we installed maven Plugin on jenkin GUI
- we configured maven and java on jenkins GUI
