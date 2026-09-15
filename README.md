<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ancient Egypt — History Project</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@500;600&family=Source+Serif+4:opsz,wght@8..60,400;8..60,600&display=swap" rel="stylesheet">
<style>
:root{
  --sand: #E7D8AE;
  --papyrus: #F6EFDD;
  --lapis: #1B3B6F;
  --gold: #B8892B;
  --ink: #2B2118;
  --line: rgba(43,33,24,0.15);
}
*{ box-sizing: border-box; margin:0; padding:0; }
html{ scroll-behavior:smooth; }
body{ background: var(--papyrus); color: var(--ink); font-family: 'Source Serif 4', serif; line-height: 1.65; }
h1, h2, h3, .brand{ font-family: 'Cinzel', serif; font-weight: 600; letter-spacing: 0.01em; }
#topnav{ position: sticky; top: 0; z-index: 10; background: var(--lapis); color: var(--papyrus); display:flex; align-items:center; justify-content:space-between; padding: 0.9rem 1.5rem; flex-wrap: wrap; gap: 0.6rem; }
#topnav .brand{ font-size: 1.05rem; color: var(--gold); }
#topnav ul{ list-style:none; display:flex; gap: 1.2rem; flex-wrap: wrap; }
#topnav a{ color: var(--papyrus); text-decoration:none; font-family: 'Source Serif 4', serif; font-size: 0.95rem; border-bottom: 1px solid transparent; }
#topnav a:hover, #topnav a:focus-visible{ border-bottom-color: var(--gold); outline: none; }
.hero{ max-width: 760px; margin: 0 auto; padding: 4.5rem 1.5rem 3rem; border-bottom: 1px solid var(--line); }
.kicker{ color: var(--gold); font-size: 0.95rem; margin-bottom: 0.6rem; }
.hero h1{ font-size: 3rem; color: var(--lapis); margin-bottom: 1rem; }
.hero-sub{ max-width: 55ch; font-size: 1.1rem; color: #4A3E2E; }
main{ max-width: 760px; margin: 0 auto; padding: 0 1.5rem; }
section{ padding: 3.2rem 0; border-bottom: 1px solid var(--line); }
section:last-of-type{ border-bottom: none; }
section h2{ font-size: 1.7rem; color: var(--lapis); margin-bottom: 1rem; }
.section-intro{ max-width: 62ch; margin-bottom: 1.6rem; color: #4A3E2E; }
section p{ max-width: 68ch; }
.timeline{ list-style:none; border-left: 2px solid var(--gold); padding-left: 1.5rem; display:flex; flex-direction: column; gap: 1.8rem; }
.timeline li{ position: relative; }
.timeline li::before{ content:''; position:absolute; left: -1.63rem; top: 0.3rem; width: 10px; height: 10px; border-radius: 50%; background: var(--gold); }
.t-date{ display:block; font-family: 'Cinzel', serif; font-size: 0.85rem; color: var(--gold); margin-bottom: 0.2rem; }
.timeline h3{ font-size: 1.1rem; margin-bottom: 0.3rem; color: var(--ink); }
.card-grid{ display:grid; grid-template-columns: repeat(2, 1fr); gap: 1.2rem; }
.card{ background: var(--sand); border: 1px solid var(--line); padding: 1.2rem 1.3rem; border-radius: 2px; }
.card h3{ font-size: 1.05rem; margin-bottom: 0.4rem; color: var(--lapis); }
.card p{ font-size: 0.95rem; color: #3A2F22; }
.sources{ list-style: disc; padding-left: 1.4rem; color: #4A3E2E; display:flex; flex-direction:column; gap:0.4rem; }
footer{ text-align:center; padding: 2.5rem 1.5rem 3rem; font-size: 0.9rem; color: #6B5D45; }
a:focus-visible, button:focus-visible{ outline: 2px solid var(--gold); outline-offset: 2px; }
@media (max-width: 600px){
  .hero h1{ font-size: 2.2rem; }
  .card-grid{ grid-template-columns: 1fr; }
  #topnav{ flex-direction: column; align-items:flex-start; }
}
@media (prefers-reduced-motion: reduce){ html{ scroll-behavior: auto; } }
</style>
</head>
<body>

  <nav id="topnav">
    <span class="brand">Ancient Egypt</span>
    <ul>
      <li><a href="#timeline">Timeline</a></li>
      <li><a href="#pharaohs">Pharaohs</a></li>
      <li><a href="#religion">Religion</a></li>
      <li><a href="#architecture">Architecture</a></li>
      <li><a href="#daily-life">Daily Life</a></li>
      <li><a href="#sources">Sources</a></li>
    </ul>
  </nav>

  <header class="hero">
    <p class="kicker">A History Project</p>
    <h1>Ancient Egypt</h1>
    <p class="hero-sub">Three thousand years of one civilization along a single river — its rulers, its gods, and the monuments it left behind.</p>
  </header>

  <main>

    <section id="timeline">
      <h2>Timeline</h2>
      <p class="section-intro">Ancient Egyptian history is usually divided into three major kingdoms, separated by periods of instability.</p>
      <ol class="timeline">
        <li>
          <span class="t-date">c. 3100 BCE</span>
          <div>
            <h3>Unification</h3>
            <p>King Narmer unites Upper and Lower Egypt into a single kingdom, traditionally marking the start of dynastic Egypt.</p>
          </div>
        </li>
        <li>
          <span class="t-date">2686–2181 BCE</span>
          <div>
            <h3>Old Kingdom</h3>
            <p>The "Age of the Pyramids." Pharaohs like Khufu commission the Giza pyramids as royal tombs.</p>
          </div>
        </li>
        <li>
          <span class="t-date">2055–1650 BCE</span>
          <div>
            <h3>Middle Kingdom</h3>
            <p>A period of reunification and cultural growth, with expanded trade and irrigation projects along the Nile.</p>
          </div>
        </li>
        <li>
          <span class="t-date">1550–1077 BCE</span>
          <div>
            <h3>New Kingdom</h3>
            <p>Egypt's imperial peak. Rulers such as Hatshepsut, Akhenaten, and Ramesses II expand Egypt's borders and build monuments like Abu Simbel.</p>
          </div>
        </li>
        <li>
          <span class="t-date">30 BCE</span>
          <div>
            <h3>Roman Conquest</h3>
            <p>After the death of Cleopatra VII, Egypt becomes a province of the Roman Empire, ending dynastic rule.</p>
          </div>
        </li>
      </ol>
    </section>

    <section id="pharaohs">
      <h2>Notable Pharaohs</h2>
      <div class="card-grid">
        <article class="card">
          <h3>Khufu</h3>
          <p>Second pharaoh of the Fourth Dynasty, credited with commissioning the Great Pyramid of Giza, the largest pyramid ever built.</p>
        </article>
        <article class="card">
          <h3>Hatshepsut</h3>
          <p>One of the few female pharaohs to rule in her own right, known for expanding trade routes, notably to the land of Punt.</p>
        </article>
        <article class="card">
          <h3>Akhenaten</h3>
          <p>Attempted a religious revolution by promoting the worship of a single god, the sun-disk Aten, over the traditional pantheon.</p>
        </article>
        <article class="card">
          <h3>Ramesses II</h3>
          <p>Ruled for 66 years, fought the Battle of Kadesh, and built extensively, including the temples at Abu Simbel.</p>
        </article>
      </div>
    </section>

    <section id="religion">
      <h2>Religion &amp; Mythology</h2>
      <p class="section-intro">Egyptian religion centered on maintaining <em>ma'at</em> — cosmic order and balance — through ritual, offerings, and the pharaoh's divine role.</p>
      <div class="card-grid">
        <article class="card">
          <h3>Ra</h3>
          <p>The sun god, considered the creator and one of the most important deities, often depicted with a falcon's head.</p>
        </article>
        <article class="card">
          <h3>Osiris</h3>
          <p>God of the afterlife and judge of the dead, central to Egyptian beliefs about resurrection and the underworld.</p>
        </article>
        <article class="card">
          <h3>Isis</h3>
          <p>Goddess of magic and motherhood, wife of Osiris, widely worshipped throughout Egyptian history.</p>
        </article>
        <article class="card">
          <h3>Anubis</h3>
          <p>Jackal-headed god associated with mummification and guiding souls to the afterlife.</p>
        </article>
      </div>
    </section>

    <section id="architecture">
      <h2>Pyramids &amp; Architecture</h2>
      <p>
        Egyptian monumental architecture reflects both engineering skill and religious purpose. The step pyramid of
        Djoser at Saqqara, designed by the architect Imhotep, is considered the earliest large-scale stone
        building in history. It set the template for the true pyramids that followed at Giza, built as tombs
        intended to help the pharaoh's soul ascend to the afterlife. Temples such as Karnak and Abu Simbel
        served a different purpose: as houses for the gods, maintained by priests through daily rituals of
        offering and worship.
      </p>
    </section>

    <section id="daily-life">
      <h2>Daily Life</h2>
      <p>
        Most ancient Egyptians were farmers, and their year was structured around the Nile's annual flood, which
        deposited fertile silt on the fields. Society was organized in a broad hierarchy: the pharaoh and nobility
        at the top, followed by priests, scribes, artisans, and farmers. Scribes held particular status, since
        literacy in hieroglyphic and hieratic script was rare and essential to running the state. Family life,
        food (bread and beer were dietary staples), and craft work such as pottery and weaving filled most
        people's daily routines.
      </p>
    </section>

    <section id="sources">
      <h2>Sources</h2>
      <p class="section-intro">Replace these with the sources you actually used for your assignment — cite properly according to your teacher's required format (MLA, APA, etc.).</p>
      <ul class="sources">
        <li>[Textbook name], [Author], [Chapter/Page numbers]</li>
        <li>[Museum or academic website], [URL], [Access date]</li>
        <li>[Documentary or video source], [Title], [Year]</li>
      </ul>
    </section>

  </main>

  <footer>
    <p>Made by <span id="student-name">Your Name</span> — History Class Project</p>
  </footer>

  <script>
    document.getElementById('year');
    document.getElementById('student-name').textContent = 'Your Name';
  </script>
</body>
</html>
