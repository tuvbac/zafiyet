# zafiyet
html ile yazılmış zafiyetli web sitesi
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Giriş Sayfası</title>
</head>
<body>
    <h1>Giriş Yap</h1>
    <form action="/login" method="post">
        <label for="username">Kullanıcı Adı:</label>
        <input type="text" id="username" name="username" placeholder="Kullanıcı adınızı girin">
        <br><br>
        <label for="password">Parola:</label>
        <input type="password" id="password" name="password" placeholder="Parolanızı girin">
        <br><br>
        <button type="submit">Giriş Yap</button>
    </form>

    <hr>

   
    <p style="display:none">Kullanıcı adı: admin</p>
    <p style="display:none">Parola: 1234</p>

   
</body>
</html>
