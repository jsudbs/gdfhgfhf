vibeprinz
vibeprinz
Unsichtbar

Kaiser Silas
 hat einen Anruf gestartet, der ein paar Sekunden gedauert hat. — gestern um 20:30 Uhr
Kaiser Silas
 hat einen Anruf gestartet, der eine Stunde gedauert hat. — gestern um 20:30 Uhr
vibeprinz — gestern um 20:31 Uhr
https://www.deepseek.com/
DeepSeek | 深度求索
深度求索（DeepSeek），成立于2023年，专注于研究世界领先的通用人工智能底层模型与技术，挑战人工智能前沿性难题。基于自研训练框架、自建智算集群和万卡算力等资源，深度求索团队仅用半年时间便已发布并开源多个百亿级参数大模型，如DeepSeek-LLM通用大语...
DeepSeek | 深度求索
https://code.visualstudio.com/
Visual Studio Code - The open source AI code editor
Visual Studio Code redefines AI-powered coding with GitHub Copilot for building and debugging modern web and cloud applications. Visual Studio Code is free and available on your favorite platform - Linux, macOS, and Windows.
Visual Studio Code - The open source AI code editor
vibeprinz — gestern um 21:07 Uhr
TWINT ist eine mobile Bezahl-App aus der Schweiz 🇨🇭

Damit kannst du mit dem Smartphone einfach und schnell Geld bezahlen oder senden, ohne Bargeld oder Karte.

Kurz erklärt:

📱 Bezahlen im Laden (QR-Code scannen)
🛒 Online einkaufen
💸 Geld an Freunde schicken (per Telefonnummer)
🏦 Direkt mit deinem Schweizer Bankkonto verknüpft

TWINT funktioniert ähnlich wie PayPal oder Apple Pay, ist aber speziell für die Schweiz und dort extrem verbreitet.
Kaiser Silas — gestern um 21:36 Uhr
boah
ich feuer ab
vibeprinz — gestern um 21:54 Uhr
https://discord.gg/UpFs3nQK
Filmeabend
Filmeabend
40 online
89 Mitglieder
Gegründet am Okt. 2025

Zum Server
Kaiser Silas — gestern um 22:04 Uhr
hat jetzt alles geklappt
Kaiser Silas — gestern um 23:10 Uhr
Kannst du morgen mir helfen das online zu stellen
vibeprinz — gestern um 23:10 Uhr
seht gut
vibeprinz — gestern um 23:10 Uhr
ja
warte
bist du jetzt noch da?
@Kaiser Silas
Kaiser Silas — gestern um 23:13 Uhr
ja
aber gehe ins bett
muss da eh noch morgen was ändern
dann kann ich es erst online stellen
vibeprinz — gestern um 23:14 Uhr
Alles
Klar
Bin morgen erst gegen 19 Uhr zuhause
Kaiser Silas — gestern um 23:16 Uhr
Ja egal passt ja
Hoffe das klappt dann auch morgen alles
Kaiser Silas — 19:04
Bin wahrscheinlich erst so um 20:30 Uhr da
vibeprinz — 19:32
Ruf mich dann einfach an dann komme ich an den PC
Du hast einen Anruf von 
Kaiser Silas
 verpasst, der 3 Minuten gedauert hat. — 20:55
Kaiser Silas
 hat einen Anruf gestartet. — 21:01
vibeprinz — 21:03
Warte komme jetzt
Kaiser Silas — 21:10
warte kurz
vibeprinz — 21:12
jo
Kaiser Silas — 21:45
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Offene Beträge</title>

message.txt
46 kB
﻿
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Offene Beträge</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #6a11cb 0%, #2575fc 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }
        
        .container {
            max-width: 500px;
            width: 100%;
            display: flex;
            flex-direction: column;
            gap: 30px;
        }
        
        .header {
            text-align: center;
            color: white;
            padding: 20px;
            border-radius: 15px;
            background-color: rgba(0, 0, 0, 0.2);
            backdrop-filter: blur(10px);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
        }
        
        .header h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }
        
        .login-card, .result-card, .admin-login-card, .admin-card {
            background-color: white;
            border-radius: 15px;
            padding: 40px;
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.2);
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 25px;
        }
        
        .result-card, .admin-login-card, .admin-card {
            display: none;
        }
        
        .card-title {
            font-size: 1.8rem;
            color: #333;
            margin-bottom: 10px;
            text-align: center;
        }
        
        .input-group {
            width: 100%;
            max-width: 400px;
        }
        
        .input-group label {
            display: block;
            margin-bottom: 8px;
            font-weight: 600;
            color: #555;
        }
        
        .code-input, .admin-input {
            width: 100%;
            padding: 15px;
            border: 2px solid #ddd;
            border-radius: 10px;
            font-size: 1.2rem;
            text-align: center;
            transition: all 0.3s;
        }
        
        .code-input:focus, .admin-input:focus {
            border-color: #6a11cb;
            outline: none;
            box-shadow: 0 0 0 3px rgba(106, 17, 203, 0.2);
        }
        
        .btn {
            background: linear-gradient(to right, #6a11cb, #2575fc);
            color: white;
            border: none;
            padding: 15px 40px;
            font-size: 1.2rem;
            border-radius: 10px;
            cursor: pointer;
            transition: all 0.3s;
            font-weight: 600;
            width: 100%;
            max-width: 400px;
        }
        
        .btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 7px 15px rgba(0, 0, 0, 0.2);
        }
        
        .btn:active {
            transform: translateY(0);
        }
        
        .logout-btn, .back-btn {
            background: #f8f9fa;
            color: #333;
            border: 1px solid #ddd;
            padding: 10px 25px;
            margin-top: 10px;
            width: auto;
        }
        
        .admin-btn {
            background: #ff9800;
            color: white;
            margin-top: 10px;
        }
        
        .amount-display {
            text-align: center;
            padding: 30px;
            background: linear-gradient(135deg, #f5f7fa 0%, #e4edf5 100%);
            border-radius: 10px;
            width: 100%;
            max-width: 500px;
        }
        
        .person-name {
            font-size: 2rem;
            color: #333;
            margin-bottom: 10px;
        }
        
        .person-fullname {
            font-size: 1.5rem;
            color: #555;
            margin-bottom: 20px;
            font-style: italic;
        }
        
        .amount {
            font-size: 3.5rem;
            font-weight: 700;
            color: #2575fc;
            margin-bottom: 10px;
        }
        
        .amount-label {
            color: #666;
            font-size: 1.2rem;
            margin-bottom: 25px;
        }
        
        .details-table {
            width: 100%;
            max-width: 500px;
            margin-top: 20px;
            border-collapse: collapse;
            background-color: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 3px 10px rgba(0, 0, 0, 0.1);
        }
        
        .details-table th {
            background-color: #f8f9fa;
            padding: 15px;
            text-align: left;
            color: #333;
            font-weight: 600;
            border-bottom: 2px solid #e9ecef;
        }
        
        .details-table td {
            padding: 15px;
            border-bottom: 1px solid #e9ecef;
        }
        
        .details-table tr:last-child td {
            border-bottom: none;
        }
        
        .error-message {
            color: #e74c3c;
            text-align: center;
            margin-top: 10px;
            font-weight: 600;
            display: none;
        }
        
        .success-message {
            color: #27ae60;
            text-align: center;
            margin-top: 10px;
            font-weight: 600;
            display: none;
        }
        
        .paste-area {
            width: 100%;
            height: 150px;
            padding: 15px;
            border: 2px dashed #ddd;
            border-radius: 10px;
            font-family: monospace;
            font-size: 0.9rem;
            margin-bottom: 15px;
            background: #f8f9fa;
        }
        
        .paste-area:focus {
            border-color: #6a11cb;
            outline: none;
            background: white;
        }
        
        .instructions-box {
            background: rgba(255, 255, 255, 0.1);
            border-radius: 10px;
            padding: 15px;
            color: white;
            font-size: 0.9rem;
            margin-top: 10px;
        }
        
        .tab-buttons {
            display: flex;
            gap: 10px;
            margin-bottom: 20px;
            flex-wrap: wrap;
            justify-content: center;
        }
        
        .tab-btn {
            background: #3498db;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 0.9rem;
        }
        
        .tab-btn.active {
            background: #2980b9;
            font-weight: bold;
        }
        
        .tab-content {
            display: none;
            width: 100%;
        }
        
        .tab-content.active {
            display: block;
        }
        
        .data-overview {
            background-color: white;
            border-radius: 10px;
            padding: 15px;
            margin-top: 20px;
            overflow-x: auto;
            max-height: 400px;
            overflow-y: auto;
        }
        
        .data-overview table {
            width: 100%;
            border-collapse: collapse;
            font-size: 0.9rem;
        }
        
        .data-overview th {
            background-color: #f8f9fa;
            padding: 10px;
            text-align: left;
            border: 1px solid #ddd;
            position: sticky;
            top: 0;
        }
        
        .data-overview td {
            padding: 8px;
            border: 1px solid #ddd;
            font-size: 0.8rem;
        }
        
        .action-buttons {
            display: flex;
            gap: 10px;
            margin-top: 15px;
            flex-wrap: wrap;
            justify-content: center;
        }
        
        .action-btn {
            background: #2ecc71;
            color: white;
            border: none;
            padding: 10px 15px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 0.9rem;
        }
        
        .action-btn.secondary {
            background: #95a5a6;
        }
        
        .action-btn.export {
            background: #9b59b6;
        }
        
        @media (max-width: 768px) {
            .container {
                gap: 20px;
                max-width: 95%;
            }
            
            .login-card, .result-card, .admin-login-card, .admin-card {
                padding: 30px 20px;
            }
            
            .header h1 {
                font-size: 2rem;
            }
            
            .amount {
                font-size: 2.8rem;
            }
            
            .person-name {
                font-size: 1.8rem;
            }
            
            .person-fullname {
                font-size: 1.3rem;
            }
            
            .tab-buttons {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>Offene Beträge</h1>
        </div>
        
        <!-- Haupt-Login für Schüler -->
        <div class="login-card" id="loginCard">
            <h2 class="card-title">Login mit Passwort</h2>
            <div class="input-group">
                <label for="code">Ihr persönliches Passwort:</label>
                <input type="text" id="code" class="code-input" placeholder="Ihr Passwort" maxlength="20">
                <div class="error-message" id="errorMessage">Ungültiges Passwort. Bitte versuchen Sie es erneut.</div>
            </div>
            <button class="btn" id="loginBtn">Einloggen</button>
            <button class="btn admin-btn" id="adminAccessBtn">⚙️ Admin-Bereich</button>
        </div>
        
        <!-- Ergebnis-Anzeige für Schüler -->
        <div class="result-card" id="resultCard">
            <div class="amount-display">
                <div class="person-name" id="personName">Name</div>
                <div class="person-fullname" id="personFullName">Vor- und Nachname</div>
                <div class="amount" id="amountDisplay">0,00 €</div>
                <div class="amount-label">offener Betrag</div>
                
                <table class="details-table">
                    <tr>
                        <th>Information</th>
                        <th>Wert</th>
                    </tr>
                    <tr>
                        <td>Nachname:</td>
                        <td id="lastName">-</td>
                    </tr>
                    <tr>
                        <td>Vorname:</td>
                        <td id="firstName">-</td>
                    </tr>
                    <tr>
                        <td>Persönliches Passwort:</td>
                        <td id="userPassword">-</td>
                    </tr>
                    <tr>
                        <td>Status:</td>
                        <td id="statusDisplay">-</td>
                    </tr>
                </table>
            </div>
            <button class="btn logout-btn" id="logoutBtn">Zurück zum Login</button>
        </div>
        
        <!-- Admin-Login -->
        <div class="admin-login-card" id="adminLoginCard">
            <h2 class="card-title">Admin-Login</h2>
            <div class="input-group">
                <label for="adminPassword">Admin-Passwort eingeben:</label>
                <input type="password" id="adminPassword" class="admin-input" placeholder="Passwort" maxlength="10">
                <div class="error-message" id="adminLoginError">Ungültiges Passwort.</div>
            </div>
            <button class="btn" id="adminLoginBtn">Als Admin einloggen</button>
            <button class="btn back-btn" id="backToMainBtn">← Zurück zur Hauptseite</button>
        </div>
        
        <!-- Admin-Bereich -->
        <div class="admin-card" id="adminCard">
            <h2 class="card-title">⚙️ Admin-Bereich</h2>
            
            <div class="tab-buttons">
                <button class="tab-btn active" data-tab="betraege">💰 Beträge aktualisieren</button>
                <button class="tab-btn" data-tab="passwoerter">🔑 Passwörter ändern</button>
                <button class="tab-btn" data-tab="uebersicht">📋 Datenübersicht</button>
            </div>
            
            <!-- Tab 1: Beträge aktualisieren -->
            <div class="tab-content active" id="tab-betraege">
                <div class="input-group">
                    <label for="betraegeInput">Kopierte Beträge einfügen:</label>
                    <textarea id="betraegeInput" class="paste-area" placeholder="Kopiere hier die Werte aus deiner Beträge-Spalte...
                    
Beispiel:
80
100
80
0
80
0
..."></textarea>
                    <div class="success-message" id="betraegeSuccess"></div>
                    <div class="error-message" id="betraegeError"></div>
                </div>
                
                <div class="action-buttons">
                    <button class="action-btn" id="updateBetraegeBtn">🔄 Beträge aktualisieren</button>
                    <button class="action-btn secondary" id="showBetraegeExampleBtn">📋 Beispiel anzeigen</button>
                </div>
            </div>
            
            <!-- Tab 2: Passwörter ändern -->
            <div class="tab-content" id="tab-passwoerter">
                <div class="input-group">
                    <label for="passwoerterInput">Neue Passwörter (pro Zeile eins):</label>
                    <textarea id="passwoerterInput" class="paste-area" placeholder="Neue Passwörter für jeden Schüler...
                    
Beispiel:
valerie123
lea456
lennox789
..."></textarea>
                    <div class="success-message" id="passwoerterSuccess"></div>
                    <div class="error-message" id="passwoerterError"></div>
                </div>
                
                <div class="action-buttons">
                    <button class="action-btn" id="updatePasswoerterBtn">🔑 Passwörter aktualisieren</button>
                    <button class="action-btn secondary" id="showPasswoerterBtn">👁️ Aktuelle Passwörter anzeigen</button>
                </div>
            </div>
            
            <!-- Tab 3: Datenübersicht -->
            <div class="tab-content" id="tab-uebersicht">
                <div class="data-overview" id="dataOverview">
                    <table>
                        <thead>
                            <tr>
                                <th>Code</th>
                                <th>Nachname</th>
                                <th>Vorname</th>
                                <th>Betrag</th>
                                <th>Status</th>
                                <th>Login-Passwort</th>
                            </tr>
                        </thead>
                        <tbody id="overviewTableBody">
                            <!-- Daten werden hier eingefügt -->
                        </tbody>
                    </table>
                </div>
                
                <div class="action-buttons">
                    <button class="action-btn" id="refreshOverviewBtn">🔄 Aktualisieren</button>
                    <button class="action-btn export" id="exportDataBtn">📥 Alle Daten exportieren</button>
                </div>
            </div>
            
            <div class="instructions-box">
                <strong>📋 So einfach geht's:</strong>
                <ol style="margin-left: 20px; margin-top: 10px;">
                    <li><strong>Schüler login:</strong> Jetzt nur noch mit persönlichem Passwort (nicht Code!)</li>
                    <li><strong>Beträge:</strong> Ganze Beträge-Spalte kopieren & einfügen</li>
                    <li><strong>Passwörter:</strong> Neue Login-Passwörter (pro Schüler eins) eintragen</li>
                    <li><strong>Datenübersicht:</strong> Alle aktuellen Daten einsehen</li>
                </ol>
            </div>
            
            <button class="btn back-btn" id="adminLogoutBtn">← Zurück zur Hauptseite</button>
        </div>
    </div>

    <script>
        // ================= KONFIGURATION =================
        const ADMIN_PASSWORT = "1578"; // Dein Admin-Passwort
        
        // ================= FESTE SCHÜLERDATEN =================
        let schuelerDaten = [
            { code: "1", lastName: "Ackerschott", firstName: "Valerie Marie", amount: 80, password: "valerie123" },
            { code: "2", lastName: "Albrecht", firstName: "Lea Sophia", amount: 100, password: "lea456" },
            { code: "3", lastName: "Altendorf", firstName: "Lennox", amount: 80, password: "lennox789" },
            { code: "4", lastName: "Andrys", firstName: "Kaj Solomon", amount: 0, password: "kaj012" },
            { code: "5", lastName: "Bartko", firstName: "Tim Julio", amount: 80, password: "tim345" },
            { code: "6", lastName: "Behrens", firstName: "Marlene", amount: 0, password: "marlene678" },
            { code: "7", lastName: "Berger", firstName: "Marius", amount: 80, password: "marius901" },
            { code: "8", lastName: "Biltner", firstName: "Lars Simeon", amount: 80, password: "lars234" },
            { code: "9", lastName: "Böhm", firstName: "Max", amount: 80, password: "max567" },
            { code: "10", lastName: "Breidenbach", firstName: "Jonas", amount: 80, password: "jonas890" },
            { code: "11", lastName: "Brieden", firstName: "Hannah Carin", amount: 80, password: "hannah123" },
            { code: "12", lastName: "Bünger", firstName: "Leni", amount: 80, password: "leni456" },
            { code: "13", lastName: "Burwitz", firstName: "Aaron Alexander", amount: 80, password: "aaron789" },
            { code: "14", lastName: "Contzen", firstName: "Emilia", amount: 100, password: "emilia012" },
            { code: "15", lastName: "Daase", firstName: "Sophie", amount: 0, password: "sophie345" },
            { code: "16", lastName: "Deitert", firstName: "Lara Alessandra", amount: 80, password: "lara678" },
            { code: "17", lastName: "Dietrich", firstName: "Linda", amount: 0, password: "linda901" },
            { code: "18", lastName: "Dreiner", firstName: "Johannes Stephan", amount: 80, password: "johannes234" },
            { code: "19", lastName: "Dreßen", firstName: "Mathilda Luise", amount: 60, password: "mathilda567" },
            { code: "20", lastName: "Duran", firstName: "Chiara", amount: 80, password: "chiara890" },
            { code: "21", lastName: "Eschmann", firstName: "Sophie", amount: 0, password: "sophie21" },
            { code: "22", lastName: "Flosbach", firstName: "Benedikt Paul", amount: 80, password: "benedikt22" },
            { code: "23", lastName: "Forche", firstName: "Annika", amount: 0, password: "annika23" },
            { code: "24", lastName: "Frank", firstName: "Elisabeth", amount: 0, password: "elisabeth24" },
            { code: "25", lastName: "Gökce", firstName: "Kerim Ihsan", amount: 80, password: "kerim25" },
            { code: "26", lastName: "Goth", firstName: "Jasmin", amount: 80, password: "jasmin26" },
            { code: "27", lastName: "Grzelak", firstName: "Leyla", amount: 80, password: "leyla27" },
            { code: "28", lastName: "Haberzeth", firstName: "Lisa", amount: 80, password: "lisa28" },
            { code: "29", lastName: "Hausberg", firstName: "Arian", amount: 80, password: "arian29" },
            { code: "30", lastName: "Hegering", firstName: "Nelly Sophie", amount: 80, password: "nelly30" },
            { code: "31", lastName: "Heinemann", firstName: "Charlotte", amount: 0, password: "charlotte31" },
            { code: "32", lastName: "Hilger", firstName: "Lilli", amount: 80, password: "lilli32" },
            { code: "33", lastName: "Höck", firstName: "Julius", amount: 80, password: "julius33" },
            { code: "34", lastName: "Hoppe", firstName: "Liona Katharina", amount: 80, password: "liona34" },
            { code: "35", lastName: "Huckenbeck", firstName: "Romy", amount: 80, password: "romy35" },
            { code: "36", lastName: "Irlenbusch", firstName: "Mats", amount: 0, password: "mats36" },
            { code: "37", lastName: "Johnen", firstName: "Jayce", amount: 0, password: "jayce37" },
            { code: "38", lastName: "Johnen", firstName: "Joyce", amount: 0, password: "joyce38" },
            { code: "39", lastName: "Jung", firstName: "Kayla Madison", amount: 0, password: "kayla39" },
            { code: "40", lastName: "Kämmer", firstName: "Lina", amount: 80, password: "lina40" },
            { code: "41", lastName: "Klären", firstName: "Florian René", amount: 0, password: "florian41" },
            { code: "42", lastName: "Kösük", firstName: "Selim", amount: 80, password: "selim42" },
            { code: "43", lastName: "Krämer", firstName: "Amaia", amount: 80, password: "amaia43" },
            { code: "44", lastName: "Lasarzik", firstName: "Lisa Mali", amount: 80, password: "lisa44" },
            { code: "45", lastName: "Letzel", firstName: "Klara Anna", amount: 0, password: "klara45" },
            { code: "46", lastName: "Leue", firstName: "Lina", amount: 0, password: "lina46" },
            { code: "47", lastName: "Lieder", firstName: "Michael", amount: 105, password: "michael47" },
            { code: "48", lastName: "Linke", firstName: "Severin", amount: 0, password: "severin48" },
            { code: "49", lastName: "Loth", firstName: "Vincent", amount: 80, password: "vincent49" },
            { code: "50", lastName: "Mäder", firstName: "Hannah Victoria", amount: 80, password: "hannah50" },
            { code: "51", lastName: "Mäder", firstName: "Jette Charlotte", amount: 80, password: "jette51" },
            { code: "52", lastName: "Menebröcker", firstName: "Niklas", amount: 0, password: "niklas52" },
            { code: "53", lastName: "Mogk", firstName: "Melissa", amount: 0, password: "melissa53" },
            { code: "54", lastName: "Mogk", firstName: "Seraphina", amount: 0, password: "seraphina54" },
            { code: "55", lastName: "Müller", firstName: "Emilia Helena", amount: 0, password: "emilia55" },
            { code: "56", lastName: "Müller", firstName: "Phill", amount: 80, password: "phill56" },
            { code: "57", lastName: "Nover", firstName: "Adele Paula", amount: 0, password: "adele57" },
            { code: "58", lastName: "Nunziante", firstName: "Celina Melane", amount: 0, password: "celina58" },
            { code: "59", lastName: "Olerich", firstName: "Lasse", amount: 25, password: "lasse59" },
            { code: "60", lastName: "Ortlieb", firstName: "Klara", amount: 80, password: "klara60" },
            { code: "61", lastName: "Otman", firstName: "Tom", amount: 80, password: "tom61" },
            { code: "62", lastName: "Pohl", firstName: "Antonia", amount: 0, password: "antonia62" },
            { code: "63", lastName: "Quinke", firstName: "Felix", amount: 80, password: "felix63" },
            { code: "64", lastName: "Rabanus", firstName: "Josia Niklas", amount: 0, password: "josia64" },
            { code: "65", lastName: "Raffelsieper", firstName: "Nika", amount: 0, password: "nika65" },
            { code: "66", lastName: "Rempel", firstName: "Eve Melina", amount: 0, password: "eve66" },
            { code: "67", lastName: "Reppel", firstName: "Leon", amount: 5, password: "leon67" },
            { code: "68", lastName: "Schieren", firstName: "Anna", amount: 40, password: "anna68" },
            { code: "69", lastName: "Schmalt", firstName: "Florian Michael", amount: 0, password: "florian69" },
            { code: "70", lastName: "Schmidt", firstName: "Heidi Mo", amount: 80, password: "heidi70" },
            { code: "71", lastName: "Schmidt", firstName: "Lennart", amount: 80, password: "lennart71" },
            { code: "72", lastName: "Schmidt", firstName: "Luis", amount: 80, password: "luis72" },
            { code: "73", lastName: "Schmitz", firstName: "Luca Elias", amount: 0, password: "luca73" },
            { code: "74", lastName: "Schmitz", firstName: "Paul Guido", amount: 80, password: "paul74" },
            { code: "75", lastName: "Schnabel", firstName: "Silas", amount: 0, password: "silas75" },
            { code: "76", lastName: "Schreiber", firstName: "Maja", amount: 0, password: "maja76" },
            { code: "77", lastName: "Schwarzer", firstName: "Jule", amount: 0, password: "jule77" },
            { code: "78", lastName: "Seifert", firstName: "Mia", amount: 0, password: "mia78" },
            { code: "79", lastName: "Sippach", firstName: "Julius", amount: 80, password: "julius79" },
            { code: "80", lastName: "Sommerberg", firstName: "Klara Maria", amount: 80, password: "klara80" },
            { code: "81", lastName: "Standfuß", firstName: "Luca Marie", amount: 80, password: "luca81" },
            { code: "82", lastName: "Tews", firstName: "Hendrik", amount: 80, password: "hendrik82" },
            { code: "83", lastName: "Trubitz", firstName: "Celina", amount: 80, password: "celina83" },
            { code: "84", lastName: "Tsakiroglou", firstName: "Anna", amount: 80, password: "anna84" },
            { code: "85", lastName: "Ulhaas", firstName: "Sebastian", amount: 80, password: "sebastian85" },
            { code: "86", lastName: "Urbatzka", firstName: "Rut Maria", amount: 0, password: "rut86" },
            { code: "87", lastName: "von der Neyen", firstName: "Jonas", amount: 0, password: "jonas87" },
            { code: "88", lastName: "Warmbier", firstName: "Nico", amount: 0, password: "nico88" },
            { code: "89", lastName: "Weber", firstName: "Hannah", amount: 80, password: "hannah89" },
            { code: "90", lastName: "Wencker", firstName: "Nico", amount: 0, password: "nico90" },
            { code: "91", lastName: "Wienand", firstName: "Josefine", amount: 80, password: "josefine91" },
            { code: "92", lastName: "Winterhager", firstName: "Nele Anna Marie", amount: 0, password: "nele92" },
            { code: "93", lastName: "Winterhoff", firstName: "Moritz", amount: 80, password: "moritz93" },
            { code: "94", lastName: "Wolf", firstName: "Leonie Marie", amount: 0, password: "leonie94" },
            { code: "95", lastName: "Zimmermann", firstName: "Hannes", amount: 80, password: "hannes95" },
            { code: "96", lastName: "Zimmermann", firstName: "Tobias", amount: 80, password: "tobias96" }
        ];
        
        // Daten aus localStorage laden falls vorhanden
        function loadFromLocalStorage() {
            const savedData = localStorage.getItem('schuelerDatenMitLoginPasswort');
            if (savedData) {
                try {
                    schuelerDaten = JSON.parse(savedData);
                    console.log("📁 Daten aus LocalStorage geladen");
                } catch (e) {
                    console.log("📁 Keine gespeicherten Daten gefunden, verwende Standard");
                }
            }
        }
        
        // Daten in localStorage speichern
        function saveToLocalStorage() {
            localStorage.setItem('schuelerDatenMitLoginPasswort', JSON.stringify(schuelerDaten));
            console.log("💾 Daten gespeichert");
        }
        
        // DOM-Elemente
        const loginCard = document.getElementById('loginCard');
        const resultCard = document.getElementById('resultCard');
        const adminLoginCard = document.getElementById('adminLoginCard');
        const adminCard = document.getElementById('adminCard');
        const codeInput = document.getElementById('code');
        const adminPasswordInput = document.getElementById('adminPassword');
        const betraegeInput = document.getElementById('betraegeInput');
        const passwoerterInput = document.getElementById('passwoerterInput');
        const loginBtn = document.getElementById('loginBtn');
        const logoutBtn = document.getElementById('logoutBtn');
        const adminAccessBtn = document.getElementById('adminAccessBtn');
        const adminLoginBtn = document.getElementById('adminLoginBtn');
        const backToMainBtn = document.getElementById('backToMainBtn');
        const adminLogoutBtn = document.getElementById('adminLogoutBtn');
        const updateBetraegeBtn = document.getElementById('updateBetraegeBtn');
        const updatePasswoerterBtn = document.getElementById('updatePasswoerterBtn');
        const showPasswoerterBtn = document.getElementById('showPasswoerterBtn');
        const showBetraegeExampleBtn = document.getElementById('showBetraegeExampleBtn');
        const refreshOverviewBtn = document.getElementById('refreshOverviewBtn');
        const exportDataBtn = document.getElementById('exportDataBtn');
        const errorMessage = document.getElementById('errorMessage');
        const adminLoginError = document.getElementById('adminLoginError');
        const betraegeSuccess = document.getElementById('betraegeSuccess');
        const betraegeError = document.getElementById('betraegeError');
        const passwoerterSuccess = document.getElementById('passwoerterSuccess');
        const passwoerterError = document.getElementById('passwoerterError');
        const personName = document.getElementById('personName');
        const personFullName = document.getElementById('personFullName');
        const firstName = document.getElementById('firstName');
        const lastName = document.getElementById('lastName');
        const userPassword = document.getElementById('userPassword');
        const statusDisplay = document.getElementById('statusDisplay');
        const amountDisplay = document.getElementById('amountDisplay');
        const overviewTableBody = document.getElementById('overviewTableBody');
        const tabButtons = document.querySelectorAll('.tab-btn');
        const tabContents = document.querySelectorAll('.tab-content');
        
        // Login-Funktion für Schüler (JETZT NUR MIT PASSWORT!)
        function login() {
            const password = codeInput.value.trim();
            
            if (!password) {
                showMessage("Bitte geben Sie Ihr Passwort ein.", "error", errorMessage);
                return;
            }
            
            // Schüler anhand des Passworts finden
            const schueler = schuelerDaten.find(s => s.password === password);
            
            if (schueler) {
                // Alle Felder aktualisieren
                personName.textContent = schueler.firstName;
                personFullName.textContent = `${schueler.firstName} ${schueler.lastName}`;
                firstName.textContent = schueler.firstName;
                lastName.textContent = schueler.lastName;
                userPassword.textContent = password;
                amountDisplay.textContent = `${schueler.amount.toFixed(2)} €`;
                
                // Status anzeigen
                if (schueler.amount === 0) {
                    statusDisplay.textContent = "✅ Alles bezahlt";
                    statusDisplay.style.color = "#27ae60";
                } else if (schueler.amount > 0) {
                    statusDisplay.textContent = `⏳ Noch ${schueler.amount.toFixed(2)} € offen`;
                    statusDisplay.style.color = "#e74c3c";
                } else {
                    statusDisplay.textContent = `💰 Guthaben von ${Math.abs(schueler.amount).toFixed(2)} €`;
                    statusDisplay.style.color = "#3498db";
                }
                
                // Farbliche Hervorhebung basierend auf Betrag
                if (schueler.amount === 0) {
                    amountDisplay.style.color = "#27ae60";
                } else if (schueler.amount > 100) {
                    amountDisplay.style.color = "#e74c3c";
                } else {
                    amountDisplay.style.color = "#2575fc";
                }
                
                // Karten wechseln
                loginCard.style.display = 'none';
                resultCard.style.display = 'flex';
                errorMessage.style.display = 'none';
                
                codeInput.value = '';
                
                console.log(`🔓 Login erfolgreich: Passwort ${password} - ${schueler.firstName} ${schueler.lastName}`);
            } else {
                showMessage(`Ungültiges Passwort.`, "error", errorMessage);
                codeInput.focus();
            }
        }
        
        // Admin-Login
        function adminLogin() {
            const passwort = adminPasswordInput.value.trim();
            
            if (passwort === ADMIN_PASSWORT) {
                adminLoginCard.style.display = 'none';
                adminCard.style.display = 'flex';
                adminLoginError.style.display = 'none';
                adminPasswordInput.value = '';
                
                // Datenübersicht aktualisieren
                updateOverview();
                
                console.log("🔓 Admin-Login erfolgreich");
            } else {
                adminLoginError.style.display = 'block';
                adminPasswordInput.focus();
            }
        }
        
        // Beträge aktualisieren
        function updateBetraege() {
            const inputText = betraegeInput.value.trim();
            
            if (!inputText) {
                showMessage("Bitte füge zuerst die Beträge ein.", "error", betraegeError);
                betraegeInput.focus();
                return;
            }
            
            // Text in Zeilen aufteilen
            const zeilen = inputText.split('\n').filter(zeile => zeile.trim() !== '');
            
            // Zahlen extrahieren
            const neueBetraege = [];
            
            for (let zeile of zeilen) {
                const zahl = zeile.replace(/[^\d.,]/g, '').replace(',', '.');
                const betrag = parseFloat(zahl);
                
                if (!isNaN(betrag)) {
                    neueBetraege.push(betrag);
                }
            }
            
            // Überprüfen
            if (neueBetraege.length !== schuelerDaten.length) {
                showMessage(
                    `Achtung: ${neueBetraege.length} Werte gefunden, aber ${schuelerDaten.length} erwartet.`, 
                    "error", 
                    betraegeError
                );
            }
            
            // Beträge aktualisieren
            for (let i = 0; i < Math.min(schuelerDaten.length, neueBetraege.length); i++) {
                schuelerDaten[i].amount = neueBetraege[i];
            }
            
            // Erfolgsmeldung
            const aktualisiert = Math.min(schuelerDaten.length, neueBetraege.length);
            showMessage(
                `✅ ${aktualisiert} Beträge erfolgreich aktualisiert!`, 
                "success", 
                betraegeSuccess
            );
            
            // Speichern und aktualisieren
            saveToLocalStorage();
            updateOverview();
            
            // Eingabefeld leeren
            betraegeInput.value = '';
            
            console.log(`🔄 ${aktualisiert} Beträge aktualisiert`);
        }
        
        // Passwörter aktualisieren
        function updatePasswoerter() {
            const inputText = passwoerterInput.value.trim();
            
            if (!inputText) {
                showMessage("Bitte füge zuerst die Passwörter ein.", "error", passwoerterError);
                passwoerterInput.focus();
                return;
            }
            
            // Text in Zeilen aufteilen
            const zeilen = inputText.split('\n').filter(zeile => zeile.trim() !== '');
            
            // Überprüfen
            if (zeilen.length !== schuelerDaten.length) {
                showMessage(
                    `Achtung: ${zeilen.length} Passwörter gefunden, aber ${schuelerDaten.length} erwartet.`, 
                    "error", 
                    passwoerterError
                );
            }
            
            // Passwörter aktualisieren
            for (let i = 0; i < Math.min(schuelerDaten.length, zeilen.length); i++) {
                schuelerDaten[i].password = zeilen[i].trim();
            }
            
            // Erfolgsmeldung
            const aktualisiert = Math.min(schuelerDaten.length, zeilen.length);
            showMessage(
                `✅ ${aktualisiert} Passwörter erfolgreich aktualisiert!`, 
                "success", 
                passwoerterSuccess
            );
            
            // Speichern und aktualisieren
            saveToLocalStorage();
            updateOverview();
            
            // Eingabefeld leeren
            passwoerterInput.value = '';
            
            console.log(`🔑 ${aktualisiert} Passwörter aktualisiert`);
        }
        
        // Aktuelle Passwörter anzeigen
        function showCurrentPasswords() {
            const passwoerter = schuelerDaten.map(s => s.password);
            passwoerterInput.value = passwoerter.join('\n');
            
            showMessage(
                `👁️ ${schuelerDaten.length} aktuelle Passwörter angezeigt`, 
                "success", 
                passwoerterSuccess
            );
        }
        
        // Beträge-Beispiel anzeigen
        function showBetraegeExample() {
            const betraege = schuelerDaten.map(s => s.amount);
            betraegeInput.value = betraege.join('\n');
            
            showMessage(
                `📋 ${schuelerDaten.length} aktuelle Beträge angezeigt`, 
                "success", 
                betraegeSuccess
            );
        }
        
        // Datenübersicht aktualisieren
        function updateOverview() {
            overviewTableBody.innerHTML = '';
            
            schuelerDaten.forEach(schueler => {
                const row = document.createElement('tr');
                
                // Status bestimmen
                let status = '';
                let statusColor = '';
                let statusIcon = '';
                if (schueler.amount === 0) {
                    status = 'Bezahlt';
                    statusColor = '#27ae60';
                    statusIcon = '✅';
                } else if (schueler.amount > 0) {
                    status = 'Offen';
                    statusColor = '#e74c3c';
                    statusIcon = '⏳';
                } else {
                    status = 'Guthaben';
                    statusColor = '#3498db';
                    statusIcon = '💰';
                }
                
                row.innerHTML = `
                    <td><strong>${schueler.code}</strong></td>
                    <td>${schueler.lastName}</td>
                    <td>${schueler.firstName}</td>
                    <td style="font-weight: bold; color: ${schueler.amount > 0 ? '#e74c3c' : schueler.amount === 0 ? '#27ae60' : '#3498db'}">
                        ${schueler.amount.toFixed(2)} €
                    </td>
                    <td style="color: ${statusColor}">${statusIcon} ${status}</td>
                    <td>${schueler.password}</td>
                `;
                overviewTableBody.appendChild(row);
            });
        }
        
        // Alle Daten exportieren
        function exportAllData() {
            const exportData = schuelerDaten.map(s => ({
                Code: s.code,
                Nachname: s.lastName,
                Vorname: s.firstName,
                Betrag: s.amount,
                Login_Passwort: s.password
            }));
            
            // CSV-Format erstellen
            let csv = 'Code,Nachname,Vorname,Betrag,Login_Passwort\n';
            exportData.forEach(row => {
                csv += `"${row.Code}","${row.Nachname}","${row.Vorname}",${row.Betrag},"${row.Login_Passwort}"\n`;
            });
            
            // Download
            const blob = new Blob([csv], { type: 'text/csv;charset=utf-8;' });
            const url = URL.createObjectURL(blob);
            const a = document.createElement('a');
            a.href = url;
            a.download = `schueler-daten-${new Date().toISOString().split('T')[0]}.csv`;
            a.click();
            URL.revokeObjectURL(url);
            
            console.log("📥 Alle Daten exportiert");
        }
        
        // Tab-Wechsel
        function setupTabs() {
            tabButtons.forEach(button => {
                button.addEventListener('click', () => {
                    const tabId = button.getAttribute('data-tab');
                    
                    // Aktiven Tab zurücksetzen
                    tabButtons.forEach(btn => btn.classList.remove('active'));
                    tabContents.forEach(content => content.classList.remove('active'));
                    
                    // Neuen Tab aktivieren
                    button.classList.add('active');
                    document.getElementById(`tab-${tabId}`).classList.add('active');
                    
                    // Bei Datenübersicht aktualisieren
                    if (tabId === 'uebersicht') {
                        updateOverview();
                    }
                });
            });
        }
        
        // Admin-Bereich anzeigen
        function showAdminLogin() {
            loginCard.style.display = 'none';
            adminLoginCard.style.display = 'flex';
            adminPasswordInput.focus();
        }
        
        // Zurück zur Hauptseite
        function backToMain() {
            loginCard.style.display = 'flex';
            resultCard.style.display = 'none';
            adminLoginCard.style.display = 'none';
            adminCard.style.display = 'none';
            codeInput.value = '';
            adminPasswordInput.value = '';
            betraegeInput.value = '';
            passwoerterInput.value = '';
            errorMessage.style.display = 'none';
            adminLoginError.style.display = 'none';
            betraegeSuccess.style.display = 'none';
            betraegeError.style.display = 'none';
            passwoerterSuccess.style.display = 'none';
            passwoerterError.style.display = 'none';
            codeInput.focus();
        }
        
        // Nachricht anzeigen
        function showMessage(message, type, element) {
            element.textContent = message;
            element.style.display = 'block';
            
            if (type === "error") {
                element.style.color = "#e74c3c";
            } else {
                element.style.color = "#27ae60";
            }
            
            setTimeout(() => {
                element.style.display = 'none';
            }, 5000);
        }
        
        // Event Listener
        loginBtn.addEventListener('click', login);
        logoutBtn.addEventListener('click', backToMain);
        adminAccessBtn.addEventListener('click', showAdminLogin);
        adminLoginBtn.addEventListener('click', adminLogin);
        backToMainBtn.addEventListener('click', backToMain);
        adminLogoutBtn.addEventListener('click', backToMain);
        updateBetraegeBtn.addEventListener('click', updateBetraege);
        updatePasswoerterBtn.addEventListener('click', updatePasswoerter);
        showPasswoerterBtn.addEventListener('click', showCurrentPasswords);
        showBetraegeExampleBtn.addEventListener('click', showBetraegeExample);
        refreshOverviewBtn.addEventListener('click', updateOverview);
        exportDataBtn.addEventListener('click', exportAllData);
        
        // Enter-Taste zum Einloggen verwenden
        codeInput.addEventListener('keypress', function(event) {
            if (event.key === 'Enter') {
                login();
            }
        });
        
        adminPasswordInput.addEventListener('keypress', function(event) {
            if (event.key === 'Enter') {
                adminLogin();
            }
        });
        
        // Beim Laden der Seite
        window.addEventListener('DOMContentLoaded', function() {
            console.log("🚀 Website wird geladen...");
            console.log("📊 Schülerdaten: 96 Einträge geladen");
            console.log("🔐 Admin-Passwort: 1578");
            console.log("👤 Schüler login: Jetzt nur mit persönlichem Passwort!");
            
            // Daten laden
            loadFromLocalStorage();
            
            // Tabs einrichten
            setupTabs();
            
            // Fokus auf Eingabefeld setzen
            codeInput.focus();
        });
    </script>
</body>
</html>
message.txt
46 kB
