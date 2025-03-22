<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profile Page</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
</head>
<body>
    <style>
html, body {
    height: 100%;
    margin: 0;
    padding: 0;
    display: flex;
    flex-direction: column;
    background-color: white; 
    background: #f8f9fa;
    font-family: sans-serif;
} 

.box {
    text-align: center;
    padding: 30px;
}

.box p {
    font-size: 24px;
}

.wrapper {
    flex: 1; 
    display: flex;
    justify-content: center; 
    align-items: center; 
}

.content {
    text-align: center;
    padding: 40px;
    background: #f8f9fa;
    border-radius: 10px;
    box-shadow:  0 0 10px rgba(0, 0, 0, 0.1);
}

button {
    padding: 10px 20px;
    font-size: 16px;
    background-color: #000000;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    margin-bottom: 15px;
}

button:hover {
    opacity: .8;
}

footer {
    background-color: white;
    text-align: center;
    padding: 30px;
    color: rgb(165, 165, 165);
}

    </style>
      <div class="box">
        <p><i class="bi bi-fire" style="margin-right: 5px;"></i>Selamat Datang Di Website Saya<i class="bi bi-fire" style="margin-left: 5px;"></i></p>
    </div> 

    <div class="wrapper">  
           
        <div class="content">
            <p>Silahkan Klik Untuk Melihat Profile</p>
            <a href="profile.html" data-toggle="tootip" title="Profile"><button><i class="bi bi-person-fill me-2"></i> Profile Saya</button></a>
        </div>
    </div>

    <footer>
        By Gilang Ramadhan || 52023100011 || Sistem Informasi
    </footer>

</body>
</html>

