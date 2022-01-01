FROM python:3.6
WORKDIR /app 
COPY requirements.txt .
COPY front.py .
COPY templates ./templates/
RUN pip install -r requirements.txt 
EXPOSE 3001
CMD ["python", "front.py"]
