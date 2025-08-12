
Added a cloned Flask application and created a Dockerfile for it.
![1](1-.png)


Ran the Flask app on port 5001.

![2](1.png)


The registration page appeared when accessing /register.

![3](2.png)


Created a Dockerfile for the Spring  application and displayed its contents.

![4](g-2.png)
run the spring bet on port 5001

![5](g--3.png)


Cat .dockerignore 

![6](g-3.png)

Run  docker ps to see spring and springwith ignore and the ports

![7](g--2.png)

Accessed the Spring bit app with .dockerignore in the browser on port 5000

![8](g--4.png)


Compared image sizes with and without .dockerignore and found the size was reduced when using with ignore

![9](size.png)

I made a new flask with a more dockerfile layers it is name is flask1 and cat the dockerfile
![10](1---1.png)

The rest of cat and the build command 
![11](1---2.png)

The size compare and they are the same !
![12](1---3.png)




