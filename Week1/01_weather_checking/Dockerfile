FROM python:3.7-alpine
RUN apk add git

#RUN git clone https://github.com/dianewoodbridge/2021-msds603-example /2021-msds603-example
COPY . /2021-msds603-example/Week1/weather_checking
WORKDIR /2021-msds603-example/Week1/weather_checking

RUN pip install --upgrade pip
RUN pip install -r requirements.txt

EXPOSE 80
ENTRYPOINT [ "python", "application.py"]
