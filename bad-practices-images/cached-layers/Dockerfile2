FROM python:3.9-alpine

LABEL name="Phthon Application"\
      maintainer="Ali Kahoot <kahoot.ali@outlook.com>"\
      summary="A Sample Phython application"

# Create app directory

WORKDIR /app

EXPOSE 8080


RUN pip3 install flask

COPY app.py index.html ./

CMD ["python3" ,"/app.py"]
