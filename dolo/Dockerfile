FROM ubuntu:22.04
RUN apt-get update -y
RUN apt-get install -y python3-pip
ADD ./src/main.py .
RUN pip3 install pytsk3
CMD ["python", "./main.py"]
