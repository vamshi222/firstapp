FROM python:3 
ENV PYTHONUNBUFFERED = 1
RUN mkdir /firstapp
WORKDIR /firstapp
ADD . /firstapp
COPY ./requirements.txt /firstapp/requirements.txt
RUN pip install -r requirements.txt
COPY . /firstapp 
