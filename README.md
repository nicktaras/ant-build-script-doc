# ant-build-script-doc

Build Scripts Using Html5 Boiler Plate and Ant.
Why build?
Combines and minifies; Javascript, CSS, Html and image files.
Versions each build to ensure the user will see the latest version of the project online.
Allows for various builds for staging and development.
Getting Started
	Download: 
Html5 boiler plate http://html5boilerplate.com/
Ant http://ant.apache.org/
Ant Build Script https://github.com/h5bp/ant-build-script
Java JDK http://www.oracle.com/technetwork/java/javase/downloads/index.html
Make Build
Install the Java JDK
Install Ant
Open the Html5 boiler plate directory and create a folder called “build” in the root.
Unzip then, copy and paste the Ant Build script contents inside the build folder.
When you are ready to make a build, open the command prompt or using Gitbash
Go to the location of the project e.g. C:\Users\Nick\boilerPlate\build
Run the command – ant build / ant text (to build the text part only)
Modify build to include/exclude files
Open the project.properties file
Here you will see areas to add, html files, css style sheets (although try to #include these in the css instead)
Also there is an area where you can list files to exclude from the build.
To list the files use the following syntax – about.html,contact.html,checkout.html
Additional
.htaccess  contains expiry dates

Last updated 11/04/2013 


