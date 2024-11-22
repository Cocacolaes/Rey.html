<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Pribadi</title>
    <style>
        /* Reset dasar */
body, h1, h2, h3, p, ul, li {
    margin: 0;
    padding: 0;
    list-style: none;
    font-family: Arial, sans-serif;
    box-sizing: border-box;
}

body {
    line-height: 1.6;
    background: white;
    color: #333;
}

/* Header */
header {
    background: yellow;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    margin-bottom: 10px;
}

/* Navigation */
nav {
    background: #333;
}

nav ul {
    display: flex;
    justify-content: left;
    padding: 10px;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: #fff;

}

/* Section */
.container {
    width: 80%;
    margin: 0 auto;
    padding: 20px;
    text-align: center;
}
.nama {
    
    text-align: center;
}



section {
    margin: 20px 0;
}

.grid {
    display: flex;
    gap: 20px;
    flex-wrap: wrap;
}

.card {
    background: #fff;
    border: 1px solid #ddd;
    border-radius: 5px;
    overflow: hidden;
    text-align: center;
    flex: 1 1 calc(33.333% - 20px);
}
 .hero{
    background-image: url("C:/Urfi/amagede.jpg");
    background-repeat: no-repeat;
    background-size: cover;
    height: 350px;
    background-position: center;
    justify-content: center;
    align-items: center;
    color: white;
 }
.card img {
    width: 100%;
    height: 150px;
    object-fit: cover;
}
.nama h1{
    color: white;
}
.card h3 {
    margin: 10px 0;
}

.card ul li{

}
/* Form */
form label {
    display: block;
    margin-top: 10px;
}

form input, form textarea, form button {
    width: 100%;
    padding: 10px;
    margin-top: 5px;
}

form button {
    background: #007bff;
    color: #fff;
    border: none;
    cursor: pointer;
}

form button:hover {
    background: #0056b3;
}

/* Footer */
footer {
    text-align: center;
    background: #333;
    color: #fff;
    padding: 10px 0;
}

    </style>
</head>
<body>


    <nav>
        <div class="container">
            <ul>
                <li><a href="#about">Tentang Saya</a></li>
                <li><a href="#Download">Download cv</a></li>
                <li><a href="#contact">Kontak</a></li>
            </ul>
        </div>
    </nav>
    <div class="hero">
        <div class="nama">
            <h1>Muhammad Reyhan</h1>
            <p>Mahasiswa Komputerisasi akuntansi</p>
        </div>
    </div>

    <section id="about">
        <div class="container">
            <h2>hallo semuanya!!</h2>
            <p>Perkenalkan nama saya Muhammad Reyhan dari prodi komputerisai akuntansi, saya memiliki hobi 
                membaca novel
            </p>
        </div>
    </section>

    <section id="Donwload">
        <div class="container">
            <h2>Overview</h2>
            <br>
            <p>Hi, saya adalah mahasiswa STMIK Mardira</p>
            <br>
            <div class="grid">
                <div class="card">
                    
                    <h3>Hard Skill</h3>
                    <ul>
                        <li>Mengelola Keuangan</li>
                        <li>Memasak</li>
                        <li>Berenabg</li>
                        <li>mengelola waktu</li>
                    </ul>
                </div>
                <div class="card">
                    
                    <h3>Soft Skill</h3>
                    <ul>
                        <li>Disiplin</li>
                        <li>Bertanggung Jawab</li>
                        <li>Publik Speaking</li>
                        <Li>Problem Solving</Li>
                    </ul>
                </div>
            </div>
        </div>
    </section>


    <footer>
        <div class="container">
            <p>&copy; 2024 Muhammad Reyhan. aku adalah cowok</p>
        </div>
    </footer>
</body>
</html>
