FROM python:latest

WORKDIR /app

COPY setup.py utils.py requirements.txt /app/

COPY documents /app/documents

RUN pip3 install --upgrade pip
RUN pip3 install -r requirements.txt

CMD [ "/app/setup.py" ]
ENTRYPOINT [ "python" ]
