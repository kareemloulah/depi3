# run a container from mariadb image 
(/Picture3.png)
first try failed because we need to pass MARIADB_ROOT_PASSWORD as an enviroment variable 
so we run it again and also specify the ports and a container name 
command 
docker run --name kareem-mariadb -d -e MARIADB_ROOT_PASSWORD='kareem01' mariadb:latest

# run another container but with different port 
(/Picture2.png)
# To get the default open port for any image 
(/Picture1.png)
command Docker image inspect <imagename>
under ExposedPorts 
