from python:alpine3.16

WORKDIR /app

COPY . /app

RUN pip3 install -r requirments.txt

ENTRYPOINT ["python3"]

CMD ["app.py"]
