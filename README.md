<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sideline Lens Photography</title>
<link rel="stylesheet" href="style.css">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Oswald:wght@500;600;700&family=Inter:wght@400;500;600&display=swap" rel="stylesheet">
</head>
<body>

<nav>
  <div class="wrap">
    <a href="#" class="logo">
      <svg viewBox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg">
        <circle cx="20" cy="20" r="18" stroke="#F4A300" stroke-width="2.5"/>
        <path d="M20 8 L25 15 L22 24 L18 24 L15 15 Z" fill="#F4A300"/>
      </svg>
      Sideline Lens
    </a>
    <ul>
      <li><a href="#gallery">Gallery</a></li>
      <li><a href="#packages">Packages</a></li>
      <li><a href="#book">Book</a></li>
    </ul>
  </div>
</nav>

<header class="hero">
  <div class="wrap">
    <div class="eyebrow">Youth &amp; High School Soccer Photography</div>
    <h1>Every sprint,<br><span>every save,</span><br>captured.</h1>
    <p class="sub">Action shots your player will actually want to keep. Sideline coverage for games and tournaments, delivered fast.</p>
    <a href="#book" class="btn">Book a Shoot</a>
  </div>
</header>

<section id="gallery">
  <div class="wrap">
    <div class="halfway"><div class="line"></div><span class="label">Gallery</span><div class="dot"></div><div class="line"></div></div>
    <div class="gallery-grid">
      <figure>Photo coming soon</figure>
      <figure>Photo coming soon</figure>
      <figure>Photo coming soon</figure>
      <figure>Photo coming soon</figure>
      <figure>Photo coming soon</figure>
      <figure>Photo coming soon</figure>
    </div>
  </div>
</section>

<section id="packages" class="alt">
  <div class="wrap">
    <div class="halfway"><div class="line"></div><span class="label">Packages</span><div class="dot"></div><div class="line"></div></div>
    <div class="packages">
      <div class="ticket">
        <h3>Single Match</h3>
        <div class="price">$45</div>
        <ul>
          <li>One full game covered</li>
          <li>25+ edited digital photos</li>
          <li>Delivered within 3 days</li>
          <li>Private online gallery</li>
        </ul>
      </div>
      <div class="ticket featured">
        <span class="tag">Most Popular</span>
        <h3>Season Pass</h3>
        <div class="price">$150</div>
        <ul>
          <li>4 games of coverage</li>
          <li>120+ edited digital photos</li>
          <li>Delivered within 3 days each</li>
          <li>1 printed 8x10 included</li>
        </ul>
      </div>
      <div class="ticket">
        <h3>Team Package</h3>
        <div class="price">$25<sup>/player</sup></div>
        <ul>
          <li>Full team, one game</li>
          <li>Individual + group shots</li>
          <li>Digital gallery per player</li>
          <li>Ask about bulk pricing</li>
        </ul>
      </div>
    </div>
  </div>
</section>

<section id="book">
  <div class="wrap">
    <div class="booking-box">
      <h2>Request a Booking</h2>
      <p class="lead">Send your game details and I'll reply to confirm within a day.</p>
      <form id="booking-form">
        <div class="row-2">
          <div class="field">
            <label for="date">Date</label>
            <input type="date" id="date" name="date" required>
          </div>
          <div class="field">
            <label for="time">Time</label>
            <input type="time" id="time" name="time" required>
          </div>
        </div>
        <div class="field">
          <label for="players">Number of Players</label>
          <input type="number" id="players" name="players" min="1" required>
        </div>
        <div class="field">
          <label for="package">Package</label>
          <select id="package" name="package">
            <option>Single Match — $45</option>
            <option>Season Pass — $150</option>
            <option>Team Package — $25/player</option>
            <option>Not sure yet</option>
          </select>
        </div>
        <div class="field">
          <label for="name">Your Name</label>
          <input type="text" id="name" name="name" required>
        </div>
        <div class="field">
          <label for="email">Email Address</label>
          <input type="email" id="email" name="email" required>
        </div>
        <div class="field">
          <label for="notes">Notes (location, team name, etc.)</label>
          <textarea id="notes" name="notes" rows="3"></textarea>
        </div>
        <button type="submit" class="btn">Send Request</button>
        <div id="form-status"></div>
      </form>
    </div>
  </div>
</section>

<footer>
  <div class="wrap">Sideline Lens Photography — booking requests are reviewed and confirmed by email.</div>
</footer>

<script src="script.js"></script>
</body>
</html>
