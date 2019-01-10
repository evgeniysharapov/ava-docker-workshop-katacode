You can also get this file onto a host by using bind mount 

`docker run -it -v $PWD:/appHost -v myvol:/app --rm busybox sh -c "cp /app/test.txt /appHost/."`{{execute}}

