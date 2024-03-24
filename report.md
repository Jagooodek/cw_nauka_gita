# Sprawozdanie lista 2

## Zadanie 5

```bash
vdi-terminal@MX1-Prog-098 MINGW64 ~/cw_nauka_gita
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
vdi-terminal@MX1-Prog-098 MINGW64 ~/cw_nauka_gita
$ curl http://127.0.0.1:5000/hello
<!doctype html>
<html lang=en>
<title>Redirecting...</title>
<h1>Redirecting...</h1>
<p>You should be redirected automatically to the target URL: <a href="http://127.0.0.1:5000/hello/">http://127.0.0.1:5000/hello/</a>. If not, click the link.

vdi-terminal@MX1-Prog-098 MINGW64 ~/cw_nauka_gita
$ curl http://127.0.0.1:5000/hello/test
<!doctype html>
<title>Hello from Flask</title>

  <h1>Hello test!</h1>
```