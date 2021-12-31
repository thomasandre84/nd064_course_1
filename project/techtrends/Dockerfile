FROM python:2.7
LABEL maintainer="Thomas Andre"
EXPOSE 3111

COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt
RUN python init_db.py

CMD [ "python", "app.py" ]
