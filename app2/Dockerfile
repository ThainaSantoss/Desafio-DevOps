FROM python:3.14-rc-alpine
WORKDIR /app
COPY . .
RUN pip install -r requirements.txt
RUN adduser --disabled-password appuser
USER appuser
CMD ["python", "app.py"]