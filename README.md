# FLASK REST API BACKEND

### RUN
```
$ sh run.sh
```

### PYTEST
```
$ pytest --host=http://localhost:5000
```

### SWAGGER
```
http://localhost:5000/api/docs
```

### PROJECT STRUCTURE
```
flask_api_backend/
│   requirements.txt 
│   app.ini
│   wsgi.py
│
└───src/
│   │   app.py
│   │   api_spec.py
│   │
│   │───blueprints/
│       │   blueprint_x.py
│       │   blueprint_y.py
│       │   swagger.py
│
└───test/
    │   conftest.py
    │   test_endpoints.py
```

