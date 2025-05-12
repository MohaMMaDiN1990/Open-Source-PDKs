------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

 This is what I have concluded from running this open source pdks:
 After pulling the image from the docker, I shall execute the command (making a container from the image) in the Terminal Command with the following commands:
 
 First command:
 docker run -it -p 80:80 --user $(id -u):$(id -g) -v $DESIGNS:/Users/mohammad.i.nassiri/open_pdks hpretl/iic-osic-tools:latest -w

Second Command:
docker run -it -p 80:80 --user $(id -u):$(id -g) hpretl/iic-osic-tools:latest
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
