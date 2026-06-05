<!DOCTYPE html>  
<html lang="ru">  
<head>  
    <meta charset="UTF-8">  
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">  
    <title>CLICKER EMPIRE | Админ панель + Лидерборд + 2 счета</title>  
    <style>  
        * {  
            margin: 0;  
            padding: 0;  
            box-sizing: border-box;  
            font-family: 'Segoe UI', 'Poppins', system-ui, sans-serif;  
        }  
  
        body {  
            background: linear-gradient(135deg, #0a0f1e 0%, #0c1222 100%);  
            padding: 20px;  
            min-height: 100vh;  
        }  
  
        /* главная сетка */  
        .dashboard {  
            max-width: 1400px;  
            margin: 0 auto;  
            display: flex;  
            flex-wrap: wrap;  
            gap: 24px;  
        }  
  
        /* левая колонка — кликер и прочее */  
        .main-column {  
            flex: 2;  
            min-width: 280px;  
        }  
  
        .right-column {  
            flex: 1.4;  
            min-width: 300px;  
            display: flex;  
            flex-direction: column;  
            gap: 24px;  
        }  
  
        /* карточки */  
        .card {  
            background: rgba(18, 25, 45, 0.85);  
            backdrop-filter: blur(12px);  
            border-radius: 40px;  
            padding: 20px 24px;  
            border: 1px solid rgba(255, 215, 0, 0.25);  
            box-shadow: 0 20px 35px -10px black;  
            transition: 0.2s;  
        }  
  
        .card-title {  
            font-size: 1.5rem;  
            font-weight: bold;  
            color: #ffdf8c;  
            border-left: 5px solid #f5b042;  
            padding-left: 16px;  
            margin-bottom: 18px;  
            display: flex;  
            align-items: center;  
            gap: 10px;  
            flex-wrap: wrap;  
        }  
  
        /* кликер зона */  
        .clicker-area {  
            text-align: center;  
            background: linear-gradient(145deg, #1e2a3a, #0f1722);  
            border-radius: 48px;  
            padding: 20px;  
        }  
  
        .balance-row {  
            display: flex;  
            justify-content: center;  
            gap: 20px;  
            flex-wrap: wrap;  
            margin-bottom: 20px;  
        }  
  
        .balance-card {  
            background: #000000aa;  
            border-radius: 60px;  
            padding: 10px 24px;  
            font-weight: bold;  
            font-size: 1.5rem;  
            color: #ffecb3;  
        }  
  
        .click-btn {  
            background: radial-gradient(circle at 30% 20%, #f9b43a, #e67e22);  
            border: none;  
            font-size: 3.5rem;  
            font-weight: bold;  
            padding: 20px 40px;  
            width: 90%;  
            border-radius: 120px;  
            cursor: pointer;  
            box-shadow: 0 12px 0 #b45f1b;  
            transition: 0.05s linear;  
            margin: 10px 0;  
        }  
  
        .click-btn:active { transform: translateY(6px); box-shadow: 0 5px 0 #b45f1b; }  
  
        .upgrade-potion {  
            margin-top: 16px;  
            display: flex;  
            gap: 12px;  
            flex-wrap: wrap;  
            justify-content: center;  
        }  
        button {  
            background: #2c3e66;  
            border: none;  
            padding: 10px 20px;  
            border-radius: 50px;  
            font-weight: bold;  
            color: white;  
            cursor: pointer;  
            transition: 0.1s;  
        }  
        button:active { transform: scale(0.97); }  
        .admin-btn { background: #3a4a6e; }  
        .danger { background: #b53b2e; }  
        .success { background: #2c6e2f; }  
        .warning { background: #e68a2e; }  
  
        /* таблица лидеров */  
        .leaderboard-table {  
            width: 100%;  
            border-collapse: collapse;  
            color: #ddd;  
        }  
        .leaderboard-table td, .leaderboard-table th {  
            padding: 8px 6px;  
            border-bottom: 1px solid #ffd96655;  
        }  
        .badge-verified {  
            background: #1d9bf0;  
            border-radius: 20px;  
            padding: 2px 8px;  
            font-size: 0.7rem;  
            color: white;  
            margin-left: 6px;  
        }  
        .report-item, .message-item {  
            background: #00000055;  
            border-radius: 20px;  
            padding: 8px 12px;  
            margin: 8px 0;  
            font-size: 0.85rem;  
        }  
        .input-dark {  
            background: #0f1422;  
            border: 1px solid #ffcc66;  
            border-radius: 30px;  
            padding: 8px 14px;  
            color: white;  
            width: 100%;  
        }  
        .flex-row { display: flex; gap: 10px; flex-wrap: wrap; align-items: center; margin-top: 10px; }  
        .role-badge { font-size: 0.7rem; background: #000000aa; border-radius: 16px; padding: 4px 12px; }  
        hr { border-color: #ffaa3355; margin: 12px 0; }  
    </style>  
</head>  
<body>  
<div class="dashboard">  
    <!-- ЛЕВАЯ ОСНОВНАЯ КОЛОНКА -->  
    <div class="main-column">  
        <!-- КЛИКЕР И ДВА СЧЁТА -->  
        <div class="card">  
            <div class="card-title">💎 КЛИКЕР IMPERIUM 💎</div>  
            <div class="clicker-area">  
                <div class="balance-row">  
                    <div class="balance-card">💰 ОСН. СЧЁТ: <span id="mainBalance">0</span></div>  
                    <div class="balance-card">⭐ VIP СЧЁТ: <span id="vipBalance">0</span></div>  
                </div>  
                <button class="click-btn" id="clickMainBtn">🔥 КЛИК (осн.счёт) 🔥</button>  
                <div>➕ Сила клика: <strong id="clickPower">1</strong> (в осн.счёт)</div>  
                <div class="upgrade-potion">  
                    <button id="upgradePotionBtn">🧪 Улучшить зелье (ур. <span id="potionLvl">0</span>)</button>  
                    <button id="buyPotionBtn">💊 Купить зелье (врем. бонус)</button>  
                </div>  
                <div id="potionStatus" class="role-badge" style="margin-top: 8px;">⚗️ Зелье: не активно</div>  
            </div>  
        </div>  
  
        <!-- БАГ РЕПОРТЫ + ЦЕНТР СООБЩЕНИЙ -->  
        <div class="card">  
            <div class="card-title">🐞 БАГ-РЕПОРТЫ & МОДЕРАЦИЯ</div>  
            <textarea id="bugText" rows="2" class="input-dark" placeholder="Опиши баг или жалобу..."></textarea>  
            <div class="flex-row">  
                <button id="sendBugBtn" class="admin-btn">📩 Отправить репорт</button>  
                <button id="clearReportsBtn" class="danger">🗑️ Очистить репорты (модер+)</button>  
            </div>  
            <div id="reportsList" style="max-height: 150px; overflow-y: auto; margin-top: 12px;"></div>  
        </div>  
  
        <div class="card">  
            <div class="card-title">💬 ЦЕНТР СООБЩЕНИЙ (админ/модер)</div>  
            <input type="text" id="msgInput" class="input-dark" placeholder="Текст сообщения...">  
            <div class="flex-row">  
                <button id="sendGlobalMsgBtn">📢 Отправить (всем)</button>  
                <select id="msgTargetRole" class="input-dark" style="width:auto;">  
                    <option value="all">Всем игрокам</option>  
                    <option value="admin">Только админы/модеры</option>  
                </select>  
            </div>  
            <div id="messagesCenter" style="max-height: 180px; overflow-y: auto; margin-top: 12px; background:#00000044; border-radius: 20px; padding: 8px;"></div>  
        </div>  
    </div>  
  
    <!-- ПРАВАЯ КОЛОНКА: ЛИДЕРБОРД, АДМИН-ПАНЕЛЬ, БАНЫ -->  
    <div class="right-column">  
        <!-- Лидерборд + галочка инсты -->  
        <div class="card">  
            <div class="card-title">🏆 ЛИДЕРБОРД (общий счёт) 🏆 <span id="instaBadge" style="font-size:0.8rem;">✅ Галочка INSTA</span></div>  
            <table class="leaderboard-table" id="leaderboardTable">  
                <thead><tr><th>#</th><th>Имя</th><th>Роль</th><th>💰 Счёт</th></tr></thead>  
                <tbody id="leaderboardBody"></tbody>  
            </table>  
            <div class="flex-row" style="margin-top: 10px;">  
                <input type="text" id="playerNameInput" class="input-dark" placeholder="Ваше имя" value="Игрок">  
                <button id="changeNameBtn">Обновить</button>  
            </div>  
        </div>  
  
        <!-- АДМИН ПАНЕЛЬ (владелец, админы, модеры) -->  
        <div class="card">  
            <div class="card-title">👑 АДМИН-ПАНЕЛЬ (Владелец / Админ / Модер)</div>  
            <div id="adminRoleDisplay" class="role-badge" style="margin-bottom: 10px;">🔒 Авторизация: выбери роль</div>  
            <div class="flex-row">  
                <select id="roleSelect">  
                    <option value="owner">👑 Владелец (все права)</option>  
                    <option value="admin">🛡️ Администратор</option>  
                    <option value="moder">🛠️ Модератор</option>  
                    <option value="user">👤 Обычный</option>  
                </select>  
                <button id="applyRoleBtn">Сменить роль (демо)</button>  
            </div>  
            <hr>  
            <div class="flex-row"><input type="number" id="adminAmount" placeholder="Сумма" value="1000" class="input-dark"><button id="addMoneyMainBtn" class="success">➕ Добавить (осн)</button><button id="addMoneyVipBtn" class="success">⭐ Добавить VIP</button></div>  
            <div class="flex-row"><button id="setMoneyMainBtn" class="warning">🎯 Установить осн.</button><button id="removeMoneyBtn" class="danger">➖ Забрать (осн)</button></div>  
            <div class="flex-row"><button id="adminGivePotionBtn" class="success">🧪 Выдать зелье (сек: <span id="potionSecVal">45</span>)</button><input type="range" id="potionSlider" min="5" max="300" value="45" style="flex:1"></div>  
            <div class="flex-row"><button id="banUserBtn" class="danger">🚫 ЗАБАНИТЬ (по имени)</button><input id="banNameInput" placeholder="никнейм" class="input-dark"></div>  
            <div class="flex-row"><button id="unbanUserBtn" class="warning">🔓 Разбанить</button><button id="resetGameBtn" class="danger">⚠️ Сброс игры (владелец)</button></div>  
            <div id="banListDisplay" style="font-size: 0.7rem; margin-top: 8px; max-height: 80px; overflow-y: auto;">🚫 Забаненные: нет</div>  
        </div>  
    </div>  
</div>  
  
<script>  
    // ------------------- ИГРОВЫЕ ДАННЫЕ -------------------  
    let players = [];   // [{ name, role, mainMoney, vipMoney, totalScore, isBanned }]  
    let potionLevel = 0;           // уровень прокачки зелья  
    let potionActive = false;  
    let potionTimer = null;  
    let currentUserIndex = 0;      // текущий игрок (по умолчанию первый)  
    let globalMessages = [];        // { text, targetRole, timestamp }  
    let bugReports = [];  
  
    // вспомогательные функции  
    function calcPotionBonus() { return 3 + potionLevel * 2; }  
    function getClickPower() { return 1 + (potionActive ? calcPotionBonus() : 0); }  
  
    // инициализация игроков (лидерборд)  
    function initPlayers() {  
        if(players.length === 0) {  
            players = [  
                { name: "Владыка", role: "owner", mainMoney: 5000, vipMoney: 2000, totalScore: 7000, isBanned: false },  
                { name: "Admin_Kate", role: "admin", mainMoney: 2500, vipMoney: 800, totalScore: 3300, isBanned: false },  
                { name: "ModerAlex", role: "moder", mainMoney: 1200, vipMoney: 400, totalScore: 1600, isBanned: false },  
                { name: "Игрок1", role: "user", mainMoney: 340, vipMoney: 60, totalScore: 400, isBanned: false },  
                { name: "Игрок2", role: "user", mainMoney: 200, vipMoney: 50, totalScore: 250, isBanned: false }  
            ];  
        }  
        currentUserIndex = 0;  
        updateTotalScores();  
    }  
  
    function updateTotalScores() {  
        for(let p of players) p.totalScore = p.mainMoney + p.vipMoney;  
        sortLeaderboard();  
    }  
  
    function sortLeaderboard() {  
        players.sort((a,b) => b.totalScore - a.totalScore);  
    }  
  
    // рендер лидерборда  
    function renderLeaderboard() {  
        const tbody = document.getElementById('leaderboardBody');  
        tbody.innerHTML = '';  
        let filtered = players.filter(p => !p.isBanned);  
        for(let i=0; i<filtered.length; i++) {  
            let p = filtered[i];  
            let row = tbody.insertRow();  
            row.insertCell(0).innerText = i+1;  
            let nameCell = row.insertCell(1);  
            nameCell.innerHTML = p.name + (p.role === 'owner' ? ' 👑' : (p.role==='admin' ? ' 🛡️' : (p.role==='moder' ? ' 🛠️' : '')));  
            row.insertCell(2).innerText = p.role;  
            row.insertCell(3).innerText = p.totalScore;  
        }  
        // обновить отображение банов  
        let bannedNames = players.filter(p=>p.isBanned).map(p=>p.name).join(', ');  
        document.getElementById('banListDisplay').innerHTML = `🚫 Забаненные: ${bannedNames || 'нет'}`;  
    }  
  
    function renderReports() {  
        const container = document.getElementById('reportsList');  
        if(bugReports.length===0) { container.innerHTML = '<i>Нет репортов</i>'; return; }  
        container.innerHTML = bugReports.map((r,i)=>`<div class="report-item">📌 [${r.date}] ${r.text} <span style="color:#ffaa66;">от ${r.author}</span></div>`).join('');  
    }  
  
    function renderMessages() {  
        const container = document.getElementById('messagesCenter');  
        if(globalMessages.length===0) { container.innerHTML = '<i>Нет сообщений</i>'; return; }  
        container.innerHTML = globalMessages.slice().reverse().map(m=>`<div class="message-item">💬 ${m.text} <small>(${m.targetRole==='all'?'всем': 'админ/модер'})</small><div style="font-size:0.7rem;">${m.timestamp}</div></div>`).join('');  
    }  
  
    function refreshAllUI() {  
        let me = players[currentUserIndex];  
        if(!me) return;  
        document.getElementById('mainBalance').innerText = Math.floor(me.mainMoney);  
        document.getElementById('vipBalance').innerText = Math.floor(me.vipMoney);  
        document.getElementById('clickPower').innerText = getClickPower();  
        document.getElementById('potionLvl').innerText = potionLevel;  
        if(potionActive) document.getElementById('potionStatus').innerHTML = `⚗️ Зелье АКТИВНО (+${calcPotionBonus()} к силе)`;  
        else document.getElementById('potionStatus').innerHTML = `⚗️ Зелье не активно`;  
        renderLeaderboard();  
        renderReports();  
        renderMessages();  
        // админ права отображаем роль  
        let roleDesc = me.role === 'owner' ? 'Владелец (полный контроль)' : (me.role === 'admin' ? 'Администратор' : (me.role === 'moder' ? 'Модератор' : 'Игрок'));  
        document.getElementById('adminRoleDisplay').innerHTML = `👤 Текущая роль: ${roleDesc} | ${me.name}`;  
        // галочка инсты (демо - просто значок)  
        document.getElementById('instaBadge').innerHTML = me.role === 'owner' ? '✅ Верифицирован INSTA' : '🔘 Обычный аккаунт';  
    }  
  
    // проверка прав: owner / admin / moder (разграничим)  
    function canManageMoney(userRole) { return userRole === 'owner' || userRole === 'admin'; }  
    function canManagePotion(userRole) { return userRole === 'owner' || userRole === 'admin' || userRole === 'moder'; }  
    function canBan(userRole) { return userRole === 'owner' || userRole === 'admin'; }  
    function canResetGame(userRole) { return userRole === 'owner'; }  
    function canClearReports(userRole) { return userRole === 'owner' || userRole === 'admin' || userRole === 'moder'; }  
  
    // БАН / РАЗБАН  
    function banPlayerByName(adminRole, name) {  
        if(!canBan(adminRole)) { alert("Недостаточно прав! Нужен админ или владелец."); return false; }  
        let p = players.find(p=>p.name.toLowerCase() === name.toLowerCase() && !p.isBanned);  
        if(p) { p.isBanned = true; refreshAllUI(); alert(`Игрок ${name} забанен`); return true; }  
        else alert("Игрок не найден или уже забанен");  
        return false;  
    }  
    function unbanPlayerByName(adminRole, name) {  
        if(!canBan(adminRole)) { alert("Недостаточно прав!"); return; }  
        let p = players.find(p=>p.name.toLowerCase() === name.toLowerCase() && p.isBanned);  
        if(p) { p.isBanned = false; refreshAllUI(); alert(`Игрок ${name} разбанен`); }  
        else alert("Не найден в бане");  
    }  
  
    // добавить сообщение  
    function addGlobalMessage(senderRole, text, target) {  
        if(!text.trim()) return;  
        if(!(senderRole === 'owner' || senderRole === 'admin' || senderRole === 'moder')) { alert("Только модерация может отправлять сообщения"); return; }  
        globalMessages.push({ text: text, targetRole: target, timestamp: new Date().toLocaleTimeString(), authorRole: senderRole });  
        refreshAllUI();  
    }  
  
    // Отправка баг репорта (любой)  
    function addBugReport(authorName, text) {  
        if(!text.trim()) return;  
        bugReports.push({ text: text, author: authorName, date: new Date().toLocaleString() });  
        refreshAllUI();  
    }  
  
    // Админ управление деньгами  
    function changeMoney(targetPlayerIndex, deltaMain, deltaVip, adminRole) {  
        if(!canManageMoney(adminRole)) { alert("Нет прав на изменение денег (требуется админ/владелец)"); return false; }  
        let p = players[targetPlayerIndex];  
        if(p.isBanned) { alert("Игрок в бане"); return false; }  
        p.mainMoney = Math.max(0, p.mainMoney + deltaMain);  
        p.vipMoney = Math.max(0, p.vipMoney + deltaVip);  
        updateTotalScores();  
        refreshAllUI();  
        return true;  
    }  
  
    function setMoney(targetPlayerIndex, newMain, adminRole) {  
        if(!canManageMoney(adminRole)) return;  
        let p = players[targetPlayerIndex];  
        if(p.isBanned) return;  
        p.mainMoney = Math.max(0, newMain);  
        updateTotalScores();  
        refreshAllUI();  
    }  
  
    // зелье админом  
    function adminGivePotion(seconds, adminRole) {  
        if(!canManagePotion(adminRole)) { alert("Модеры и выше могут выдавать зелье"); return; }  
        if(potionTimer) clearInterval(potionTimer);  
        potionActive = true;  
        refreshAllUI();  
        let remaining = seconds;  
        potionTimer = setInterval(()=> {  
            remaining--;  
            if(remaining <= 0) {  
                clearInterval(potionTimer);  
                potionActive = false;  
                potionTimer = null;  
                refreshAllUI();  
            } else {  
                refreshAllUI();  
            }  
        }, 1000);  
        refreshAllUI();  
    }  
  
    function resetGame(adminRole) {  
        if(!canResetGame(adminRole)) { alert("Только владелец может сбросить игру!"); return; }  
        players = [];  
        potionLevel = 0;  
        if(potionTimer) clearInterval(potionTimer);  
        potionActive = false;  
        bugReports = [];  
        globalMessages = [];  
        initPlayers();  
        refreshAllUI();  
        alert("Игра сброшена владельцем");  
    }  
  
    // клик по главной кнопке (увеличивает основной счёт)  
    function handleClick() {  
        let me = players[currentUserIndex];  
        if(me.isBanned) { alert("Вы забанены! Действия недоступны"); return; }  
        let gain = getClickPower();  
        me.mainMoney += gain;  
        updateTotalScores();  
        refreshAllUI();  
    }  
  
    // покупка зелья игроком  
    function buyPotion() {  
        let me = players[currentUserIndex];  
        let cost = 80 + potionLevel * 25;  
        if(me.mainMoney >= cost) {  
            me.mainMoney -= cost;  
            if(potionTimer) clearInterval(potionTimer);  
            potionActive = true;  
            let duration = 25;  
            let secs = duration;  
            potionTimer = setInterval(()=> {  
                secs--;  
                if(secs <= 0) { clearInterval(potionTimer); potionActive = false; potionTimer=null; refreshAllUI();}  
                refreshAllUI();  
            },1000);  
            refreshAllUI();  
        } else alert(`Не хватает ${cost} монет (осн.счёт)`);  
    }  
  
    function upgradePotion() {  
        let me = players[currentUserIndex];  
        let cost = 120 + potionLevel * 35;  
        if(me.mainMoney >= cost) {  
            me.mainMoney -= cost;  
            potionLevel++;  
            refreshAllUI();  
        } else alert(`Не хватает ${cost}`);  
    }  
  
    // смена имени  
    function changeMyName(newName) {  
        if(!newName.trim()) return;  
        let me = players[currentUserIndex];  
        me.name = newName;  
        refreshAllUI();  
    }  
  
    // обработчики админ-панели с проверкой роли  
    function setupEventListeners() {  
        const me = () => players[currentUserIndex];  
        document.getElementById('clickMainBtn').onclick = handleClick;  
        document.getElementById('buyPotionBtn').onclick = buyPotion;  
        document.getElementById('upgradePotionBtn').onclick = upgradePotion;  
  
        document.getElementById('addMoneyMainBtn').onclick = () => { let amt = parseInt(document.getElementById('adminAmount').value)||0; changeMoney(currentUserIndex, amt, 0, me().role); };  
        document.getElementById('addMoneyVipBtn').onclick = () => { let amt = parseInt(document.getElementById('adminAmount').value)||0; changeMoney(currentUserIndex, 0, amt, me().role); };  
        document.getElementById('removeMoneyBtn').onclick = () => { let amt = parseInt(document.getElementById('adminAmount').value)||0; changeMoney(currentUserIndex, -amt, 0, me().role); };  
        document.getElementById('setMoneyMainBtn').onclick = () => { let amt = parseInt(document.getElementById('adminAmount').value)||0; setMoney(currentUserIndex, amt, me().role); };  
        document.getElementById('adminGivePotionBtn').onclick = () => { let sec = parseInt(document.getElementById('potionSlider').value); adminGivePotion(sec, me().role); };  
        document.getElementById('banUserBtn').onclick = () => { let name = document.getElementById('banNameInput').value; banPlayerByName(me().role, name); };  
        document.getElementById('unbanUserBtn').onclick = () => { let name = document.getElementById('banNameInput').value; unbanPlayerByName(me().role, name); };  
        document.getElementById('resetGameBtn').onclick = () => { resetGame(me().role); };  
        document.getElementById('sendBugBtn').onclick = () => { let txt = document.getElementById('bugText').value; if(txt) addBugReport(me().name, txt); document.getElementById('bugText').value=''; };  
        document.getElementById('clearReportsBtn').onclick = () => { if(canClearReports(me().role)) { bugReports = []; refreshAllUI(); alert("Репорты очищены");} else alert("Нет прав"); };  
        document.getElementById('sendGlobalMsgBtn').onclick = () => { let txt = document.getElementById('msgInput').value; let target = document.getElementById('msgTargetRole').value; addGlobalMessage(me().role, txt, target); document.getElementById('msgInput').value=''; };  
        document.getElementById('changeNameBtn').onclick = () => { let newn = document.getElementById('playerNameInput').value; changeMyName(newn); };  
        document.getElementById('applyRoleBtn').onclick = () => { let newRole = document.getElementById('roleSelect').value; if(me().role !== 'owner' && newRole !== me().role) { alert("Сменить роль может только владелец через демо, но для симуляции: обычные не могут стать админами"); return; } players[currentUserIndex].role = newRole; refreshAllUI(); alert(`Роль изменена на ${newRole}`); };  
        document.getElementById('potionSlider').oninput = (e) => { document.getElementById('potionSecVal').innerText = e.target.value; };  
    }  
  
    // инициализация  
    initPlayers();  
    refreshAllUI();  
    setupEventListeners();  
    // синхрон слайдера  
    document.getElementById('potionSecVal').innerText = document.getElementById('potionSlider').value;  
</script>  
</body>  
</html>  
