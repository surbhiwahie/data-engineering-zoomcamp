FROM python:3.9 

RUN apt-get install wget
RUN pip install pandas sqlalchemy psycopg2


WORKDIR /app
COPY Ingest_data.py Ingest_data.py

ENTRYPOINT [ "python", "Ingest_data.py" ]