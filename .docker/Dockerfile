FROM python:3.8

RUN apt-get update -y && apt-get upgrade -y

COPY requirements.txt .
RUN pip3 install --upgrade pip && \
    pip3 install --no-cache-dir -r requirements.txt

WORKDIR /home/mycode/
