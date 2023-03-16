# jenklins pipeline to build the spring-petclinic project with maven and do the quality tests with sonarcloud
# steps to write the jenkins pipeline
GIT stage [![git url](https://github.com/nagendra4aa5/spring-petclinic.git)]
mention the branch name as "develop"

# To build the spc with maven
If we run with maven wrapper command
```
./mvnw package

```
If we build normally
```
mvn package

```
Note:-Before build the code,Java 11 or newer and maven 3.9.0 should be installed in the machine

```
sudo apt-get update 
sudo apt install openjdk-17-jdk -y

```
For maven 3.9.0
```
Wget https://dlcdn.apache.org/maven/maven-3/3.9.0/binaries/apache-maven-3.9.0-bin.tar.gz
tar zxvf apache-maven-3.9.0-bin.tar.gz
sudo mv apache-maven-3.9.0 /opt/maven
sudo vi /etc/environment
source /etc/environment
mvn --version

```
# To run with sonar cloud, need to add sonar cloud account and configure it with jenkins
[!To open[sonarcloud page](https://sonarcloud.io/)]
<img width="1042" 
alt=sonar1
src="D:\spc documentation\sonar1.png"



