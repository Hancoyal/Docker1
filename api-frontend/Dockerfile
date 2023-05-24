FROM python:2.7

WORKDIR /app

RUN pip install Flask==1.1.2 requests==2.26.0

COPY . /app

ENV API_BACKEND_URL="api-backend"
ENV API_BACKEND_PORT=8001

EXPOSE 8000

CMD ["python", "api.py"]
