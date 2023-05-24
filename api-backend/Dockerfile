FROM python:2.7

WORKDIR /app

RUN pip install Flask==1.1.2 requests==2.26.0

COPY . /app

EXPOSE 8001

CMD ["python", "api.py"]
