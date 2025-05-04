# TVH
Website
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>The Village Helper</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f9f9f9; }
    header { background: #2b2b2b; color: white; padding: 20px; text-align: center; }
    .banner { font-size: 2em; font-weight: bold; }
    .contact { margin-top: 10px; }
    .hero {
      position: relative;
      height: 300px;
      background: url('https://images.unsplash.com/photo-1581093588401-07014f6f94a7?auto=format&fit=crop&w=1950&q=80') center/cover no-repeat;
      color: white;
      display: flex;
      justify-content: center;
      align-items: center;
      font-size: 5em;
      font-weight: bold;
      text-shadow: 2px 2px 8px rgba(0,0,0,0.8);
    }
    .section { padding: 40px 20px; }
    .services, .reviews, .scheduling, .pricing, .coverage { background: white; margin: 20px 0; padding: 20px; border-radius: 10px; animation: fadeIn 1.5s ease-in; }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
    .flip-text {
      font-size: 2em;
      text-align: center;
      height: 2em;
      overflow: hidden;
      position: relative;
    }
    .flip-text span {
      position: absolute;
      width: 100%;
      animation: flipWords 6s infinite;
    }
    @keyframes flipWords {
      0% { transform: translateY(0%); }
      33% { transform: translateY(-100%); }
      66% { transform: translateY(-200%); }
      100% { transform: translateY(-300%); }
    }
    .flip-text span:nth-child(1) { top: 0%; }
    .flip-text span:nth-child(2) { top: 100%; }
    .flip-text span:nth-child(3) { top: 200%; }.footer { text-align: center; padding: 20px; background: #2b2b2b; color: white; }

  </style>
</head>
<body>
  <header>
    <div class="banner">Village Helper</div>
    <div class="contact">Call us: 317-612-4322 | Email: tvhwedoitall@gmail.com</div>
  </header>  <div class="hero">
    TVH
  </div>  <div class="section flip-text">
    <span>Electrical</span>
    <span>Plumbing</span>
    <span>Appliance Repair</span>
  </div>  <div class="section services">
    <h2>What We Do</h2>
    <ul>
      <li>Electrical</li>
      <li>Plumbing</li>
      <li>Appliance Repair</li>
      <li>Irrigation</li>
      <li>And More...</li>
    </ul>
  </div>  <div class="section pricing">
    <h2>Service Calls & Pricing</h2>
    <h3>Electrical & Plumbing</h3>
    <p>$125 service call. If we proceed with the work, this fee may be absorbed into the total bill if the job meets or beats the cost of the arrival.</p><h3>Appliances</h3>
<p>$75 service call, $75/hour labor (parts additional).</p>

  </div>  <div class="section reviews">
    <h2>Customer Reviews (70+)</h2>
    <p>"The Village Helper fixed our kitchen wiring quickly and professionally. Highly recommend!"</p>
    <p>"Great service! Repaired our fridge fast and saved us a ton of money."</p>
    <p>"Reliable, affordable, and friendly. They are our go-to for home repairs."</p>
  </div>  <div class="section scheduling">
    <h2>Schedule a Service</h2>
    <form>
      <label for="name">Your Name:</label><br />
      <input type="text" id="name" name="name" required><br /><br /><label for="email">Email:</label><br />
  <input type="email" id="email" name="email" required><br /><br />

  <label for="service">Select Service:</label><br />
  <select id="service" name="service">
    <option>Electrical</option>
    <option>Plumbing</option>
    <option>Appliance Repair</option>
    <option>Irrigation</option>
    <option>Other</option>
  </select><br /><br />

  <label for="message">Describe the issue:</label><br />
  <textarea id="message" name="message" rows="4" cols="50"></textarea><br /><br />

  <input type="submit" value="Submit Request">
</form>

  </div>  <div class="section coverage">
    <h2>Coverage Areas</h2>
    <p>We proudly serve Sumter County, Lake County, Marion County, Orange County, and surrounding areas.</p>
  </div>  <div class="footer">
    &copy; 2025 The Village Helper. All rights reserved.
  </div>
</body>
</html>
