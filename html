<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
    <title>Game Keuangan Jajan - Dzakwan</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            user-select: none;
        }

        body {
            font-family: 'Poppins', 'Segoe UI', system-ui, -apple-system, sans-serif;
            background: linear-gradient(135deg, #1e5f3a 0%, #2d8c5a 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }

        /* Container Game */
        .game-container {
            max-width: 550px;
            width: 100%;
            background: rgba(255,248,225,0.95);
            border-radius: 48px 48px 40px 40px;
            box-shadow: 0 20px 35px rgba(0,0,0,0.3), inset 0 1px 2px rgba(255,255,255,0.6);
            overflow: hidden;
            backdrop-filter: blur(2px);
            transition: transform 0.2s;
        }

        /* Header dengan Nama Pemain */
        .game-header {
            background: #ffb347;
            background: linear-gradient(135deg, #ff9a3c, #ff6a1a);
            padding: 20px 24px;
            text-align: center;
            border-bottom: 4px solid #ffdd99;
        }

        .game-header h1 {
            font-size: 2rem;
            font-weight: 800;
            color: #fff;
            text-shadow: 3px 3px 0 #b45f1b;
            letter-spacing: 1px;
        }

        .game-header .player-name {
            background: #fff2c9;
            display: inline-block;
            padding: 6px 20px;
            border-radius: 50px;
            margin-top: 10px;
            font-weight: bold;
            color: #c25d00;
            font-size: 1.2rem;
            box-shadow: inset 0 1px 3px rgba(0,0,0,0.1), 0 2px 4px rgba(0,0,0,0.1);
        }

        /* Area Uang & Poin */
        .wallet-area {
            background: #2d2b26;
            color: #f9e0a8;
            padding: 18px;
            display: flex;
            justify-content: space-between;
            align-items: baseline;
            flex-wrap: wrap;
            gap: 12px;
            border-bottom: 2px solid #ffc857;
        }

        .uang-card, .poin-card {
            background: #1f1e1a;
            border-radius: 32px;
            padding: 8px 20px;
            flex: 1;
            text-align: center;
            box-shadow: inset 0 1px 2px rgba(255,255,200,0.1), 0 5px 0 #0f0e0b;
        }

        .uang-card span, .poin-card span {
            font-size: 0.8rem;
            font-weight: 500;
            letter-spacing: 1px;
            color: #ffd966;
        }

        .uang-card .uang-value, .poin-card .poin-value {
            font-size: 2rem;
            font-weight: 800;
            color: #f9b81b;
            display: block;
            line-height: 1.2;
        }

        /* area menu makanan */
        .menu-section {
            padding: 20px 16px;
            background: #fef2df;
        }

        .section-title {
            font-size: 1.4rem;
            font-weight: bold;
            color: #aa5e1b;
            margin-bottom: 16px;
            display: flex;
            align-items: center;
            gap: 10px;
            border-left: 7px solid #ff8c42;
            padding-left: 15px;
        }

        .menu-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 16px;
        }

        .menu-card {
            background: white;
            border-radius: 28px;
            padding: 16px 8px;
            text-align: center;
            cursor: pointer;
            transition: all 0.2s ease;
            box-shadow: 0 8px 0 #d9b382;
            border: 1px solid #ffddbb;
        }

        .menu-card:active {
            transform: translateY(4px);
            box-shadow: 0 4px 0 #d9b382;
        }

        .menu-emoji {
            font-size: 3.5rem;
            display: block;
        }

        .menu-name {
            font-weight: 800;
            font-size: 1.3rem;
            margin: 8px 0 4px;
            color: #5a3e1f;
        }

        .menu-price {
            background: #ffedd5;
            border-radius: 50px;
            padding: 5px 0;
            font-weight: bold;
            color: #b45309;
            font-size: 0.9rem;
        }

        /* efek sedang beli */
        .notification {
            background: #3c2a1fdd;
            backdrop-filter: blur(8px);
            color: #ffefb9;
            border-radius: 60px;
            padding: 12px 20px;
            margin: 10px 16px;
            text-align: center;
            font-weight: bold;
            transition: 0.2s;
        }

        /* tombol aksi */
        .action-buttons {
            display: flex;
            gap: 12px;
            padding: 10px 16px 20px;
            flex-wrap: wrap;
        }

        .btn {
            flex: 1;
            padding: 12px 0;
            font-weight: bold;
            border: none;
            border-radius: 60px;
            font-size: 1rem;
            cursor: pointer;
            transition: 0.1s linear;
            font-family: inherit;
            background: #e9e3d5;
            box-shadow: 0 4px 0 #ad9f87;
        }

        .btn:active {
            transform: translateY(2px);
            box-shadow: 0 2px 0 #ad9f87;
        }

        .btn-primary {
            background: #f7b05e;
            color: #3b280b;
            font-weight: bold;
        }

        .btn-danger {
            background: #cf7b4a;
            color: white;
        }

        .btn-success {
            background: #4c8b5e;
            color: white;
        }

        .history-area {
            background: #e9dccd;
            margin: 8px 16px 20px;
            border-radius: 32px;
            padding: 12px;
            max-height: 210px;
            overflow-y: auto;
        }

        .history-title {
            font-weight: bold;
            margin-bottom: 8px;
            color: #5c3817;
            display: flex;
            gap: 6px;
        }

        .history-list {
            font-size: 0.8rem;
            list-style: none;
        }

        .history-list li {
            background: #fff6ea;
            margin-bottom: 6px;
            padding: 6px 12px;
            border-radius: 30px;
            display: flex;
            justify-content: space-between;
            border-left: 5px solid #ff9142;
        }

        footer {
            text-align: center;
            font-size: 0.7rem;
            padding: 12px;
            background: #e0c8ac;
            color: #624a2a;
        }
    </style>
</head>
<body>

<div class="game-container">
    <div class="game-header">
        <h1>🍜 DZAKWAN’S WARUNG 🍢</h1>
        <div class="player-name">⭐ Pemain: DZAKWAN ⭐</div>
    </div>

    <div class="wallet-area">
        <div class="uang-card">
            <span>💵 UANG SAKU</span>
            <span class="uang-value" id="uangDisplay">Rp 50.000</span>
        </div>
        <div class="poin-card">
            <span>🏆 POIN HEMAT</span>
            <span class="poin-value" id="poinDisplay">0</span>
        </div>
    </div>

    <div class="menu-section">
        <div class="section-title">
            <span>🍽️ Pilih Jajanan</span>
        </div>
        <div class="menu-grid" id="menuGrid">
            <!-- Menu akan di generate dengan js, tapi kita tulis manual -->
        </div>
    </div>

    <div id="notifBox" class="notification">✨ Klik menu untuk beli jajanan ✨</div>

    <div class="action-buttons">
        <button id="resetBtn" class="btn btn-danger">🔄 Reset Game</button>
        <button id="kerjaBtn" class="btn btn-success">💪 Nambah Uang (+10.000)</button>
    </div>

    <div class="history-area">
        <div class="history-title">📜 RIWAYAT BELANJA DZAKWAN</div>
        <ul id="historyList" class="history-list">
            <li style="opacity:0.7;">Belum ada transaksi</li>
        </ul>
    </div>
    <footer>🎮 Game Keuangan - Belanja cerdas, kumpulkan poin hemat!</footer>
</div>

<script>
    // Data Menu : Nama, Harga, Emoji, PoinHemat
    const MENU_LIST = [
        { name: "BAKSO", price: 15000, emoji: "🍜", point: 5 },
        { name: "SIOMAY", price: 12000, emoji: "🥟", point: 4 },
        { name: "CIMOL", price: 8000, emoji: "🍡", point: 3 },
        { name: "CILOK", price: 7000, emoji: "🍢", point: 3 }
    ];

    // State Game
    let uang = 50000;      // uang awal 50rb
    let poinHemat = 0;
    let history = [];      // simpan objek {text, timestamp}

    // Elemen DOM
    const uangDisplay = document.getElementById("uangDisplay");
    const poinDisplay = document.getElementById("poinDisplay");
    const menuGrid = document.getElementById("menuGrid");
    const notifBox = document.getElementById("notifBox");
    const historyList = document.getElementById("historyList");
    const resetBtn = document.getElementById("resetBtn");
    const kerjaBtn = document.getElementById("kerjaBtn");

    // Helper format Rupiah
    function formatRupiah(angka) {
        return "Rp " + angka.toLocaleString("id-ID");
    }

    // Update tampilan UI
    function updateUI() {
        uangDisplay.innerText = formatRupiah(uang);
        poinDisplay.innerText = poinHemat;
    }

    // Tambah history dengan waktu
    function addHistory(message, isBuy = true) {
        const now = new Date();
        const waktu = `${now.getHours().toString().padStart(2,'0')}:${now.getMinutes().toString().padStart(2,'0')}:${now.getSeconds().toString().padStart(2,'0')}`;
        history.unshift({ text: message, time: waktu, isBuy }); // unshift agar terbaru diatas
        if (history.length > 12) history.pop();
        renderHistory();
    }

    // Render riwayat belanja
    function renderHistory() {
        if (history.length === 0) {
            historyList.innerHTML = '<li style="opacity:0.7;">📭 Belum ada transaksi</li>';
            return;
        }
        historyList.innerHTML = history.map(item => {
            const icon = item.isBuy ? "🛒" : "💰";
            return `<li><span>${icon} ${item.text}</span><span style="font-family:monospace;">${item.time}</span></li>`;
        }).join('');
    }

    // Tampilkan notifikasi sementara
    let notifTimeout;
    function setNotif(message, isError = false) {
        if (notifTimeout) clearTimeout(notifTimeout);
        notifBox.style.background = isError ? "#9e2d2fdd" : "#2c5a3edd";
        notifBox.style.color = "white";
        notifBox.innerText = message;
        notifTimeout = setTimeout(() => {
            notifBox.style.background = "#3c2a1fdd";
            notifBox.style.color = "#ffefb9";
            notifBox.innerText = "🍢 Klik menu untuk beli jajanan 🍜";
        }, 2000);
    }

    // Fungsi beli makanan (game keuangan)
    function beliMenu(menu) {
        const { name, price, emoji, point } = menu;

        // Cek apakah uang cukup
        if (uang < price) {
            setNotif(`❌ Uang kurang! ${name} seharga ${formatRupiah(price)}. Kerja dulu ya, Dzakwan!`, true);
            return false;
        }

        // Proses pembelian
        uang -= price;
        poinHemat += point;   // setiap beli dapat poin hemat (semakin hemat makin banyak poin? disini setiap menu punya poin)
        updateUI();

        // Tambah ke riwayat
        const pesanBeli = `Beli ${emoji} ${name} (${formatRupiah(price)}) | +${point} Poin`;
        addHistory(pesanBeli, true);

        // Notifikasi sukses
        setNotif(`✅ ${name} berhasil dibeli! -${formatRupiah(price)} | Poin +${point}`);
        
        // Cek jika uang habis beri semangat
        if (uang === 0) {
            setNotif("⚠️ Uang habis! Klik 'Nambah Uang' buat jajan lagi", false);
        }
        return true;
    }

    // Fitur nambah uang (kerja / dapat jajan tambahan)
    function nambahUang() {
        uang += 10000;
        updateUI();
        addHistory(`💼 Dapat tambahan uang saku +Rp10.000`, false);
        setNotif(`✨ +Rp10.000! Sekarang uang: ${formatRupiah(uang)}`, false);
    }

    // Reset Game (kembali ke awal)
    function resetGame() {
        uang = 50000;
        poinHemat = 0;
        history = [];
        updateUI();
        renderHistory();
        setNotif("🔄 Game direset! Uang kembali Rp50.000, poin dan riwayat bersih.", false);
        addHistory("🎮 Permainan dimulai ulang oleh Dzakwan", false);
    }

    // Membuat tombol menu dinamis
    function buildMenuButtons() {
        menuGrid.innerHTML = "";
        MENU_LIST.forEach(menu => {
            const card = document.createElement("div");
            card.className = "menu-card";
            card.setAttribute("data-name", menu.name);
            
            const emojiSpan = document.createElement("span");
            emojiSpan.className = "menu-emoji";
            emojiSpan.innerText = menu.emoji;
            
            const nameSpan = document.createElement("div");
            nameSpan.className = "menu-name";
            nameSpan.innerText = menu.name;
            
            const priceSpan = document.createElement("div");
            priceSpan.className = "menu-price";
            priceSpan.innerText = formatRupiah(menu.price) + `  🎁 +${menu.point}P`;
            
            card.appendChild(emojiSpan);
            card.appendChild(nameSpan);
            card.appendChild(priceSpan);
            
            // event beli
            card.addEventListener("click", (e) => {
                e.stopPropagation();
                beliMenu(menu);
            });
            menuGrid.appendChild(card);
        });
    }

    // event listener tombol eksternal
    kerjaBtn.addEventListener("click", () => {
        nambahUang();
    });
    
    resetBtn.addEventListener("click", () => {
        resetGame();
    });

    // Inisialisasi awal
    function init() {
        buildMenuButtons();
        updateUI();
        // history awal ada pesan selamat datang
        history = [];
        addHistory("📌 Selamat datang Dzakwan! Atur keuangan jajanmu", false);
        renderHistory();
        setNotif("Halo Dzakwan! Jajan secukupnya, kumpulin poin hemat ✨", false);
    }

    init();
</script>
</body>
</html>
