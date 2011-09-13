Prerequisites
=======
Maven 
-------
install Maven, check http://maven.apache.org/

Mac OSX user, if you have installed homebrew

	$ brew install maven

Run
=======
step 1
-------
open "com.yourdomain.webcanvas.config.AppConfig"
change APP_ID,API_KEY,APP_SECRET according to your app setting

step 2
-------
search and replace "www.yourdomain.com" to your renren app website host

step 3
-------

	$ mvn compile

step 4
-------
default port is 8080, because on Mac OSX, port 80 is restrict for admin user, you should add 'sudo' if you stick with 80 port, you can change port number in pom.xml

	$ mvn jetty:run
	