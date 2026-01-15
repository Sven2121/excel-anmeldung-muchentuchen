# excel-anmeldung-muchentuchen
Anmeldeformular für Lehrgang Excelschulung Marco Maurer
[anmeldung.html](https://github.com/user-attachments/files/24642459/anmeldung.html)
<div style="text-align:center; margin-bottom:20px;">
    <!-- Logo -->
    <!-- SVG hier einfügen -->
</div>
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <title>Muchentuchen’s Excel Kurs – Studienanmeldung</title>
    <style>
        body {
            font-family: "Segoe UI", Arial, sans-serif;
            background: linear-gradient(135deg, #f2f6fb, #e3ecf7);
            margin: 0;
            padding: 40px;
        }

        .container {
            max-width: 900px;
            margin: auto;
            background: #ffffff;
            padding: 40px;
            border-radius: 12px;
            box-shadow: 0 15px 40px rgba(0, 0, 0, 0.1);
        }

        h1 {
            text-align: center;
            color: #1f3c88;
            margin-bottom: 10px;
        }

        h2 {
            text-align: center;
            color: #444;
            font-weight: normal;
            margin-bottom: 30px;
        }

        .info-box {
            background: #f0f5ff;
            border-left: 5px solid #1f3c88;
            padding: 15px 20px;
            margin-bottom: 30px;
            border-radius: 6px;
        }

        .info-box strong {
            color: #1f3c88;
        }

        form {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
        }

        label {
            font-weight: 600;
            color: #333;
        }

        input, select, textarea {
            width: 100%;
            padding: 12px;
            border-radius: 6px;
            border: 1px solid #ccc;
            font-size: 15px;
        }

        textarea {
            resize: vertical;
            min-height: 100px;
        }

        .full-width {
            grid-column: 1 / 3;
        }

        .submit-btn {
            background: #1f3c88;
            color: white;
            border: none;
            padding: 15px;
            font-size: 16px;
            font-weight: bold;
            border-radius: 8px;
            cursor: pointer;
            transition: background 0.3s;
        }

        .submit-btn:hover {
            background: #162d66;
        }

        .footer {
            text-align: center;
            margin-top: 30px;
            font-size: 13px;
            color: #777;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>Muchentuchen’s Excel Kurs</h1>
    <h2>Studienanmeldung</h2>

    <div class="info-box">
        <p><strong>Studiengang:</strong> Excel-Listen von Marco Maurer verstehen</p>
        <p><strong>Studienstart:</strong> 15.01.2026</p>
        <p><strong>Abschluss:</strong> Zertifikat „Excel-Analyse & Praxisverständnis“</p>
    </div>

    <form>
        <div>
            <label>Vorname</label>
            <input type="text" placeholder="Max" required>
        </div>

        <div>
            <label>Nachname</label>
            <input type="text" placeholder="Mustermann" required>
        </div>

        <div>
            <label>E-Mail-Adresse</label>
            <input type="email" placeholder="max.mustermann@email.de" required>
        </div>

        <div>
            <label>Telefonnummer</label>
            <input type="tel" placeholder="+49 170 1234567">
        </div>

        <div>
            <label>Geburtsdatum</label>
            <input type="date" required>
        </div>

        <div>
            <label>Gewünschte Teilnahmeform</label>
            <select required>
                <option value="">Bitte auswählen</option>
                <option>Präsenzunterricht</option>
                <option>Online (Live)</option>
                <option>Hybrid (Präsenz & Online)</option>
            </select>
        </div>

        <div>
            <label>Bevorzugter Teilnahmezeitraum</label>
            <select required>
                <option value="">Bitte auswählen</option>
                <option>Vormittags (09:00 – 12:00)</option>
                <option>Nachmittags (13:00 – 16:00)</option>
                <option>Abends (18:00 – 21:00)</option>
            </select>
        </div>

        <div>
            <label>Vorkenntnisse in Excel</label>
            <select>
                <option>Keine</option>
                <option>Grundkenntnisse</option>
                <option>Fortgeschritten</option>
            </select>
        </div>

        <div class="full-width">
            <label>Motivation / Erwartung an den Studiengang</label>
            <textarea placeholder="Warum möchten Sie Excel-Listen von Marco Maurer verstehen?"></textarea>
        </div>

        <div class="full-width">
            <button class="submit-btn" type="submit">
                Verbindlich zum Studiengang anmelden
            </button>
        </div>
    </form>

    <div class="footer">
        © 2026 Muchentuchen’s Excel Kurs · Akademische Weiterbildung
    </div>
</div>

</body>
</html>
