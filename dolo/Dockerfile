FROM ubuntu:22.04

RUN apt-get update -y
RUN apt-get install -y python3-pip
RUN pip3 install pytsk3

WORKDIR /app

COPY src/ .

CMD ["python3", "main.py"]
