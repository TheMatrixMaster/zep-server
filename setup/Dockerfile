FROM python:3.8

WORKDIR /app

COPY setup.py utils.py requirements.txt /app/

RUN pip3 install --upgrade pip
RUN pip3 install -r requirements.txt

CMD [ "/app/setup.py" ]
ENTRYPOINT [ "python" ]
