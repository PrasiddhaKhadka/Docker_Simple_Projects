FROM python:3.7

WORKDIR /app

COPY ./run.py /app/run.py

RUN pip install -r requirements.txt

ENTRYPOINT ["python", "run.py"]

CMD ["run.py"]