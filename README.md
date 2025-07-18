# warsitoaq.github.io
<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>Karya Ilmiah & Penelitian Hukum dan Dakwah Islamiyyah</title>
<style>
:root{--biru:#2c3e50;--hijau:#27ae60;--putih:#ffffff}
*{box-sizing:border-box;font-family:Arial,Helvetica,sans-serif}
body{margin:0;background:#ecf0f1;color:#2d3436;line-height:1.6}
header{background:var(--biru);color:var(--putih);padding:30px 10px;text-align:center}
header h1{margin:0;font-size:1.6rem}
header p{margin:4px 0 0;font-size:.95rem}
nav{background:#bdc3c7;text-align:center;padding:10px;position:sticky;top:0;z-index:20}
nav a{color:var(--biru);margin:0 12px;text-decoration:none;font-weight:bold}
nav a:hover{opacity:.8}
section{max-width:900px;margin:30px auto;background:var(--putih);padding:25px;border-radius:8px;box-shadow:0 2px 6px rgba(0,0,0,.1)}
h2{color:var(--biru);margin-top:0}
ul{margin-left:20px}
.download-btn,.btn{display:inline-block;background:var(--hijau);color:#fff;padding:9px 15px;border:none;border-radius:5px;text-decoration:none;cursor:pointer}
.download-btn:hover,.btn:hover{opacity:.9}
table{width:100%;border-collapse:collapse;margin-top:18px}
th,td{border:1px solid #dfe6e9;padding:8px;font-size:.9rem;text-align:left}
th{background:#f5f6fa}
.form-block{margin:12px 0}
label{display:block;margin-bottom:6px;font-weight:bold}
input[type=text],input[type=password],input[type=file]{width:100%;padding:8px;border:1px solid #ccc;border-radius:4px}
.alert{padding:8px;border-radius:4px;font-size:.9rem;margin-top:10px}
.success{background:#d4edda;color:#155724}
.error{background:#f8d7da;color:#721c24}
#logout{background:#e74c3c;margin-left:10px}
footer{background:var(--biru);color:var(--putih);text-align:center;padding:18px;font-size:.85rem;margin-top:40px}
</style>
</head>
<body>

<header>
  <h1>Karya Ilmiah &amp; Penelitian Hukum dan Dakwah Islamiyyah</h1>
  <p>Oleh Warsito Ahmad Qodlofi SH</p>
</header>

<nav>
  <a href="#home">Halaman Depan</a>
  <a href="#daftar-isi">Daftar Isi</a>
  <a href="#artikel">Judul Artikel</a>
  <a href="#kontak">Kontak</a>
</nav>

<!-- ================= HALAMAN DEPAN / LOGIN ================= -->
<section id="home">
  <h2>Selamat Datang</h2>
  <p>Portal pribadi ini menyediakan karya ilmiah, penelitian hukum, dan materi dakwah Islamiyyah untuk diunduh gratis. Silakan menelusuri daftar isi, membaca artikel, atau—bagi admin—mengunggah berkas baru.</p>

  <!-- ======== AUTH AREA ======== -->
  <div id="auth-area">
    <h3>Login Admin</h3>
    <div id="auth-msg"></div>

    <div class="form-block">
      <label for="login-user">Username</label>
      <input type="text" id="login-user" placeholder="Qodlofi">
    </div>
    <div class="form-block">
      <label for="login-pass">Password</label>
      <input type="password" id="login-pass" placeholder="********">
    </div>
    <button class="btn" onclick="login()">Masuk</button>
  </div>

  <!-- ======== MEMBER AREA ======== -->
  <div id="member-area" style="display:none">
    <p class="success alert">Login sebagai <strong id="member-name"></strong></p>
    <button id="logout" class="btn" onclick="logout()">Logout</button>

    <h3 style="margin-top:28px">Upload Berkas (PDF / JPG / PNG)</h3>
    <div class="form-block">
      <input type="file" id="file-input">
    </div>
    <button class="btn" onclick="uploadFile()">Upload</button>

    <h4 style="margin-top:22px">Daftar Berkas Terunggah</h4>
    <table id="file-table">
      <thead><tr><th>Nama File</th><th>Aksi</th></tr></thead>
      <tbody></tbody>
    </table>
  </div>
</section>

<!-- ================= DAFTAR ISI ================= -->
<section id="daftar-isi">
  <h2>Daftar Isi</h2>
  <ul>
    <li><a href="#karya-ilmiah">Karya Ilmiah</a></li>
    <li><a href="#penelitian-hukum">Penelitian Hukum</a></li>
    <li><a href="#dakwah">Dakwah Islamiyyah</a></li>
  </ul>
</section>

<!-- ================= ARTIKEL & DOWNLOAD ================= -->
<section id="artikel">
  <h2 id="karya-ilmiah">Karya Ilmiah</h2>
  <p><strong>1. Tinjauan Pidana Korporasi (2025)</strong></p>
  <a href="https://drive.google.com/file/d/LINK-PDF-1/view?usp=sharing" target="_blank" class="download-btn">📥 Download PDF</a>

  <h2 id="penelitian-hukum" style="margin-top:35px">Penelitian Hukum</h2>
  <p><strong>2. Perlindungan Hukum Anak dalam UU No. 35/2014</strong></p>
  <a href="https://drive.google.com/file/d/LINK-PDF-2/view?usp=sharing" target="_blank" class="download-btn">📥 Download PDF</a>

  <h2 id="dakwah" style="margin-top:35px">Dakwah Islamiyyah</h2>
  <p><strong>3. Strategi Dakwah Digital di Era Industri 4.0</strong></p>
  <a href="https://drive.google.com/file/d/LINK-PDF-3/view?usp=sharing" target="_blank" class="download-btn">📥 Download PDF</a>
</section>

<!-- ================= KONTAK ================= -->
<section id="kontak">
  <h2>Kontak</h2>
  <p>Alamat: Jl. Masjid, Dusun II GG Jati, Desa Karang Anyar, Kec. Secanggang, Kab. Langkat, Sumatera Utara – 20855</p>
  <p>Email: <a href="mailto:warsito.a.qodlofi@gmail.com">warsito.a.qodlofi@gmail.com</a><br>
     WA/Telp: <a href="tel:+6282277080975">0822-7708-0975</a></p>
</section>

<footer>
  &copy; 2025 Warsito Ahmad Qodlofi SH – Portal Karya Ilmiah
</footer>

<!-- ================= JAVASCRIPT (LOGIN & UPLOAD DEMO) ================= -->
<script>
/* ------- Credensial admin (disimpan di sisi klien) ------- */
const ADMIN_USER = "Qodlofi";
const ADMIN_PASS = "sidik121275";

/* ------- Helper localStorage untuk file demo ------- */
const getFiles = () => JSON.parse(localStorage.getItem("files") || "[]");
const setFiles = arr => localStorage.setItem("files", JSON.stringify(arr));

/* ------- Login process ------- */
function showMsg(txt, ok){
  const el = document.getElementById("auth-msg");
  el.className = (ok ? "success" : "error") + " alert";
  el.textContent = txt;
}
function login(){
  const u = document.getElementById("login-user").value.trim();
  const p = document.getElementById("login-pass").value;
  if(u === ADMIN_USER && p === ADMIN_PASS){
    localStorage.setItem("session","admin");
    renderMember();
  }else{
    showMsg("Username / password salah", false);
  }
}
function logout(){
  localStorage.removeItem("session");
  location.reload();
}
function renderMember(){
  document.getElementById("auth-area").style.display = "none";
  document.getElementById("member-area").style.display = "block";
  document.getElementById("member-name").textContent = ADMIN_USER;
  renderFileTable();
}
if(localStorage.getItem("session")==="admin") renderMember();

/* ------- Upload demo ------- */
function uploadFile(){
  const f = document.getElementById("file-input").files[0];
  if(!f){alert("Pilih file dahulu");return;}
  const arr = getFiles();
  arr.push({name:f.name});
  setFiles(arr);
  document.getElementById("file-input").value="";
  renderFileTable();
}
function renderFileTable(){
  const tbody = document.querySelector("#file-table tbody");
  tbody.innerHTML = "";
  getFiles().forEach((f,i)=>{
    const tr = document.createElement("tr");
    tr.innerHTML = `<td>${f.name}</td><td><button class="btn" onclick="alert('Fitur download demo');">Download</button></td>`;
    tbody.appendChild(tr);
  });
}
</script>

<!-- ======= Tempatkan kode Google AdSense di sini jika sudah disetujui ======= -->
</body>
</html>
