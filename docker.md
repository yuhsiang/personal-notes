### Remove all images
```
docker rmi $(docker images -qf "dangling=true")
Kill containers and remove them:

docker rm $(docker kill $(docker ps -aq))
```
Note: Replace kill with stop for graceful shutdown

### Remove all images except "my-image"

You could use grep to remove all except my-image and ubuntu
```
docker rmi $(docker images | grep -v 'ubuntu\|my-image' | awk {'print $3'})
```
### Add person to docker
```
sudo usermod -aG docker $USER
```
### Connect to mongo
```docker run -it --link mongo --rm mongo sh -c 'exec mongo 127.0.0.1:27017'```
