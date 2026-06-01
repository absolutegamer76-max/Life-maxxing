# Life-maxxing
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Life Maxxing - Level Up Your Life</title>
  <style>
    body { 
      font-family: Arial, sans-serif; 
      margin: 0; 
      background: #0a0a0a; 
      color: #fff; 
      text-align: center; 
      line-height: 1.5;
    }
    .container { max-width: 800px; margin: 0 auto; padding: 20px; }
    h1 { font-size: 2.8em; margin: 20px 0 8px; color: #00ff88; }
    .price { font-size: 2.8em; color: #00ff88; margin: 15px 0; font-weight: bold; }
    .qr { 
      max-width: 300px; 
      margin: 25px auto; 
      border: 12px solid #fff; 
      border-radius: 20px; 
      box-shadow: 0 0 25px rgba(0,255,136,0.4);
    }
    button { 
      background: #00ff88; 
      color: black; 
      padding: 16px 32px; 
      font-size: 1.4em; 
      font-weight: bold; 
      border: none; 
      border-radius: 50px; 
      cursor: pointer; 
      margin: 20px; 
      width: 90%;
      max-width: 400px;
    }
    .section { margin: 35px 0; padding: 25px; background: #1a1a1a; border-radius: 16px; }
    ul { text-align: left; display: inline-block; max-width: 520px; }
  </style>
</head>
<body>
  <div class="container">
    <h1>Life Maxxing</h1>
    <p style="font-size:1.4em;">by Shivansh Gupta</p>
    
    <div class="price">Only ₹50</div>
    
    <button onclick="window.location.href='#payment'">Buy Now - Get Instant Access</button>

    <div class="section">
      <h2>What You'll Get</h2>
      <p>A practical course designed for teenagers to build better habits, mindset, fitness, and confidence. Perfect first step to level up your life.</p>
    </div>

    <div class="section">
      <h2>Course Modules</h2>
      <ul>
        <li>✅ Mindset & Self-Confidence</li>
        <li>✅ Habit Building System</li>
        <li>✅ Productivity & Discipline</li>
        <li>✅ Fitness Fundamentals</li>
        <li>✅ Social Skills & Communication</li>
        <li>🔄 New modules added regularly</li>
      </ul>
    </div>

    <div id="payment" class="section">
      <h2>Pay ₹50 with FamPay</h2>
      <p><strong>Scan this QR code</strong></p>
      
      <!-- === PUT YOUR QR IMAGE LINK HERE === -->
      <img src="https://i.imgur.com/YOUR_QR_LINK_HERE.jpg" 
           alt="FamPay QR - 7694098107@fam" 
           class="qr">
      
      <p><strong>UPI ID:</strong> <span style="font-size:1.3em; color:#00ff88;">7694098107@fam</span></p>
      
      <p><strong>After Payment:</strong><br>
         1. Take screenshot of successful payment<br>
         2. Send it to my WhatsApp<br>
         3. Get instant access to all modules</p>
    </div>

    <button onclick="window.location.href='#payment'">Pay ₹50 Now</button>

    <footer style="margin-top:60px; padding:20px; font-size:0.9em; opacity:0.8;">
      <p>Life Maxxing © 2026 • Shivansh Gupta • First Business Launch</p>
    </footer>
  </div>
</body>
</html>
