!#/bin/bash
gradle build
cp /home/tcluri/mygram/website/website/build/libs/website.war /home/tcluri/mygram/website/container/
docker build -t mygram/website /home/tcluri/mygram/website/container/ 

docker push mygram/website




