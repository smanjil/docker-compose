From python:3.7
ADD . /code
WORKDIR /code
RUN apt-get update
RUN apt-get install python3-pip -y
RUN pip install -r requirements.txt
CMD python app.py
