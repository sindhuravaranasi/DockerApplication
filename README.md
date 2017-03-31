
##Docker IMAGE of Project1##

This Project will allow you to migrate that WebService into a docker container instance, that acts as a more portable and modular framework for hosting services.
##STEPS TO RUN THE IMAGE: 
1.DOWNLOAD THE IMAGE FROM THE URL https://drive.google.com/open?id=0B9zraS48eIpEaUp5WTVtTHBPcDg<br>
2.Install the docker in aws environment.<br>
3.Install (as root): yum install docker-io.<br>
4.Start the docker service (as root): service docker start.<br>
5.Docker load -i weather.tar.<br>
6.New image will be created and displays the container id.<br>
7.Copy the newly created id(visible below the docker load command).<br>
8.Docker run -d -p 8081:80 <copied id> <br>
9.Check in the browser with your instance ip.<br>



	


