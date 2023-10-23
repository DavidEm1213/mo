<!DOCTYPE html>
<html>
<head>
  <title>You are Welcome</title>
  <style>
    body {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      font-family: Arial, sans-serif;
    }

    .login-form {
      padding: 20px;
      background-color: #f8f8f8;
      border-radius: 5px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    }

    .login-form label {
      display: block;
      margin-bottom: 10px;
      font-weight: bold;
    }

    .login-form input[type="text"],
    .login-form input[type="password"] {
      width: 100%;
      padding: 10px;
      margin-bottom: 20px;
      border-radius: 10px; 
      border: 1px solid #c07c7c;
      background-color: #F3DEDE;
    }

    .login-form input[type="submit"] {
      display: block;
      width: 100%;
      padding: 10px;
      border: none;
      border-radius: 10px;
      background-color: #000802;
      border: #67f045;
      color: white;
      font-size: 16px;
      cursor: pointer;
      
    }
    .login-form input[type="button"] {
      display: block;
      width: 320px;
      padding: 10px;
      flex-shrink: 0;
      border: none;
      border-radius: 60px;
      background-color: #55f37d;
      border: #020a01;
      color: rgb(7, 2, 2);
      font-size: 20px;
      cursor: pointer;
       
    }
    
    .login-form input[type="submit"]:hover {
      background-color: #67f045;
    }
  </style>
</head>
<body>
  <div class="login-form">
    <h2 align="center">You are Welcome!</h2>
    <h6 align="center"> please enter your login and password to enter a privat account</h6>
    <form>
      <label for="username">Email:</label>
      <input type="text" id="username" name="username" required>
      <label for="password">Password:</label>
      <input type="password" id="password" name="password" required>
      <input type="submit" value="Login">
      <label for="forgot password?"  align="center"><u><a style="color: #0A6402;">forgot password?</a></u></label>
      <h5 align="center"> Don't have an account?</h5>
      <button><input type="button" value="create an account" align="center"></button>
    </form>
  </div>
</body>
</html>
