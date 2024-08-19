## FastAPI03

Shows examples of using FastAPI

Based on chapter 3 of:

```
Building Python Microservices with FastAPI
Sherwin John C. Tragura
```

This application uses the FastAPI framework driven by Python 3.8.
No database included yet.

The requirements.txt will guide you with the dependencies. Just install by running:

```
pkg-config mariadb-dev
pip install -r requirements.txt
```

# Running this

```
uvicorn main:app --reload
```

then use

```
[POST] localhost:8000/ch03/keyword/add?rid=urn:uuid:12345678-1234-5678-1234-567812345678&keyword=alpha
```

then use:

```
[GET] localhost:8000/ch03/keyword/list
```



mysql==0.0.3
mysql-connector-python==8.0.28
mysqlclient==2.1.1
