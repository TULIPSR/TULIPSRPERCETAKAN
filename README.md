<!DOCTYPE html>
<html>
<head>
  <title>Tulip SR Print</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    body { font-family: Arial; margin:0; background:#f4f6f9; }
    header {
      background: linear-gradient(45deg,#0f2027,#203a43,#2c5364);
      color:white;
      padding:30px;
      text-align:center;
    }
    .container { padding:15px; }
    .card {
      background:white;
      padding:15px;
      margin-bottom:15px;
      border-radius:10px;
    }
    button {
      width:100%;
      padding:10px;
      background:#25D366;
      color:white;
      border:none;
      border-radius:5px;
      margin-top:10px;
    }
  </style>
</head>

<body>

<header>
  <h2>TULIP SR PRINT</h2>
  <p>Fotocopy • Print • Desain</p>
</header>

<div class="container">

  <div class="card">
    <h3>Print & Fotocopy</h3>
    <p>Hitam Putih: Rp 500</p>
    <p>Warna: Rp 1.000</p>
    <button onclick="wa()">Pesan via WhatsApp</button>
  </div>

</div>

<script>
function wa(){
  window.location.href = "https://wa.me/6285713393771";
}
</script>

</body>
</html>
