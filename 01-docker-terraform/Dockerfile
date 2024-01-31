FROM python:3.10

RUN apt-get install wget
RUN pip install pandas sqlalchemy psycopg2

WORKDIR /app

COPY simple_pipeline.py simple_pipeline.py

ENTRYPOINT [ "bash", "simple_pipeline.py"]