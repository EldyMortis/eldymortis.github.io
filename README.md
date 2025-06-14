<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Eldy Character Roster</title>
  <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=IM+Fell+English+SC&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
    }
    body {
      margin: 0;
      font-family: 'IM Fell English SC', serif;
      background: url('https://i.ibb.co/3ynydhh7/gridania.jpg') no-repeat center center fixed;
      background-size: cover;
      color: #2f3e2f;
      backdrop-filter: brightness(0.9);
    }
    header {
      background-color: rgba(255, 255, 255, 0.85);
      text-align: center;
      padding: 2rem;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
      border-radius: 0 0 10px 10px;
    }
    h1 {
      font-family: 'Great Vibes', cursive;
      font-size: 3rem;
      margin: 0.5rem 0;
      color: #517d6b;
    }
    .news-banner {
  background: #7e59c2;
  color: white;
  padding: 0.75rem 1rem;
  font-weight: bold;
  font-size: 1.1rem; /* <-- Add this line or increase as needed */
  overflow: hidden;
  white-space: nowrap;
  box-shadow: 0 3px 6px rgba(0,0,0,0.2);
}
    .news-scroll {
  display: inline-block;
  animation: scrollNews 80s linear infinite; /* Slowed from 20s to 60s */
}
    @keyframes scrollNews {
      0% { transform: translateX(100%); }
      100% { transform: translateX(-100%); }
    }
    .filter-controls {
      padding: 1rem;
      text-align: center;
    }
    .filter-controls button {
      margin: 0.5rem;
      padding: 0.5rem 1rem;
      border: none;
      border-radius: 6px;
      background: linear-gradient(135deg, #7e59c2, #a98ed1);
      color: white;
      cursor: pointer;
      box-shadow: 0 0 10px rgba(255,255,255,0.4);
      transition: box-shadow 0.3s ease, transform 0.2s ease;
    }
    .filter-controls button:hover {
      box-shadow: 0 0 20px rgba(255,255,255,0.7);
      transform: scale(1.05);
    }
    .character-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 2rem;
      padding: 2rem;
    }
    .card {
      background: url('https://i.ibb.co/hJGRZqbJ/Chat-GPT-Image-Jun-14-2025-08-32-34-PM.png');
      background-color: rgba(245, 243, 234, 0.95);
      border: 2px solid #c2d6b0;
      border-radius: 15px;
      box-shadow: 0 6px 12px rgba(0,0,0,0.15);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
      overflow: hidden;
    }
    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 0 15px rgba(190, 160, 255, 0.8), 0 0 25px rgba(255, 255, 255, 0.4);
      outline: 2px solid rgba(200, 180, 255, 0.7);
      outline-offset: -4px;
      animation: shimmer 1.2s infinite;
    }
    .card img {
      width: 100%;
      height: 180px;
      object-fit: cover;
      border-bottom: 1px solid #c2d6b0;
    }
    .card-content {
      padding: 1rem;
    }
    .keywords {
      font-style: italic;
      color: #6c8672;
      margin: 0.5rem 0;
    }
    .card button {
      background-color: #7e59c2;
      color: white;
      border: none;
      padding: 0.5rem 1rem;
      margin-top: 0.5rem;
      border-radius: 8px;
      cursor: pointer;
    }
  @keyframes shimmer {
      0% {
        box-shadow: 0 0 10px rgba(190, 160, 255, 0.5);
      }
      50% {
        box-shadow: 0 0 25px rgba(255, 255, 255, 0.9);
      }
      100% {
        box-shadow: 0 0 10px rgba(190, 160, 255, 0.5);
      }
    }
  </style>
</head>
<body>
  <nav style="background: rgba(60,91,78,0.95); padding: 1rem; display: flex; justify-content: center; align-items: center; gap: 2rem; position: sticky; top: 0; z-index: 1000; border-bottom: 2px solid #a3c4a8; box-shadow: 0 0 15px rgba(255,255,255,0.3);">
  <img src="whitelily.png" alt="lily icon" style="height: 24px; width: auto; filter: brightness(1.2);">
  <a href="about.html" style="color: #fffbd6; text-shadow: none; text-decoration: none; font-weight: bold; font-size: 1.1rem; transition: transform 0.3s ease;">About Me</a>
  <img src="whitelily.png" alt="lily icon" style="height: 24px; width: auto; filter: brightness(1.2);">
  <a href="#characterGrid" style="color: #fffbd6; text-shadow: 0 0 8px #ffffff, 0 0 12px #b088e5; text-decoration: none; font-weight: bold; font-size: 1.1rem; transition: transform 0.3s ease;">Character Roster</a>
  <img src="whitelily.png" alt="lily icon" style="height: 24px; width: auto; filter: brightness(1.2);">
  <a href="#mooglemail" style="color: #fffbd6; text-shadow: 0 0 8px #ffffff, 0 0 12px #b088e5; text-decoration: none; font-weight: bold; font-size: 1.1rem; transition: transform 0.3s ease;">Send a Letter</a>
</nav>
  <header>
    <h1>Eldy Character Roster</h1>
    <p>Final Fantasy XIV RP Character Roster</p>
  </header>

  <div class="news-banner">
    <div class="news-scroll">
      [14/06] Celestial Nebula is working next at Lunae's on the 20th June – [12/06] Foxglove spotted at a secret auction in Kugane – [10/06] Himari Mihata seen in deep discussion with a Doman dignitary – [09/06] Seda’a Polaali breaks up tavern brawl using dad jokes and sheer intimidation – [08/06] Liokki "Moss" Qufiswesfv observed journaling alone beneath the stars – [06/06] Felixient Merthelin charms three venues in one night – [04/06] Raih Polaali requests rare Sharlayan manuscripts on genetic healing – [30/05] Hao-Mosch seen mourning in Twine – [28/05] Kie-Hatch still getting Amh Araeng sand out of his boots – [22/05] Fir attends private meeting at Skysteel Manufactory – [18/05] Eldy Matthiola seen arguing with a conjurer over fern taxonomy – [14/05] Himari Mihata’s okiya hosts exclusive closed-door gathering
    </div>
  </div>
 

  <div style="text-align: center; margin: 2rem auto;">
    <img src="whitelily.png" alt="Section Divider" style="height: 40px; filter: brightness(1.1); transition: filter 0.3s ease-in-out;" onmouseover="this.style.filter='brightness(1.4) drop-shadow(0 0 6px white)'" onmouseout="this.style.filter='brightness(1.1)'">
  </div>
 <section class="filter-controls">
    <button onclick="filterCards('all')">Show All</button>
    <button onclick="filterCards('Healers')">Healers</button>
    <button onclick="filterCards('DPS')">DPS</button>
    <button onclick="filterCards('Tanks')">Tanks</button>
    <button onclick="filterCards('Crafter/Gatherer')">Crafters</button>
    <button onclick="filterCards('Open to RP')">Open to RP</button>
    <button onclick="filterCards('Open to Romance')">Open to Romance</button>
  </section>
  <section class="character-grid" id="characterGrid">
    <div class="card" data-tags="Gridania,Open to RP,Healers,Male">
      <img src="eldy1.png" alt="Eldy Matthiola">
      <div class="card-content">
        <h3>Eldy Matthiola</h3>
        <p><strong>Age:</strong> 26</p>
        <p><strong>Job:</strong> Scholar</p>
        <p class="keywords">Gridania, Open to RP, Healers, Male</p>
        <p>A neurotic healer drawn to adventure despite yearning for a quiet domestic life.</p>
        <button onclick="location.href='eldy.html'">View Full Profile</button>
      </div>
    </div>

    <div class="card" data-tags="Gridania,Open to RP,DPS,Male">
      <img src="pol1.png" alt="Seda'a 'Pol' Polaali">
      <div class="card-content">
        <h3>Seda'a 'Pol' Polaali</h3>
        <p><strong>Age:</strong> 30</p>
        <p><strong>Job:</strong> Dragoon</p>
        <p class="keywords">Gridania, Open to RP, DPS, Male</p>
        <p>Lives with his husband and child; gradually losing eyesight and thinking of becoming a Hunter-Scholar.</p>
        <button onclick="location.href='pol.html'">View Full Profile</button>
      </div>
    </div>

    <div class="card" data-tags="Gridania,Open to RP,Tanks,Male">
      <img src="celestial4.png" alt="Celestial Nebula">
      <div class="card-content">
        <h3>Celestial Nebula</h3>
        <p><strong>Age:</strong> 72</p>
        <p><strong>Job:</strong> Marauder</p>
        <p class="keywords">Gridania, Open to RP, Tanks, Male</p>
        <p>Host at Lunae’s who prefers small joys and time with Dioxia.</p>
        <button onclick="location.href='celestial.html'">View Full Profile</button>
      </div>
    </div>

    <div class="card" data-tags="The Far East,Open to RP,DPS,Male">
      <img src="foxglove.png" alt="Foxglove">
      <div class="card-content">
        <h3>Foxglove</h3>
        <p><strong>Age:</strong> 136</p>
        <p><strong>Job:</strong> Arcanist and Onnagata</p>
        <p class="keywords">The Far East, Open to RP, DPS, Male</p>
        <p>Graceful and mysterious; dangerous.</p>
        <button onclick="location.href='foxglove.html'">View Full Profile</button>
      </div>
    </div>

    <div class="card" data-tags="Open to RP,Open to Romance,DPS,The Far East,Female">
      <img src="himari1.png" alt="Himari Mihata">
      <div class="card-content">
        <h3>Himari Mihata</h3>
        <p><strong>Age:</strong> 31</p>
        <p><strong>Job:</strong> Okiya Okaasan and Samurai</p>
        <p class="keywords">Open to RP, Open to Romance, DPS, The Far East, Female</p>
        <p>Elegant and calculating; runs an okiya in Shirogane.</p>
        <button onclick="location.href='himari.html'">View Full Profile</button>
      </div>
    </div>

    <div class="card" data-tags="Open to RP,Healers,Male">
      <img src="moss.png" alt="Moss">
      <div class="card-content">
        <h3>Moss</h3>
        <p><strong>Age:</strong> 42</p>
        <p><strong>Job:</strong> Astrologian</p>
        <p class="keywords">Open to RP, Healers, Male</p>
        <p>Daydreaming diviner who is constantly bamboozled.</p>
        <button onclick="location.href='moss.html'">View Full Profile</button>
      </div>
    </div>

    <div class="card" data-tags="Gridania,Open to RP,DPS,Male">
      <img src="felix1.png" alt="Felixient Merthelin">
      <div class="card-content">
        <h3>Felixient Merthelin</h3>
        <p><strong>Age:</strong> 36</p>
        <p><strong>Job:</strong> Dancer</p>
        <p class="keywords">Gridania, Open to RP, DPS, Male</p>
        <p>Flamboyant, secretive, and possibly noble-born.</p>
        <button onclick="location.href='felixient.html'">View Full Profile</button>
      </div>
    </div>

    <div class="card" data-tags="Male,Crafter/Gatherer,Open to RP">
      <img src="fir2.png" alt="Fir">
      <div class="card-content">
        <h3>Fir</h3>
        <p><strong>Age:</strong> 90</p>
        <p><strong>Job:</strong> Goldsmith</p>
        <p class="keywords">Male, Crafter/Gatherer, Open to RP</p>
        <p>Burned exile turned goldsmith artisan.</p>
        <button onclick="location.href='fir.html'">View Full Profile</button>
      </div>
    </div>

    <div class="card" data-tags="Female,Healers,Open to Romance,Open to RP">
      <img src="raih1.png" alt="Raih Polaali">
      <div class="card-content">
        <h3>Raih Polaali</h3>
        <p><strong>Age:</strong> 31</p>
        <p><strong>Job:</strong> Conjurer/Hearer</p>
        <p class="keywords">Female, Healers, Open to Romance, Open to RP</p>
        <p>Destined to be a Hearer, but the voices are gone.</p>
        <button onclick="location.href='raih.html'">View Full Profile</button>
      </div>
    </div>

    <div class="card" data-tags="Male,DPS,The First">
      <img src="mosch1.png" alt="Hao-Mosch">
      <div class="card-content">
        <h3>Hao-Mosch</h3>
        <p><strong>Age:</strong> 23</p>
        <p><strong>Job:</strong> Dragoon/Cannoneer</p>
        <p class="keywords">Male, DPS, The First</p>
        <p>Quiet soul in chaos, tethered to Riiht’s fire.</p>
        <button onclick="location.href='mosch.html'">View Full Profile</button>
      </div>
    </div>

    <div class="card" data-tags="Male,Healers,The First">
      <img src="hatch1.png" alt="Kie-Hatch">
      <div class="card-content">
        <h3>Kie-Hatch</h3>
        <p><strong>Age:</strong> ??</p>
        <p><strong>Job:</strong> White Mage</p>
        <p class="keywords">Male, Healers, The First</p>
        <p>Haunted survivor of the Flood, seeking peace.</p>
        <button onclick="location.href='hatch.html'">View Full Profile</button>
      </div>
    </div>
  </section>

  <div style="text-align: center; margin: 2rem auto;">
    <img src="whitelily.png" alt="Section Divider" style="height: 40px; filter: brightness(1.1); transition: filter 0.3s ease-in-out;" onmouseover="this.style.filter='brightness(1.4) drop-shadow(0 0 6px white)'" onmouseout="this.style.filter='brightness(1.1)'">
  </div>

  <section id="mooglemail" style="padding: 2rem; max-width: 800px; margin: auto; background: url('https://www.transparenttextures.com/patterns/aged-paper.png'); background-color: rgba(255,255,255,0.9); border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
    <h2>Send a letter through moogle mail</h2>
    <form>
      <label for="senderName">Your name:</label><br>
      <input type="text" id="senderName" name="senderName" style="width: 100%; margin-bottom: 1rem;">

      <label for="characterSelect">Character to contact:</label><br>
      <select id="characterSelect" name="characterSelect" style="width: 100%; margin-bottom: 1rem;">
        <option value="Eldy Matthiola">Eldy Matthiola</option>
        <option value="Seda'a 'Pol' Polaali">Seda'a 'Pol' Polaali</option>
        <option value="Celestial Nebula">Celestial Nebula</option>
        <option value="Foxglove">Foxglove</option>
        <option value="Himari Mihata">Himari Mihata</option>
        <option value="Moss">Moss</option>
        <option value="Felixient Merthelin">Felixient Merthelin</option>
        <option value="Fir">Fir</option>
        <option value="Raih Polaali">Raih Polaali</option>
        <option value="Hao-Mosch">Hao-Mosch</option>
        <option value="Kie-Hatch">Kie-Hatch</option>
      </select>

      <label for="message">Your message:</label><br>
      <textarea id="message" name="message" rows="5" style="width: 100%; margin-bottom: 1rem;"></textarea>

      <fieldset style="margin-bottom: 1rem;">
        <legend>What kind of RP are you interested in?</legend>
        <label><input type="checkbox" name="rpType" value="Long-term RP"> Long-term RP</label><br>
        <label><input type="checkbox" name="rpType" value="Adventure RP"> Adventure RP</label><br>
        <label><input type="checkbox" name="rpType" value="Romance RP"> Romance RP</label><br>
        <label><input type="checkbox" name="rpType" value="One-Off RP Request"> One-Off RP Request</label><br>
        <label><input type="checkbox" name="rpType" value="Just putting out feelers"> Just putting out feelers</label>
      </fieldset>

      <label for="profileURL">Your character profile URL:</label><br>
      <input type="url" id="profileURL" name="profileURL" style="width: 100%; margin-bottom: 1rem;"><br>

      <button type="button" onclick="generateDiscordMessage()">Send via Discord (eldy.)</button>
      <button type="button" onclick="generateEmail()">Send via Email (eldritchmortis@gmail.com)</button>
    </form>
    <p id="output" style="margin-top: 1rem; white-space: pre-wrap;"></p>
<button onclick="copyToClipboard()" style="margin-top: 0.5rem;">Copy to Clipboard</button>
  </section>

  <script>
    function getFormData() {
      const name = document.getElementById('senderName').value;
      const character = document.getElementById('characterSelect').value;
      const message = document.getElementById('message').value;
      const profileURL = document.getElementById('profileURL').value;
      const checkboxes = document.querySelectorAll('input[name="rpType"]:checked');
      const rpTypes = Array.from(checkboxes).map(cb => cb.value).join(', ');

      return { name, character, message, rpTypes, profileURL };
    }

    function generateDiscordMessage() {
  const { name, character, message, rpTypes, profileURL } = getFormData();
  const output = `Copy and paste this message into Discord and send it to eldy. (Yes, include the period at the end!):

Hello! My name is ${name}, and I'd like to RP with ${character}.

Message:
${message}

RP Types: ${rpTypes}
Character Profile: ${profileURL}`;
  document.getElementById('output').textContent = output;
  window.open('https://discord.com/app', '_blank');
    }

    function generateEmail() {
      const { name, character, message, rpTypes, profileURL } = getFormData();
      const emailBody = `Hello! My name is ${name}, and I'd like to RP with ${character}.%0D%0A%0D%0AMessage:%0D%0A${message}%0D%0A%0D%0ARP Types: ${rpTypes}%0D%0ACharacter Profile: ${profileURL}`;
      window.location.href = `mailto:eldritchmortis@gmail.com?subject=RP Request for ${character}&body=${emailBody}`;
    }
  function copyToClipboard() {
  const text = document.getElementById('output').textContent;
  navigator.clipboard.writeText(text).then(() => {
    alert('Copied to clipboard!');
  }).catch(err => {
    alert('Failed to copy text: ' + err);
  });
}
</script>
<script>
function filterCards(tag) {
  const cards = document.querySelectorAll('.card');
  
  cards.forEach(card => {
    const tags = card.dataset.tags.split(',').map(t => t.trim().toLowerCase());

    if (tag === 'all' || tags.includes(tag.toLowerCase())) {
      card.style.display = 'block';
    } else {
      card.style.display = 'none';
    }
  });
}
</script>
</body>
</html>
