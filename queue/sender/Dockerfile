FROM python:3.7

WORKDIR /app

COPY . /app

RUN pip3 install --trusted-host pypi.python.org -r requirements.txt

CMD ["python", "send.py"]

