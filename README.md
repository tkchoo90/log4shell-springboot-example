# Log4Shell vulnerability demo on Springboot project

This is a sample springboot application that be used to demostrate Log4Shell. 
Taken reference from https://github.com/christophetd/log4shell-vulnerable-app, except:
* this project has been changed to build with Maven
* Inside main(), a line System.setProperty("com.sun.jndi.ldap.object.trustURLCodebase", "true"); has been added to demostrate the vulnerability on later versions of Java

