FROM ubuntu


RUN apt-get update -y
RUN apt-get install -y python python-pip
RUN pip install flask

COPY app.py /opt/app.py

ENTRYPOINT FLASK_APP=/opt/app.py flask run --host=0.0.0.0

#     1  apt-get update
#     2  apt-get install -y python
#     4  apt-get install python-pip
#     6  pip install flask
#     7  create/copy app code to /opt/app.py
#    10  FLASK_APP=/opt/app.py flask run --host=0.0.0.0
