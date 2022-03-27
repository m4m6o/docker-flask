FROM python:3.7.4

COPY app /app
WORKDIR /app

RUN pip3 install --upgrade -r requirements.txt

COPY app /app
ENTRYPOINT ["python3"]
CMD ["app/app.py"]
