# Node.js Server


 ### Building

```
 $ docker build -t <NODESERVER_IMAGE_NAME> github.com/jaquiel/docker-node-server
```

### Running

```
 $  docker run -it -p 3000:3000 --name <NODESERVER_CONTAINER_NAME> <NODESERVER_IMAGE_NAME> 
```

**OR** **(with --rm to remove the container after stop it)**


```
 $  docker run -it -p 3000:3000 --rm --name <NODESERVER_CONTAINER_NAME> <NODESERVER_IMAGE_NAME> 
```
