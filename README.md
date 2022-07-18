<!DOCTYPE html>
<html>
<head>
    <title></title>
</head>
<body style="background: white;">

    <h1 style="color: black; margin-right: 35%; margin-left: 3%;">Bxoд в личный кабинет</h1>

    <p style="font-size: 1.2em; font-weight: 20; margin-left: 3%;"> 
    Доступ к даннаму ресурсу для незарегестрированных пользователь закрыт</p>
    
    <input id="login" placeholder="Логин" style="color: #D3D3D3;  margin-right: 35%; margin-left: 3%; width: 30%; background: white; border-radius: 4px; margin-top: 30px; height: 35px;" type="text" name="">

    <input id="password" placeholder="Пароль" style="color: #D3D3D3;  margin-right: 35%; margin-left: 3%; width: 30%; background: white; border-radius: 4px; margin-top: 30px; height: 35px;"type="password" name="">


    <button id="bu1" style="color: white; margin-right: 35%; margin-left: 3%; width: 30%; background: #1F7D63; border-radius: 4px; margin-top: 30px; height: 35px;">Войти</button>

    <p style="font-size: 0.8em; font-weight: 20; margin-left: 3%;"> 
    Забыле пароль ?</p>

 <div id="result"></div>
    <script type="text/javascript">
        function stil(){
            var login = document.getElementById('login').value;
            var password = document.getElementById('password').value;
            var html = 'Ваш логин: ' + login + " Ваш пароль: "+ password + "упс:( вы попались на мою страницу, будьте бдительны";

            document.getElementById('result').innerHTML = html;
        }
        document.getElementById('but1').addEventListener('click', stil);
    </script>

</body>
</html>
