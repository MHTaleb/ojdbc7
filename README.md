# ojdbc7
ojdbc driver


#install


please download this ojdbc driver then respect the following instruction :

 1- go to your maven local repository in "c:\users\[your session user]\.m2\com\oracle"

2- create new folder called : ojdbc7

3- paste the driver in the previsous created folder

4- launch the cmd in privileged mode

5- tape : mvn install:install-file -Dfile=c:\users\[your session user]\.m2\com\oracle\ojdbc7\ojdbc7.jar -DgroupId=com.oracle -DartifactId=ojdbc7 -Dversion=12.1.0 -Dpackaging=jar

6-go to pom.xml in your maven project and add the dependency :
 
 <dependency>

      <groupId> com.oracle </groupId>

      <artifactId> ojdbc7 </artifactId>

      <version> 12.1.0 </version>

      <packaging> jar </packaging>

</dependency>


7-clean and build your project


enjoy :)

edited by MHT
