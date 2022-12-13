FROM python:3.6-alpine
MAINTAINER GHARBI Rima
ENV ODOO_URL= https://www.odoo.com
ENV PGADMIN_URL= https://www.pgadmin.org
WORKDIR /opt
ADD app.py /opt
RUN pip install flask==1.1.2
EXPOSE 8080
ENTRYPOINT ["python","./app.py"]
