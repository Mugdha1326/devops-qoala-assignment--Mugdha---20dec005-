FROM python:3.9

WORKDIR /app  // corrected appp to app

COPY app.py /app // appy.py to app.py

RUN pip install flask netifaces //netiface to netifaces

EXPOSE 8000 //port

CMD ["python", "app.py"] 
