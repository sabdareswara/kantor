<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Sabda Reswara - Admin</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      padding: 20px;
      background-color: #f0f6ff;
    }
    h1 {
      color: #004a99;
    }
    section {
      margin-bottom: 40px;
      padding: 20px;
      background-color: white;
      border-radius: 10px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    label {
      display: block;
      margin-top: 10px;
    }
    input, button {
      padding: 8px;
      margin-top: 5px;
      width: 100%;
      max-width: 400px;
    }
    ul {
      margin-top: 10px;
      padding-left: 20px;
    }
    li {
      margin-bottom: 6px;
    }
  </style>
</head>
<body>
  <h1>Sabda Reswara - Admin</h1>

  <section>
    <h2>Input Data Siswa</h2>
    <label>Nama:</label>
    <input type="text" placeholder="Nama Siswa" />
    <label>No. HP:</label>
    <input type="text" placeholder="Nomor HP" />
    <button>Simpan</button>
    <ul>
      <li>Contoh: Rina - 081234567890</li>
    </ul>
  </section>

  <section>
    <h2>Input Jadwal Les</h2>
    <label>Hari:</label>
    <input type="text" placeholder="Hari (contoh: Senin)" />
    <label>Jam:</label>
    <input type="text" placeholder="Jam (contoh: 16:00)" />
    <button>Tambah</button>
    <ul>
      <li>Senin, 16:00</li>
    </ul>
  </section>

  <section>
    <h2>Input Pembayaran</h2>
    <label>Nama:</label>
    <input type="text" placeholder="Nama Siswa" />
    <label>Jumlah (Rp):</label>
    <input type="text" placeholder="Contoh: 150000" />
    <button>Simpan</button>
    <ul>
      <li>Kwitansi untuk Rina: Rp150.000</li>
    </ul>
  </section>

  <section>
    <h2>Input Absensi</h2>
    <label>Nama:</label>
    <input type="text" placeholder="Nama Siswa" />
    <label>Tanggal:</label>
    <input type="date" />
    <button>Simpan</button>
    <ul>
      <li>Rina hadir pada 7 April 2025</li>
    </ul>
  </section>

  <section>
    <h2>Laporan</h2>
    <h3>Siswa Menunggak:</h3>
    <ul>
      <li>Rina</li>
    </ul>

    <h3>Siswa Belum Hadir:</h3>
    <ul>
      <li>Rina</li>
    </ul>

    <button>Export ke CSV</button>
  </section>
</body>
</html>
