<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Secret Santa Message</title>
  <style>
    body {
      font-family: 'Segoe UI', Arial, sans-serif;
      background: linear-gradient(135deg, #fdfbfb, #ebedee);
      padding: 40px 15px;
    }

    .message-box {
      max-width: 650px;
      margin: auto;
      background: #ffffff;
      padding: 35px;
      border-radius: 16px;
      box-shadow: 0 10px 25px rgba(0, 0, 0, 0.12);
      line-height: 1.8;
      color: #333;
      position: relative;
      overflow: hidden;
    }

    .message-box::before {
      content: "🎄";
      font-size: 120px;
      position: absolute;
      top: -30px;
      right: -30px;
      opacity: 0.08;
    }

    h1 {
      text-align: center;
      color: #c62828;
      margin-bottom: 25px;
      font-size: 26px;
      letter-spacing: 1px;
    }

    p {
      font-size: 16px;
      margin-bottom: 18px;
    }

    .highlight {
      color: #2e7d32;
      font-weight: 600;
    }

    .signature {
      margin-top: 30px;
      text-align: right;
      font-style: italic;
      font-weight: 600;
      color: #555;
    }

    .footer {
      text-align: center;
      margin-top: 25px;
      font-size: 14px;
      color: #888;
    }
  </style>
</head>
<body>

  <div class="message-box">
    <h1>Secret Santa Wishes</h1>

    <p>
      I may be your <span class="highlight">Secret Santa</span>, but in truth, you’ve been the Secret Santa in the office.
      One amazing year of friendship has passed, and I want to thank you for everything you’ve done for me.
    </p>

    <p>
      I’m giving you this <span class="highlight">infinity bracelet</span> as a small token of our bond.
      Even if one day we are not in the same place, let this bracelet be a reminder of me.
    </p>

    <p>
      Wishing you a very <span class="highlight">Merry Christmas</span> and a year filled with happiness and success! 🎁✨
    </p>

    <div class="signature">
      — Your Secret Santa 🎅
    </div>

    <div class="footer">
      Made with warmth & gratitude 💙
    </div>
  </div>

</body>
</html>
