<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>KIRA WORK'S</title>
    <script src="https://telegram.org/js/telegram-web-app.js"></script>
    <style>
        :root {
            --bg-dark: #080808;
            --bg-card: #121212;
            --card-border: #262626;
            --gold-primary: #f5c518;
            --gold-gradient: linear-gradient(135deg, #d4af37, #fff2a3, #aa771c);
            --gold-glow: rgba(212, 175, 55, 0.2);
            --text-white: #ffffff;
            --text-muted: #8e8e93;
            --nav-bg: #0f0f0f;
            --success: #30d158;
            --danger: #ff453a;
        }

        * { margin: 0; padding: 0; box-sizing: border-box; font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif; -webkit-tap-highlight-color: transparent; }
        body { background-color: var(--bg-dark); color: var(--text-white); padding-bottom: 85px; overflow-x: hidden; }

        /* Top Header */
        .top-bar { background: var(--nav-bg); border-bottom: 1px solid var(--card-border); padding: 14px 18px; display: flex; align-items: center; justify-content: space-between; position: sticky; top: 0; z-index: 100; }
        .user-profile { display: flex; align-items: center; gap: 12px; }
        .avatar { width: 42px; height: 42px; border-radius: 50%; border: 2px solid var(--gold-primary); box-shadow: 0 0 10px var(--gold-glow); object-fit: cover; }
        .user-meta h3 { font-size: 15px; font-weight: 700; color: var(--text-white); }
        .user-meta span { font-size: 11px; color: var(--gold-primary); font-weight: 500; }
        .user-id-badge { background: #1c1c1e; border: 1px solid var(--card-border); padding: 4px 10px; border-radius: 20px; font-size: 11px; color: var(--text-muted); font-weight: 600; }

        /* Balance Hero Card */
        .balance-hero { background: linear-gradient(180deg, #181818, #101010); border: 1px solid rgba(212, 175, 55, 0.35); border-radius: 20px; margin: 12px 16px 20px; padding: 24px 20px; text-align: center; box-shadow: 0 8px 24px var(--gold-glow); }
        .balance-subtitle { font-size: 11px; letter-spacing: 1.2px; color: var(--text-muted); text-transform: uppercase; margin-bottom: 6px; }
        .balance-amount { font-size: 40px; font-weight: 900; color: #ffffff; margin-bottom: 8px; }
        .balance-amount span { color: var(--gold-primary); margin-right: 2px; }

        /* Container & Sections */
        .content-area { padding: 0 16px; }
        .tab-section { display: none; animation: fadeIn 0.25s ease-in-out; }
        .tab-section.active { display: block; }
        @keyframes fadeIn { from { opacity: 0; transform: translateY(6px); } to { opacity: 1; transform: translateY(0); } }

        .section-label { font-size: 13px; font-weight: 800; color: var(--gold-primary); text-transform: uppercase; letter-spacing: 1px; margin: 18px 4px 12px; display: flex; align-items: center; gap: 6px; }

        /* Card Styles */
        .task-card { background: var(--bg-card); border: 1px solid var(--card-border); border-radius: 16px; padding: 18px; margin-bottom: 14px; box-shadow: 0 4px 12px rgba(0,0,0,0.4); }
        .card-top { display: flex; justify-content: space-between; align-items: center; margin-bottom: 8px; }
        .card-heading { font-size: 16px; font-weight: 700; color: #fff; }
        .reward-tag { font-size: 16px; font-weight: 800; color: var(--gold-primary); }
        .card-text { font-size: 13px; color: var(--text-muted); line-height: 1.45; margin-bottom: 16px; }

        /* Buttons & Inputs */
        .btn-gold { width: 100%; padding: 13px; background: var(--gold-gradient); border: none; border-radius: 12px; font-size: 14px; font-weight: 800; color: #000; text-transform: uppercase; cursor: pointer; box-shadow: 0 4px 14px var(--gold-glow); margin-bottom: 10px; transition: 0.2s;}
        .btn-gold:active { transform: scale(0.96); }
        .btn-outline { width: 100%; padding: 12px; background: transparent; border: 1px solid var(--gold-primary); border-radius: 12px; font-size: 14px; font-weight: 700; color: var(--gold-primary); cursor: pointer; margin-bottom: 10px; transition: 0.2s;}
        .btn-outline:active { transform: scale(0.96); background: rgba(212, 175, 55, 0.1); }
        
        .flex-row { display: flex; gap: 10px; }
        
        textarea.admin-input { width: 100%; background: #000; border: 1px solid var(--gold-primary); color: #fff; padding: 12px; border-radius: 10px; height: 100px; font-size: 12px; resize: none; margin-bottom: 15px; outline: none; }
        textarea.admin-input:focus { box-shadow: 0 0 10px var(--gold-glow); }

        /* Bottom Navigation */
        .bottom-nav { position: fixed; bottom: 0; left: 0; width: 100%; background: var(--nav-bg); border-top: 1px solid var(--card-border); display: flex; justify-content: space-around; padding: 10px 0 16px; z-index: 200; }
        .nav-button { background: none; border: none; color: var(--text-muted); font-size: 11px; font-weight: 600; display: flex; flex-direction: column; align-items: center; gap: 4px; cursor: pointer; }
        .nav-button .nav-icon { font-size: 20px; filter: grayscale(100%); transition: 0.2s; }
        .nav-button.active { color: var(--gold-primary); }
        .nav-button.active .nav-icon { filter: grayscale(0%); transform: scale(1.15); }

        #nav-admin { display: none; } 
    </style>
</head>
<body>

    <!-- Header -->
    <header class="top-bar">
        <div class="user-profile">
            <img id="userAvatar" class="avatar" src="https://ui-avatars.com/api/?name=User&background=121212&color=f5c518" alt="Profile">
            <div class="user-meta">
                <h3 id="userName">Kira Worker</h3>
                <span>Verified Worker ⚡</span>
            </div>
        </div>
        <div class="user-id-badge">ID: <span id="userId">---</span></div>
    </header>

    <main class="content-area">

        <!-- 1. WALLET SECTION -->
        <section id="tab-wallet" class="tab-section active">
            <div style="text-align: center; margin: 10px 0 20px;">
                <h1 style="font-size: 26px; color: var(--gold-primary); font-weight: 900; letter-spacing: 2px;">KIRA WORK'S</h1>
            </div>
            
            <div class="balance-hero">
                <div class="balance-subtitle">Total Vault Balance</div>
                <div class="balance-amount"><span>₹</span><span id="walletBalance">0.00</span></div>
            </div>
            <button class="btn-gold" onclick="sendAction('request_withdraw')">🔀 Request Withdrawal</button>
        </section>

        <!-- 2. REVIEW TASKS SECTION -->
        <section id="tab-review" class="tab-section">
            <div class="section-label">📍 Map Review Tasks</div>
            <div class="task-card">
                <div class="card-top">
                    <div class="card-heading">Single Map Review</div>
                    <div class="reward-tag">₹ 10.00</div>
                </div>
                <div class="card-text">Open the direct map link, give a 5-star rating, and post the provided comment.</div>
                <button class="btn-gold" onclick="sendAction('start_single_review')">Start Single Task</button>
                <button class="btn-outline" onclick="sendAction('start_bulk_review')">Claim Bulk Pack (10x)</button>
            </div>
        </section>

        <!-- 3. GMAIL TASKS SECTION -->
        <section id="tab-gmail" class="tab-section">
            <div class="section-label">✉️ Gmail Account Tasks</div>
            <div class="task-card">
                <div class="card-top">
                    <div class="card-heading">Available Gmail Tasks</div>
                    <div class="reward-tag">₹ 10.00</div>
                </div>
                <div class="card-text">Create fresh Gmail accounts securely and submit the ID & Password.</div>
                <button class="btn-gold" onclick="sendAction('start_single_gmail')">Start Single Task</button>
                <button class="btn-outline" onclick="sendAction('start_bulk_gmail')">Claim Bulk Pack (5x)</button>
            </div>
        </section>

        <!-- 4. HELP & SUPPORT SECTION -->
        <section id="tab-help" class="tab-section">
            <div class="section-label">🎧 Help & Support</div>
            <div class="task-card">
                <h3 style="color: var(--gold-primary); margin-bottom: 10px;">We are here to help you!</h3>
                <p class="card-text">If your task is rejected unfairly or your withdrawal is delayed, please contact the admin directly.</p>
                <button class="btn-gold" onclick="openLink('https://t.me/KIRABOSS09')">💬 Chat with Admin</button>
            </div>
        </section>

        <!-- 5. ADMIN PANEL (Only visible to Admin) -->
        <section id="tab-admin" class="tab-section">
            <div class="section-label">👑 Boss Control Panel</div>
            
            <!-- NEW: WORK PROOF SECTION -->
            <div class="task-card" style="border-color: var(--gold-primary);">
                <div class="card-heading" style="color: var(--gold-primary); margin-bottom: 5px;">📸 WORK PROOF</div>
                <p style="font-size: 11px; color: var(--text-muted); margin-bottom: 12px;">Approve or Reject pending user submissions.</p>
                <div class="flex-row">
                    <button class="btn-gold" style="font-size:12px;" onclick="sendAction('admin_proof_review')">📍 Review Proofs</button>
                    <button class="btn-gold" style="font-size:12px;" onclick="sendAction('admin_proof_gmail')">📧 Gmail Proofs</button>
                </div>
            </div>

            <!-- NEW: LIST OF WORK SECTION -->
            <div class="task-card">
                <div class="card-heading" style="margin-bottom: 5px;">📋 LIST OF WORK</div>
                <p style="font-size: 11px; color: var(--text-muted); margin-bottom: 12px;">View all approved and rejected user tasks.</p>
                <div class="flex-row">
                    <button class="btn-outline" style="font-size:12px;" onclick="sendAction('admin_list_review')">📍 Review List</button>
                    <button class="btn-outline" style="font-size:12px;" onclick="sendAction('admin_list_gmail')">📧 Gmail List</button>
                </div>
            </div>

            <!-- ADD WORK SECTION -->
            <div class="task-card">
                <div class="card-heading" style="margin-bottom: 10px;">➕ Add Bulk Reviews</div>
                <textarea id="admin-review-data" class="admin-input" placeholder="https://maps.app.goo.gl/... | Very good place!&#10;https://maps.app.goo.gl/... | Best service!"></textarea>
                <button class="btn-gold" onclick="submitAdminTasks('review')">Upload Reviews</button>
            </div>

            <div class="task-card">
                <div class="card-heading" style="margin-bottom: 10px;">➕ Add Bulk Gmails</div>
                <textarea id="admin-gmail-data" class="admin-input" placeholder="user1@gmail.com | Pass123@&#10;user2@gmail.com | Pass456@"></textarea>
                <button class="btn-gold" onclick="submitAdminTasks('gmail')">Upload Gmails</button>
            </div>
        </section>

    </main>

    <!-- Bottom Navigation Bar -->
    <nav class="bottom-nav">
        <button class="nav-button active" onclick="navigate('wallet', this)">
            <span class="nav-icon">👛</span><span>Wallet</span>
        </button>
        <button class="nav-button" onclick="navigate('review', this)">
            <span class="nav-icon">📍</span><span>Review</span>
        </button>
        <button class="nav-button" onclick="navigate('gmail', this)">
            <span class="nav-icon">📧</span><span>Gmail</span>
        </button>
        <button class="nav-button" onclick="navigate('help', this)">
            <span class="nav-icon">🎧</span><span>Help</span>
        </button>
        <!-- Admin Button -->
        <button class="nav-button" id="nav-admin" onclick="navigate('admin', this)">
            <span class="nav-icon">👑</span><span>Admin</span>
        </button>
    </nav>

    <script>
        const tg = window.Telegram ? window.Telegram.WebApp : null;

        // YAHAN APNI TELEGRAM ID DAALEIN
        const ADMIN_IDS = [7246962358, 8138283513, 724051786]; 

        if (tg) {
            tg.expand();
            tg.ready();
        }

        // Fetch User Data & Check Admin
        function loadUserData() {
            let name = "Kira Worker";
            let uid = "0000000";
            
            if (tg && tg.initDataUnsafe && tg.initDataUnsafe.user) {
                const u = tg.initDataUnsafe.user;
                name = u.first_name + (u.last_name ? " " + u.last_name : "");
                uid = u.id.toString();
                if(u.photo_url) document.getElementById('userAvatar').src = u.photo_url;
                else document.getElementById('userAvatar').src = `https://ui-avatars.com/api/?name=${encodeURIComponent(name)}&background=121212&color=f5c518`;
            }

            document.getElementById('userName').innerText = name;
            document.getElementById('userId').innerText = uid;

            const urlParams = new URLSearchParams(window.location.search);
            document.getElementById('walletBalance').innerText = urlParams.get('bal') || "0.00";

            // Show Admin Tab if Admin
            if (ADMIN_IDS.includes(parseInt(uid))) {
                document.getElementById('nav-admin').style.display = 'flex';
            }
        }

        function navigate(viewId, btnElem) {
            document.querySelectorAll('.tab-section').forEach(sec => sec.classList.remove('active'));
            document.querySelectorAll('.nav-button').forEach(btn => btn.classList.remove('active'));
            
            document.getElementById('tab-' + viewId).classList.add('active');
            if(btnElem) btnElem.classList.add('active');

            if (tg && tg.HapticFeedback) tg.HapticFeedback.impactOccurred('light');
        }

        function sendAction(actionName) {
            if (tg && tg.HapticFeedback) tg.HapticFeedback.notificationOccurred('success');
            if (tg && tg.sendData) {
                tg.sendData(JSON.stringify({ action: actionName }));
                tg.close();
            }
        }

        function submitAdminTasks(type) {
            const textArea = document.getElementById('admin-' + type + '-data');
            const dataText = textArea.value.trim();
            
            if (!dataText) {
                if (tg && tg.showAlert) tg.showAlert("⚠️ Please enter some tasks first!");
                else alert("⚠️ Please enter some tasks first!");
                return;
            }

            if (tg && tg.sendData) {
                tg.sendData(JSON.stringify({ 
                    action: "admin_add_bulk_" + type, 
                    payload: dataText 
                }));
                tg.close();
            }
        }

        function openLink(url) {
            tg.openTelegramLink ? tg.openTelegramLink(url) : window.open(url, '_blank');
        }

        window.onload = loadUserData;
    </script>
</body>
</html>

