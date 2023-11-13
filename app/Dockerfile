FROM python
WORKDIR /app
COPY . /app
RUN pip3 freeze > requirements.txt
RUN pip3 install -r requirements.txt
RUN pip3 install Flask 

# ENTRYPOINT ["python3"]

CMD [ "flask", "--app", "app", "run", "--host=0.0.0.0"]
# CMD ["app.py"]
