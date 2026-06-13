FROM python:slim
WORKDIR /app 
COPY requirements.txt .

RUN pip install -r requirements.txt
COPY demo1.py .

CMD ["python","demo1.py"]
