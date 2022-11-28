


## install requirement
```angular2html
pip isntall -r requirements.txt
```

## Create a squlite db in root
```angular2html
python manage.py
```

## How to deploy in docker to run in background
```angular2html
docker build -t name_of_container_you_want .
```
```angular2html
docker run -dp 5005:5000 -w /app -v "$(pwd):/app"  name_of_container_you_want
```
 
## Get api document
http://localhost:5005/swagger-ui



