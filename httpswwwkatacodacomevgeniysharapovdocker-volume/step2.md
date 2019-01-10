Use the volume when you run container 

`docker run -it -v myvol:/app --rm busybox sh -c "echo Hello > /app/test.txt"` {{execute}}

Now you have a file in the volume

You can see this file by running 

`docker run -it -v myvol:/app --rm busybox sh -c "cat /app/test.txt"` {{execute}}


