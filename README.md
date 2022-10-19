# Torche Registration Class with Django

### Flowchart
![image](https://user-images.githubusercontent.com/69528812/196679538-8793bccf-c861-4c15-b991-19b4f1c2c9c1.png)

### Requirement Packages
````
arabic-reshaper==2.1.3
asgiref==3.2.10
asn1crypto==1.5.1
cachetools==4.2.4
certifi==2022.6.15
cffi==1.15.1
charset-normalizer==2.1.1
click==8.1.3
cryptography==37.0.4
cssselect2==0.6.0
Django==3.1.1
django-environ==0.9.0
django-googledrive-storage==1.6.0
django-multiselectfield==0.1.12
djongo==1.3.6
dnspython==2.2.1
future==0.18.2
google-api-core==2.10.0
google-api-python-client==2.60.0
google-auth==1.35.0
google-auth-httplib2==0.1.0
googleapis-common-protos==1.56.4
gunicorn==20.0.4
html5lib==1.1
httplib2==0.20.4
idna==3.3
lxml==4.9.1
mock==4.0.3
mongoengine==0.24.2
oauth2client==4.1.3
oscrypto==1.3.0
Pillow==9.2.0
protobuf==4.21.5
psycopg2==2.9.3
pyasn1==0.4.8
pyasn1-modules==0.2.8
pycparser==2.21
PyDrive==1.3.1
pyHanko==0.13.2
pyhanko-certvalidator==0.19.5
pymongo==3.12.3
pyparsing==3.0.9
PyPDF3==1.0.6
python-bidi==0.4.2
python-dateutil==2.8.2
python-snappy==0.6.1
pytz==2022.2.1
pytz-deprecation-shim==0.1.0.post0
PyYAML==6.0
qrcode==7.3.1
reportlab==3.6.11
requests==2.28.1
rsa==4.9
six==1.16.0
sqlparse==0.2.4
svglib==1.4.1
tinycss2==1.1.1
tqdm==4.64.0
tzdata==2022.2
tzlocal==4.2
uritemplate==4.1.1
uritools==4.0.0
urllib3==1.26.12
webencodings==0.5.1
xhtml2pdf==0.2.8
````

### Directory Structure
```text
└── FormRegistration
    ├── FormRegistration
    │   ├── __init__.py
    │   ├── asgi.py
    │   ├── setting.py
    │   ├── urls.py
    │   ├── wsgi.py 
    ├── FormRegistrationApp
    │   ├── migrations
    │   ├── templates
    │   │    ├── FormRegistrationApp
    │   ├── __init__.py
    │   ├── admin.py
    │   ├── apps.py
    │   ├── forms.py
    │   ├── models.py
    │   ├── urls.py
    │   ├── views.py
    │   └── test.py
    ├── client_secret.json
    ├── db.sqlite3
    ├── manage.py
    ├── requirements.txt
    └── README.md
```
