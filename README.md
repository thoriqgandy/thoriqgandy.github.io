<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Portal Karier | PT Masa Depan</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background: #f2f4f8;
      color: #333;
    }

    header {
      background: linear-gradient(to right, #00b4db, #0083b0);
      color: white;
      text-align: center;
      padding: 40px 20px;
    }

    nav ul {
      list-style: none;
      padding: 0;
      display: flex;
      justify-content: center;
      gap: 20px;
      margin-top: 10px;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    section {
      padding: 40px 20px;
      max-width: 800px;
      margin: auto;
    }

    .jobs li {
      background: white;
      padding: 15px;
      margin-bottom: 10px;
      border-left: 5px solid #00b4db;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    form {
      background: white;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }

    form label {
      display: block;
      margin-top: 15px;
      font-weight: bold;
    }

    form input, form select, form textarea {
      width: 100%;
      padding: 10px;
      margin-top: 5px;
      border: 1px solid #ccc;
      border-radius: 4px;
    }

    form button {
      margin-top: 20px;
      padding: 12px 20px;
      background: #00b4db;
      color: white;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }

    form button:hover {
      background: #0083b0;
    }

    footer {
      background: #0083b0;
      color: white;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Portal Karier PT Masa Depan</h1>
    <p>Temukan pekerjaan impianmu bersama kami</p>
    <nav>
      <ul>
        <li><a href="#lowongan">Lowongan</a></li>
        <li><a href="#formulir">Formulir</a></li>
        <li><a href="#kontak">Kontak</a></li>
      </ul>
    </nav>
  </header>

  <section id="lowongan">
    <h2>Lowongan Tersedia</h2>
    <ul class="jobs">
      <li><strong>Frontend Developer</strong> - Jakarta</li>
      <li><strong>Digital Marketing</strong> - Bandung</li>
      <li><strong>HR Officer</strong> - Surabaya</li>
    </ul>
  </section>

  <section id="formulir">
    <h2>Formulir Pendaftaran</h2>
    <form>
      <label for="nama">Nama Lengkap:</label>
      <input type="text" id="nama" name="nama" required>

      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>

      <label for="posisi">Posisi yang Dilamar:</label>
      <select id="posisi" name="posisi">
        <option value="frontend">Frontend Developer</option>
        <option value="marketing">Digital Marketing</option>
        <option value="hr">HR Officer</option>
      </select>

      <label for="cv">Upload CV:</label>
      <input type="file" id="cv" name="cv">

      <label for="pesan">Pesan Tambahan:</label>
      <textarea id="pesan" name="pesan" rows="4"></textarea>

      <button type="submit">Kirim Lamaran</button>
    </form>
  </section>

  <section id="kontak">
    <h2>Hubungi Kami</h2>
    <p>Email: karier@ptmasadepan.co.id</p>
    <p>Telepon: (021) 98765432</p>
  </section>

  <footer>
    <p>&copy; 2025 PT Masa Depan. All rights reserved.</p>
  </footer>
</body>
</html>
