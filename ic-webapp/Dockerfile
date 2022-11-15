FROM python:3.6-alpine
MAINTAINER GHARBI Rima
WORKDIR /opt
ADD app.py /opt
RUN pip install flask==1.1.2
EXPOSE 8080
ENTRYPOINT ["python","./app.py"]