@@ -0,0 +1,172 @@
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DELIVERY ADAKAMI</title>
    <style>
        body {
            font-family: 'Helvetica Neue', sans-serif;
            background-color: #f9f9f9;
            color: #333;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #ff7b54;
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 36px;
            font-weight: bold;
        }

        header p {
            font-size: 18px;
            margin-top: 5px;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        .menu-section {
            margin-bottom: 40px;
        }

        h2 {
            color: #ff7b54;
            font-size: 28px;
            border-bottom: 2px solid #ff7b54;
            display: inline-block;
            padding-bottom: 5px;
            margin-bottom: 20px;
        }

        ul {
            list-style: none;
            padding: 0;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            grid-gap: 20px;
        }

        li {
            background-color: white;
            padding: 15px;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }

        li:hover {
            transform: scale(1.05);
        }

        .order-button {
            display: inline-block;
            margin-top: 30px;
            padding: 12px 24px;
            background-color: #ff7b54;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            font-size: 18px;
            transition: background-color 0.3s ease;
        }

        .order-button:hover {
            background-color: #e66940;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: white;
            margin-top: 40px;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 28px;
            }

            header p {
                font-size: 16px;
            }

            h2 {
                font-size: 24px;
            }

            .order-button {
                font-size: 16px;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>DELIVERY ADAKAMI</h1>
    <p>Makanan & Minuman Lezat, Siap Antar!</p>
</header>

<div class="container">
    <section class="menu-section">
        <h2>Makanan</h2>
        <ul>
            <li>Nasi Goreng Kampung</li>
            <li>Nasi Goreng Ayam Semur</li>
            <li>Nasi Goreng Pataya</li>
            <li>Nasi Goreng Telur</li>
            <li>Nasi Goreng Ayam</li>
            <li>Nasi Goreng Seafood</li>
            <li>Ayam Penyet</li>
            <li>Ayam Geprek</li>
            <li>Nasi Pecel Lele</li>
            <li>Nila Sambal Belacan</li>
            <li>Indomie Goreng</li>
            <li>Indomie Kuah</li>
        </ul>
    </section>

    <section class="menu-section">
        <h2>Minuman</h2>
        <ul>
            <li>Teh Manis (H/C)</li>
            <li>Nutri Sari</li>
            <li>Extra Joss</li>
            <li>Whita Koffie (H/C)</li>
            <li>Kopi Tubruk</li>
        </ul>
    </section>

    <section class="menu-section">
        <h2>Snack</h2>
        <ul>
            <li>Jasuke</li>
            <li>Sosis Gulung Telur</li>
            <li>Bakso Goreng</li>
            <li>Bakwan Sayur</li>
            <li>Bakwan Jagung</li>
        </ul>
    </section>

    <a href="https://wa.me/6281396105200" class="order-button">Pesan Sekarang via WhatsApp</a>
</div>

<footer>
    <p>&copy; 2024 DELIVERY ADAKAMI</p>
</footer>

</body>
</html>
