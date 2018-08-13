# docker-tips

## To access the file system of the container that is not currently running, follow the steps below,
`docker commit CONTAINER NEWIMAGENAME`
`docker run -ti --entrypoint /bin/bash NEWIMAGENAME`
