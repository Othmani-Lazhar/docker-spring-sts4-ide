# spring-sts4-ide
Dockerfile and scripts needed to build, run and exec into Docker Container containing Java 8 + Spring Tools 4 IDE + git +maven.

This Docker Container is treated as an executable, mainly starting STS4 IDE as a GUI via X11.


RUN CONTAINER 
==============
In order to run the STS4 container, run script ...

./run.sh

You should see the Spring Tools 4 Splash screen show up 
after the initial Docker image download from DockerHub



GETTING INTO CONTAINER 
=======================
You can get into the container once its up with script ...

./exec.sh

You'll find yourself in a bash shell



RE-BUILDING IMAGE
=================
If ever you wanted to change the username "mvpjava" or anything
else in the Dockerfile, you could run script ...

./build.sh



Note: You will have to make the scripts executable from the command line via ...

chmod 755 $script_name
