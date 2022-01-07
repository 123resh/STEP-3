# STEP-3
TO SETUP JUPITER IN DOCKER CONTAINER
First of all pull the jupyter Notebook by using the below command:
$ sudo docker pull jupyter/scipy-notebook
To run jupyter:
$ sudo docker images
Now copy the "IMAGE ID" OF Jupyter/scipy-notebook from listed images
Now run the below command to run the jupyter notebook
$docker run -rm -p 8888:8888 -v -$(pwd) 0b4387b47d86
Now go to the browser and type the following
localhost:8888
Finally copy the token from terminal running jupyter notebook
