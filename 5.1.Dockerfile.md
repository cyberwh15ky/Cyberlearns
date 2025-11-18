# Python Flask  
FROM python:3.10  
WORKDIR /app  
COPY . .  
RUN pip install -r requirements.txt  
EXPOSE 5000  
CMD ["python", "app.py"]  

docker build -t my-site .  
docker run -d -p 3000:3000 my-site  
