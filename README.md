# Login-NodeJS

1. $npm install -g express-gererator
2. $express
3. edit jade to ejs

3.1. /app.js

14 app.set('view engine','ejs');

3.2. /package.json

"jade": "~1.11.0", to "ejs": "*"

3.3. rename /views/index.jade to /views/index.ejs and edit code
```
<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
  <meta charset="UTF-8">
  <title>Login</title>
</head>
<body>
  
</body>
</html>
```
4. $npm install
