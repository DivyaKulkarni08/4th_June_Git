```                                                                      
#             .___      __     _____          __                         __  .__               
#    ______ __| _/_____/  |_  /  _  \  __ ___/  |_  ____   _____ _____ _/  |_|__| ____   ____  
#   /  ___// __ |/ __ \   __\/  /_\  \|  |  \   __\/  _ \ /     \\__  \\   __\  |/  _ \ /    \ 
#   \___ \/ /_/ \  ___/|  | /    |    \  |  /|  | (  <_> )  Y Y  \/ __ \|  | |  (  <_> )   |  \
#  /____  >____ |\___  >__| \____|__  /____/ |__|  \____/|__|_|  (____  /__| |__|\____/|___|  /
#       \/     \/    \/             \/                         \/     \/                    \/ 
```

# seleniumJava
Selenium Startup Project for Java


Introduction
------------
This project is made for anyone who is looking for a starting point for writing functional tests using Selenium WebDriver and Java.  

Maven Java Project
-----
This project is written in Java and tests can be executed using Maven commands. 

    mvn clean
    mvn test

Page Object Model
-----
Page object model is used in this framework.  Each web page will have its own java.class and within each class contains page element mappings and functions / methods used to interact /verify a specific web page under test.  


Test web page
-----
    http://the-internet.herokuapp.com/      

   
Continuous Integration(CI)
------------
A web hook has been setup with Travis CI for all Push and Pull Requests.
 
 
Selenium WebDriver
------------
This project is configured to use Firefox & Chrome WebDriver's.  The default is set to Chrome.  The WebDriver exe's added to this project will only work on macos.  


Selenium Grid
------------
Tests in this solution can also run on the Selenium Grid.  Selenium Grid is hosted by www.gridlastic.com.

Questions / Contact / Contribute
------------
Feel free to fork this repo, add to it, and create a pull request if you like to contribute.  

If you have any questions, you can contact me via email: `sdet.testautomation@gmail.com`