# py-web-srvc

Follow this step for deploy this web.


## Using docker

### 1. Clone repository
```
git clone https://github.com/aldisakti2/py-web-srvc.git .
```

### 2. Build docker images using Dockerfile
```
docker build -t tubes .
```

### 3. Create container using that image and run it
```
docker run -d --name tubes-pemfug-cont -p 8501:8501 tubes
```

### 4. Access it on your browser with this url
```
http://localhost:8501
```

## Manual Install

### 1. Clone repository
```
git clone https://github.com/aldisakti2/py-web-srvc.git .
```

### 2. Install requirement package
```
pip3 install -r requirements.txt
```

### 3. Run main.py
```
streamlit run main.py
```

### 4. Access it on your browser
```
https://localhost:8501
```
