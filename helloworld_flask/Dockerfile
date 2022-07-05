FROM python:3.7.0-alpine   
# base image alpine

# WORKDIR /helloworld_flask     
# present working directory

ADD . /helloworld_flask    
#copy the content into the working dir

WORKDIR /helloworld_flask

RUN pip install -r requirements.txt     
#run pip to install the dependencies of the flask app

EXPOSE 8080

CMD ["python","app.py"]          
# define the coommand to start the container


