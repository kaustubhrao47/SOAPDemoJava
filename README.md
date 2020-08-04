# SOAPDemoJava

Technology: Java, SOAP(Simple Object Access Protocol) <br/>
IDE: Eclipse IDE for Enterprise Java Developers ; Version: 2020-06 (4.16.0) <br/>
JDK: 12 <br/>
JRE: 1.8.0 <br/>
Server: Apache Tomcat 8.5.57 <br/>

## What is this?
&nbsp;&nbsp; This repository contains practical implementation example for SOAP concept in java. <br/>

## Working
&nbsp;&nbsp; This project demonstrates that SOAP can be used to integrate a specific action to any project. Here calculator method is implemented. A "calculator.wsdl" file is created which can be consumed in any project using web services client. The project is created using web server.

## Steps to run:
* Open Eclipse IDE <br/>
* Change perspective to Java EE <br/>
* Create a new "Dynamic Web Project" </br>
* Create Java class and interface class. Copy paste all the codes as per below file structure. <br/>
![alt text](https://github.com/kaustubhrao47/SOAPDemoJava/blob/master/File-Structure-SOAPDemoJava.JPG?raw=true) <br/>
* Create a new "Web Service" on SOAPDemo to generate SOAPDemoClient <br/>
**_NOTE:_** Select the below settings: <br/>
  * Set service level of service and client generation to full i.e. Test Service and test Client respectively.
  * Web Service Type:Bottom up Java bean Web Service.
* You can test "Calculator.wsdl" file using postman or SOAP UI.
* Visit Link: http://localhost:8080/SOAPDemo/services/Calculator?wsdl to view ".wsdl" file.

## Download Links
* Postman: https://www.postman.com/downloads/
* Eclipse IDE: https://www.eclipse.org/downloads/packages/release/neon/3/eclipse-ide-java-ee-developers
* Java Development Kit: https://www.oracle.com/java/technologies/javase/jdk12-archive-downloads.html
* Java Runtime Environment: https://www.oracle.com/java/technologies/javase-jre8-downloads.html

## Contributing
&nbsp;&nbsp; Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change. <br/>
&nbsp;&nbsp; Please make sure to update tests as appropriate.

## License
&nbsp;&nbsp; [MIT](https://choosealicense.com/licenses/mit/)
