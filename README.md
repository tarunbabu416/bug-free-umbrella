# bug-free-umbrella
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>TRB HOTEL</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      min-height: 100vh;
      margin: 0;
      font-family: 'Segoe UI', Arial, sans-serif;
      color: #fff;
      background: linear-gradient(135deg, #2e3192 0%, #1bffff 100%);
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
    }
    .container {
      background: rgba(0,0,0,0.5);
      padding: 2rem 2.5rem;
      border-radius: 1.2rem;
      box-shadow: 0 0 20px rgba(44,160,202,0.3);
      text-align: center;
      max-width: 400px;
      margin-top: 40px;
    }
    h1 {
      font-size: 2.8rem;
      margin-bottom: 0.4em;
      letter-spacing: 1px;
      font-weight: bold;
    }
    .info {
      font-size: 1.2rem;
      margin-bottom: 1.6em;
    }
    .phone {
      font-size: 1.1rem;
      background: #1bffff;
      color: #222;
      border-radius: 9px;
      padding: 0.6em 1.2em;
      display: inline-block;
      margin-top: 0.7em;
      box-shadow: 0 2px 8px rgba(44,160,202,0.15);
    }
    .btn {
      display: inline-block;
      padding: 0.7em 1.7em;
      font-size: 1.15rem;
      color: #fff;
      background: #2e3192;
      border: none;
      border-radius: 9px;
      cursor: pointer;
      transition: background 0.22s;
      margin-top: 1.5em;
      font-weight: 500;
      letter-spacing: 0.5px;
      box-shadow: 0 2px 8px rgba(44,160,202,0.22);
    }
    .btn:hover {
      background: #13227b;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>TRB HOTEL</h1>
    <div class="info">
      <strong>Address:</strong> 123 Blue Ridge Avenue, Ooty, Tamil Nadu, 643001<br>
      <strong>Email:</strong> info@trbhotel.com
    </div>
    <div class="phone">
      <strong>Phone:</strong> +91 1223445667
    </div>
    <button class="btn" onclick="alert('Thank you for choosing TRB HOTEL! For reservations, call us or email info@trbhotel.com')">
      Book Now
    </button>
  </div>
</body>
</html>
