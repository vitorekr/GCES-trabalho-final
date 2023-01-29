FROM python:3.8 as build-dep
COPY app/requirements.txt .

WORKDIR /app

COPY . .

RUN mkdir /install

RUN pip3 install -r app/requirements.txt

CMD ["python3", "src/main.py"]