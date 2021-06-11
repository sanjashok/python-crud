# python-crud
This is a CRUD operation using Python and MySQL for DB

# Prerequiste
Python 2.7

# install dependencies
pip install flask
pip install flask-mysqldb

# To Run using Docker please install docker and run the Dockerfile using below commands
docker build -t <custom_image_name>:<tag> /path/to/Dockerfile 

# run docker image
docker run --publish 3000:3000 <custom_image_name>:<tag>