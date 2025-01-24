<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday!</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to bottom, #ff9a9e, #fad0c4);
            color: #333;
            text-align: center;
        }
        header {
            padding: 50px 20px;
        }
        h1 {
            font-size: 3em;
            color: #fff;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2);
        }
        .subtitle {
            font-size: 1.5em;
            color: #ffe4e6;
        }
        .gallery {
            margin: 20px auto;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 15px;
            max-width: 90%;
        }
        .gallery img {
            width: 100%;
            height: auto;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }
        .message {
            margin: 30px auto;
            padding: 20px;
            max-width: 600px;
            background: #fff;
            border-radius: 15px;
            box-shadow: 0 5px 20px rgba(0, 0, 0, 0.1);
        }
        .btn-surprise {
            margin-top: 20px;
            padding: 15px 30px;
            font-size: 1.2em;
            color: #fff;
            background: #ff6b6b;
            border: none;
            border-radius: 10px;
            cursor: pointer;
            box-shadow: 0 5px 10px rgba(0, 0, 0, 0.1);
        }
        .btn-surprise:hover {
            background: #ff4757;
        }
    </style>
</head>
<body>
    <header>
        <h1>Happy Birthday, Sayangku Rina!</h1>
        <p class="subtitle">Hari ini adalah hari spesialmu, dan aku ingin merayakannya dengan penuh cinta ❤️</p>
    </header>

    <section class="gallery">
        <img src="WhatsApp Image 2025-01-24 at 20.50.19_cbc21e2e.jpg" alt="Memory 1">
        <img src="WhatsApp Image 2025-01-24 at 20.50.19_e976264c.jpg" alt="Memory 2">
        <img src="WhatsApp Image 2025-01-24 at 20.50.18_9aa14c0e.jpg" alt="Memory 3">
    </section>

    <section class="message">
        <p>Dear Sayangku Rina,</p>
        <p>Kamu adalah orang yang paling istimewa dalam hidupku. Aku sangat bersyukur memiliki kamu di sisiku. Terima kasih telah membawa kebahagiaan dan cinta ke dalam hidupku. Selamat ulang tahun! 🎉❤️</p>
        <p>Love, Raja</p>
        <button class="btn-surprise" onclick="showSurprise()">Klik untuk Kejutan!</button>
    </section>

    <script>
        function showSurprise() {
            alert("🎉 Selamat Ulang Tahun! Kejutan spesial menunggumu! ❤️");
        }
    </script>
</body>
</html>
