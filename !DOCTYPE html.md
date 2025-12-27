<!DOCTYPE html>  
<html lang="en">  
<head>  
  <meta charset="UTF-8">  
  <title>ANS Suites | Book a Room</title>  
  <meta name="viewport" content="width=device-width, initial-scale=1.0">  
  
  <style>  
    body {  
      font-family: Arial, sans-serif;  
      margin: 0;  
      background-color: #f4f4f4;  
      color: #333;  
    }  
  
    header {  
      background-color: #1c1c1c;  
      color: white;  
      padding: 20px;  
      text-align: center;  
    }  
  
    .container {  
      max-width: 600px;  
      margin: 40px auto;  
      background: white;  
      padding: 30px;  
      border-radius: 8px;  
      box-shadow: 0 0 10px rgba(0,0,0,0.1);  
    }  
  
    h2 {  
      text-align: center;  
      margin-bottom: 20px;  
    }  
  
    label {  
      display: block;  
      margin-top: 15px;  
      font-weight: bold;  
    }  
  
    input {  
      width: 100%;  
      padding: 10px;  
      margin-top: 5px;  
      border-radius: 4px;  
      border: 1px solid #ccc;  
    }  
  
    .price {  
      margin-top: 20px;  
      font-size: 18px;  
      text-align: center;  
    }  
  
    button {  
      margin-top: 25px;  
      width: 100%;  
      padding: 12px;  
      background-color: #000;  
      color: white;  
      font-size: 16px;  
      border: none;  
      border-radius: 5px;  
      cursor: pointer;  
    }  
  
    button:hover {  
      background-color: #333;  
    }  
  
    .confirmation {  
      margin-top: 20px;  
      text-align: center;  
      color: green;  
      display: none;  
    }  
  
    footer {  
      text-align: center;  
      padding: 15px;  
      font-size: 14px;  
      color: #666;  
    }  
  </style>  
</head>  
  
<body>  
  
<header>  
  <h1>ANS Suites</h1>  
  <p>Comfortable. Affordable. Simple.</p>  
</header>  
  
<div class="container">  
  <h2>Book a Room</h2>  
  
  <form id="bookingForm">  
    <label>Full Name</label>  
    <input type="text" required>  
  
    <label>Email Address</label>  
    <input type="email" required>  
  
    <label>Select Date</label>  
    <input type="date" required>  
  
    <div class="price">  
      Price per day: <strong>$62.32</strong>  
    </div>  
  
    <button type="submit">Book Now</button>  
  </form>  
  
  <div class="confirmation" id="confirmation">  
    ✅ Your booking request has been submitted!  
  </div>  
</div>  
  
<footer>  
  © 2025 ANS Suites. All rights reserved.  
</footer>  
  
<script>  
  document.getElementById("bookingForm").addEventListener("submit", function(e) {  
    e.preventDefault();  
    document.getElementById("confirmation").style.display = "block";  
    this.reset();  
  });  
</script>  
  
</body>  
</html>  
