# dockerfiles
##Flask
cd Flask
docker build -t flask .
docker run -itd -p 5000:5000 flask
docker ps
firefox http://0.0.0.0:5000
