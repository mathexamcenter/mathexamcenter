<!DOCTYPE html>
<html lang="az">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Riyaziyyat İmtahan Mərkəzi</title>

<style>

body{
    margin:0;
    font-family:Arial, sans-serif;
}

/* 🔥 Arxa fon */
body::before{
    content:"";
    position:fixed;
    width:100%;
    height:100%;
    background:url('https://images.unsplash.com/photo-1596495578065-6e0763fa1178') no-repeat center/cover;
    filter:blur(6px);
    z-index:-1;
}

body::after{
    content:"";
    position:fixed;
    width:100%;
    height:100%;
    background:rgba(0,0,0,0.4);
    z-index:-1;
}

/* 🔥 Form */
.container{
    width:360px;
    background:rgba(255,255,255,0.95);
    padding:25px;
    border-radius:12px;
    box-shadow:0 10px 30px rgba(0,0,0,0.3);

    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%, -50%);

    text-align:center;
}

/* 🔥 Başlıq */
.logo{
    font-size:40px;
    margin-bottom:10px;
}

h1{
    color:#0a2c6d;
    font-size:20px;
    margin-bottom:5px;
}

h2{
    color:#444;
    font-size:15px;
    margin-bottom:15px;
}

/* 🔥 Inputlar */
input{
    width:100%;
    padding:10px;
    margin:6px 0;
    border:1px solid #ccc;
    border-radius:6px;
    font-size:14px;
}

/* 🔥 Button */
button{
    width:100%;
    padding:12px;
    margin-top:12px;
    background:#0a2c6d;
    color:white;
    border:none;
    border-radius:6px;
    font-size:16px;
    cursor:pointer;
    transition:0.3s;
}

button:hover{
    background:#061c45;
}

/* 🔥 Footer */
.footer{
    margin-top:10px;
    font-size:12px;
    color:#777;
}

</style>
</head>

<body>

<div class="container">

    <div class="logo">📘</div>

    <h1>Riyaziyyat İmtahan Mərkəzi</h1>
    <h2>Şəxsi kabinetə qeydiyyat</h2>

    <form>
        <input type="text" placeholder="Şəxsiyyət vəsiqəsi / ID" required>
        <input type="text" placeholder="FIN kod" required>
        <input type="date" required>
        <input type="tel" placeholder="Telefon nömrəsi" required>
        <input type="email" placeholder="E-poçt ünvanı" required>
        <input type="password" placeholder="Açar söz" required>
        <input type="password" placeholder="Açar söz təkrar" required>

        <button type="submit">Qeydiyyatdan keç</button>
    </form>

    <div class="footer">
        © 2026 Riyaziyyat İmtahan Mərkəzi
    </div>

</div>

</body>
</html>