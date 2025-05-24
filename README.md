<!DOCTYPE html>
<html>
<head>
  <title>Donasi Kripto ke Saya</title>
  <style>
    body { font-family: Arial; text-align: center; padding: 20px; }
    .wallet { font-size: 18px; word-break: break-all; }
    .copy-btn { margin-top: 10px; }
  </style>
</head>
<body>
  <h2>Dukung Saya dengan Donasi Kripto</h2>
  <p>Kamu bisa bantu saya dengan kirim USDT ke wallet saya:</p>
  
  <div class="wallet" id="wallet">0xf40ab7db5786775d441eb27b67a2ad5b9854fbef</div>
  <button class="copy-btn" onclick="copyWallet()">Copy Alamat</button>

  <h3>Jaringan yang Didukung:</h3>
  <ul style="list-style: none;">
    <li>Ethereum (ERC20)</li>
    <li>Binance Smart Chain (BEP20)</li>
    <li>Polygon (jika support)</li>
  </ul>

  <script>
    function copyWallet() {
      const wallet = document.getElementById("wallet").textContent;
      navigator.clipboard.writeText(wallet).then(() => {
        alert("Alamat wallet berhasil disalin!");
      });
    }
  </script>
</body>
</html>

<!--
**MuhammadSahroni93/MuhammadSahroni93** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
