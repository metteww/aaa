<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Selamat Hari Valentine!</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f8f8f8;
            padding: 50px;
        }
        h1 {
            color: #d64b79;
        }
        .message {
            font-size: 1.5em;
            margin-top: 20px;
            color: #ff4d88;
        }
        .button {
            background-color: #d64b79;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            margin-top: 30px;
        }
        .button:hover {
            background-color: #ff4d88;
        }
    </style>
</head>
<body>
    <h1>Happy Valentine's Day!</h1>
    <div class="message" id="message"></div>
    <button class="button" onclick="showMessage()">gatau blm kenal!</button>

    <script>
        // Fungsi untuk menampilkan notifikasi ucapan Valentine
        function showMessage() {
            alert("Selamat Hari Valentine! Semoga hari ini penuh cinta dan kebahagiaan.");
        }

        // Menampilkan pesan otomatis ketika halaman dibuka
        window.onload = function() {
            setTimeout(function() {
                alert("Selamat Hari Valentine! Semoga hari ini penuh cinta dan kebahagiaan.");
            }, 1000); // Notifikasi muncul 1 detik setelah halaman dimuat
        }
    </script>
</body>
</html>
