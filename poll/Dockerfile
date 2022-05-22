FROM python

RUN mkdir /app
WORKDIR /app

ADD src /app

RUN pip install --upgrade pip --no-cache-dir
RUN pip install -r requirements.txt --no-cache-dir

EXPOSE 80
CMD flask run --host=0.0.0.0 --port=80