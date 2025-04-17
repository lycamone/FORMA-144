<!DOCTYPE html>
<html lang="hr">
<head>
  <meta charset="UTF-8">
  <title>FCA – Interna forma R-144</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f6f9;
      margin: 0;
      padding: 0;
    }
    .header {
      background-color: #002d72;
      color: white;
      padding: 20px;
      text-align: center;
    }
    .form-container {
      background: white;
      max-width: 700px;
      margin: 40px auto;
      padding: 30px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      border-radius: 10px;
    }
    h1, h2 {
      color: #002d72;
    }
    label {
      display: block;
      margin-top: 20px;
      font-weight: bold;
    }
    input[type="text"], input[type="email"], textarea {
      width: 100%;
      padding: 10px;
      margin-top: 8px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    textarea {
      height: 100px;
      resize: vertical;
    }
    .footer {
      text-align: center;
      font-size: 12px;
      color: #777;
      margin-top: 40px;
    }
    .submit-btn {
      background-color: #002d72;
      color: white;
      padding: 12px 20px;
      border: none;
      border-radius: 5px;
      margin-top: 30px;
      cursor: pointer;
    }
    .submit-btn:hover {
      background-color: #0046aa;
    }
  </style>
</head>
<body>
  <div class="header">
    <h1>Financial Conduct Authority (FCA)</h1>
    <p>Internal Monitoring & Tracing Unit</p>
  </div>

  <div class="form-container">
    <h2>Forma R-144 — Privremena Rezerva Sredstava</h2>
    <p><strong>Ime klijenta:</strong> Nenad Nikolić</p>
    <p><strong>Referenca sistema:</strong> 2025-R144-11678</p>
    <p><strong>Status:</strong> Privremena rezerva – čekanje potvrde zakonitosti</p>
    
    <label for="purpose">Svrha transfera:</label>
    <input type="text" id="purpose" name="purpose" placeholder="Unesite svrhu izvornih uplata...">

    <label for="source">Izvor sredstava:</label>
    <input type="text" id="source" name="source" placeholder="Na primer: lična ušteđevina, prodaja imovine...">

    <label for="receiver">Osoba koja je primila sredstva:</label>
    <input type="text" id="receiver" name="receiver" placeholder="Ime osobe ili kompanije...">

    <label for="comments">Dodatni komentari (opciono):</label>
    <textarea id="comments" name="comments" placeholder="Ovde možete opisati sve relevantne detalje..."></textarea>

    <button class="submit-btn">Pošalji dokumentaciju</button>
  </div>

  <div class="footer">
    FCA © 2025 – Odeljenje za internu procenu i praćenje finansijskih tokova. <br>
    Ova forma je deo procesa 8b–EU/FSR podregulativa 24-A.
  </div>
</body>
</html>
