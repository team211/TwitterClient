TwitterClient
=============

COMP3111 Project - team211

Running a Jar file from the other team

1) Download the other team's jar file into your project directory. 

2) Change your build.xml file line 131 from: 

    <target name="run-jar" depends="jar">
    to 
    <target name="run-jar" depends="">
    And save it.
    
3) Remove everything within the bin directory

4) Execute command: ant run-jar


========
********If you cannot see any icon when running:
========

1) Execute two commands:

  (1) cd bin
  
  (2) jar xf ../hk.ust.cse.TwitterClient.jar
  
2) Go back to your project directory and execute command: ant run-jar
