# run a container from mariadb image 
![sc](Task4/Picture3.png)
first try failed because we need to pass MARIADB_ROOT_PASSWORD as an enviroment variable 
so we run it again and also specify the ports and a container name 
 
```
docker run --name kareem-mariadb -d -e MARIADB_ROOT_PASSWORD='kareem01' mariadb:latest
```
# run another container but with different port 
![sc](Task4/Picture2.png)
# To get the default open port for any image 
![sc](Task4/Picture1.png)
```
Docker image inspect <imagename>
```
under ExposedPorts 
