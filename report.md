# Sprawozdanie lista 2

## Zadanie 5

```bash

$ curl http://127.0.0.1:5000/
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>FlaskBlog</title>
</head>
<body>
   <h1>Welcome to FlaskBlog</h1>
</body>
</html>

$ curl http://127.0.0.1:5000/hello/
<!doctype html>
<title>Hello from Flask</title>

  <h1>Hello, World!</h1>


$ curl http://127.0.0.1:5000/hello/test
<!doctype html>
<title>Hello from Flask</title>

  <h1>Hello test!</h1>
```

## Zadanie 6

Po zmianach 
```bash
$ curl http://127.0.0.1:5000/hello/test
<!doctype html>
<title>Hello from Flask</title>

  <h1>Hello test!</h1>
```

Zmieniło się w headerze ",World" na "test"