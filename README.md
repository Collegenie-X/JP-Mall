
### 환경 셋팅 

>  - python3.13 -m venv venv

###  실행 부분 
>  - Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
>  - source venv/bin/activate
>  - .\venv\Scripts\activate

>  - pip install -r requirements.txt
>
>  - mkdir backend
>  - cd backend
>  - django-admin startproject config .
>  - python manage.py runserver 0.0.0.0:8000 
>  - python manage.py runserver

> - python manage.py startapp accounts 

>  - python manage.py collectstatic
>  - python manage.py makemigrations 
>  - python manage.py migrate   

```
https://www.teacherspayteachers.com/
```

### Github desktoptop Setup download 
https://drive.google.com/file/d/12b-jwVJU9wIZYVHCrRUU2_6DlD7Q4MjZ/view?usp=sharing


#### makemigrations
```
> python manage.py makemigrations downloads
> python manage.py migrate 
> python manage.py runserver 
```

### startapp 생성 
```
>  python manage.py startapp account
```


python manage.py createsuperuser

email : admin@abc.com 
username : admin
password : 1234

python manage.py runserver









### requirements.txt 

> - amqp
> - asgiref
> - billiard
> - boto3
> - botocore
> - CacheControl
> - cachetools
> - celery
> - certifi
> - cffi
> - charset-normalizer
> - click
> - click-didyoumean
> - click-plugins
> - click-repl
> - cryptography
> - Django
> - django-celery
> - django-filter
> - django-multiselectfield
> - django-ses
> - django-storages
> - djangorestframework
> - djangorestframework_simplejwt
> - firebase-admin
> - google-api-core
> - google-api-python-client
> - google-auth
> - google-auth-httplib2
> - google-cloud-core
> - google-cloud-firestore
> - google-cloud-storage
> - google-crc32c
> - google-resumable-media
> - googleapis-common-protos
> - grpcio
> - grpcio-status
> - gunicorn
> - h11
> - httpcore
> - httplib2
> - idna
> - jmespath
> - kombu
> - msgpack
> - numpy
> - packaging
> - pandas
> - pillow
> - prompt_toolkit
> - proto-plus
> - protobuf
> - pyasn1
> - pyasn1_modules
> - pycparser
> - PyJWT
> - pyparsing
> - python-dateutil
> - python-dotenv
> - pytz
> - requests
> - rsa
> - s3transfer
> - six
> - sqlparse
> - typing_extensions
> - tzdata
> - uritemplate
> - urllib3
> - vine
> - wcwidth
> - django-admin-logs
> - django-rangefilter

