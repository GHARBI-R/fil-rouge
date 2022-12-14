FROM python:3.6-alpine
MAINTAINER GHARBI Rima
RUN addgroup -S rima -g 433 && adduser -u 431 -S -G rima -s /sbin/nologin rima
ENV ODOO_URL https://www.odoo.com
ENV PGADMIN_URL https://www.pgadmin.org
WORKDIR /opt
ADD . /opt
RUN pip install flask==1.1.2
EXPOSE 8080
ENTRYPOINT ["python","./app.py"]
USER rima
