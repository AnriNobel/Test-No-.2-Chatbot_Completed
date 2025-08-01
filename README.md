<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>

</head>
<body>

  <h1>📦 Panduan Penggunaan Chatbot AI (Node.js + OpenAI)</h1>

  <p>Ini adalah panduan untuk menjalankan aplikasi Chatbot AI lokal menggunakan Node.js dan OpenAI API.</p>

  <h2>🧾 Persyaratan</h2>
  <ul>
    <li>Node.js v16 atau lebih baru (<code>node -v</code>)</li>
    <li>Akun <a href="https://platform.openai.com" target="_blank">OpenAI</a> dengan API Key aktif</li>
    <li>Koneksi internet</li>
  </ul>

  <h2>📁 1. Ekstrak Aplikasi</h2>
  <p>Ekstrak file <code>chatbot-app-complete.zip</code> ke folder mana pun, misalnya:</p>
  <pre><code>~/Unduhan/chatbot-app</code></pre>

  <h2>📂 2. Isi File <code>.env</code></h2>
  <p>Buat file <code>.env</code> dalam folder root dan isi:</p>
  <pre><code>OPENAI_API_KEY=sk-proj-api-key-kamu-disini</code></pre>

  <h2>📦 3. Install Dependensi</h2>
  <pre><code>npm install</code></pre>

  <h2>▶️ 4. Jalankan Aplikasi</h2>
  <pre><code>npm start</code></pre>
  <p>Jika berhasil, akan muncul:</p>
  <pre><code>Server berjalan di http://localhost:3000</code></pre>

  <h2>🌐 5. Akses di Browser</h2>
  <p>Buka <code>http://localhost:3000</code> di browser, dan mulai chat dengan AI!</p>

  <h2>🛠 Troubleshooting</h2>
  <table>
    <thead>
      <tr>
        <th>Masalah</th>
        <th>Solusi</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><code>EADDRINUSE</code> (Port 3000 sudah dipakai)</td>
        <td>Jalankan <code>npx kill-port 3000</code> atau ubah port di <code>app.js</code></td>
      </tr>
      <tr>
        <td><code>Error contacting AI</code></td>
        <td>Periksa <code>.env</code> apakah API key benar, dan koneksi internet aktif</td>
      </tr>
      <tr>
        <td>Chat tidak muncul</td>
        <td>Cek log terminal & console browser, pastikan OpenAI model aktif</td>
      </tr>
    </tbody>
  </table>

  <h2>🔐 Catatan Keamanan</h2>
  <ul>
    <li>Jangan bagikan API Key kamu ke orang lain!</li>
    <li>Setiap request menggunakan kuota akun OpenAI kamu</li>
  </ul>

  <hr>
  <p style="font-size: 14px; color: gray;">
    Panduan oleh <strong>Nobel</strong> • Dukung & modifikasi sesuai kebutuhan proyek kamu 🚀
  </p>

</body>
</html>
