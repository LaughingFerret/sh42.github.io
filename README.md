<form action="action_page.php">
  <div class="container">
    <h1>Регистрация</h1>
    <p>Заполните данную форму для регистрации</p>
    <hr>

    <label for="email"><b>Email</b></label>
    <input type="text" placeholder="Введите Email" name="email" required>

    <label for="psw"><b>Пароль</b></label>
    <input type="password" placeholder="Введите пароль" name="psw" required>

    <label for="psw-repeat"><b>Подтвердите пароль</b></label>
    <input type="password" placeholder="Подтвердите пароль" name="psw-repeat" required>
    <hr>
    
    <button type="submit" class="registerbtn">Зарегистрироваться</button>
  </div>

  <div class="container signin">
    <p>У вас уже есть аккаунт? <a href="#">Войти</a>.</p>
  </div>

  <style>
body {
    font-family: Arial, Helvetica, sans-serif;
    background-color: #1f75fe;
}

* {
    box-sizing: border-box;
}

/* Add padding to containers */
.container {
    padding: 16px;
    background-color: white;
}

/* Full-width input fields */
input[type=text], input[type=password] {
    width: 100%;
    padding: 15px;
    margin: 5px 0 22px 0;
    display: inline-block;
    border: none;
    background: #f1f1f1;
}

input[type=text]:focus, input[type=password]:focus {
    background-color: #ddd;
    outline: none;
}

/* Overwrite default styles of hr */
hr {
    border: 1px solid #f1f1f1;
    margin-bottom: 25px;
}

/* Set a style for the submit button */
.registerbtn {
    background-color: #4CAF50;
    color: white;
    padding: 16px 20px;
    margin: 8px 0;
    border: none;
    cursor: pointer;
    width: 100%;
    opacity: 0.9;
}

.registerbtn:hover {
    opacity: 1;
}

/* Add a blue text color to links */
a {
    color: dodgerblue;
}

/* Set a grey background color and center the text of the "sign in" section */
.signin {
    background-color: #f1f1f1;
    text-align: center;
}
</style>
