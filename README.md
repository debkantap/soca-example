This repo holds the portal created by soca utility.

  https://github.com/debkantap/soca
  
It holds the dockerfile to create the image from the portal to run on tomcat file. 

Here are the instructions to run it on docker.

--Clone the repository

https://github.com/debkantap/soca-example.git

go to "soca-example\debkantap-portal"

--to build the image

docker build -t my-soca-app .

---to run the image

docker run -d -p 8082:8080 my-soca-app

Once the container is up and running on docker the portal can be accessable:

http://locahost:8082
