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

body{
  background: var(--papyrus);
  color: var(--ink);
  font-family: 'Source Serif 4', serif;
  line-height: 1.65;
}

h1, h2, h3, .brand{
  font-family: 'Cinzel', serif;
  font-weight: 600;
  letter-spacing: 0.01em;
}

/* Nav */
#topnav{
  position: sticky;
  top: 0;
  z-index: 10;
  background: var(--lapis);
  color: var(--papyrus);
  display:flex;
  align-items:center;
  justify-content:space-between;
  padding: 0.9rem 1.5rem;
  flex-wrap: wrap;
  gap: 0.6rem;
}
#topnav .brand{ font-size: 1.05rem; color: var(--gold); }
#topnav ul{
  list-style:none;
  display:flex;
  gap: 1.2rem;
  flex-wrap: wrap;
}
#topnav a{
  color: var(--papyrus);
  text-decoration:none;
  font-family: 'Source Serif 4', serif;
  font-size: 0.95rem;
  border-bottom: 1px solid transparent;
}
#topnav a:hover, #topnav a:focus-visible{
  border-bottom-color: var(--gold);
  outline: none;
}

/* Hero */
.hero{
  max-width: 760px;
  margin: 0 auto;
  padding: 4.5rem 1.5rem 3rem;
  text-align: left;
  border-bottom: 1px solid var(--line);
}
.kicker{
  color: var(--gold);
  font-size: 0.95rem;
  margin-bottom: 0.6rem;
}
.hero h1{
  font-size: 3rem;
  color: var(--lapis);
  margin-bottom: 1rem;
}
.hero-sub{
  max-width: 55ch;
  font-size: 1.1rem;
  color: #4A3E2E;
}

main{
  max-width: 760px;
  margin: 0 auto;
  padding: 0 1.5rem;
}

section{
  padding: 3.2rem 0;
  border-bottom: 1px solid var(--line);
}
section:last-of-type{ border-bottom: none; }

section h2{
  font-size: 1.7rem;
  color: var(--lapis);
  margin-bottom: 1rem;
}
.section-intro{
  max-width: 62ch;
  margin-bottom: 1.6rem;
  color: #4A3E2E;
}
section p{ max-width: 68ch; }

/* Timeline (a real sequence, so numbering/markers are justified) */
.timeline{
  list-style:none;
  border-left: 2px solid var(--gold);
  padding-left: 1.5rem;
  display:flex;
  flex-direction: column;
  gap: 1.8rem;
}
.timeline li{ position: relative; }
.timeline li::before{
  content:'';
  position:absolute;
  left: -1.63rem;
  top: 0.3rem;
  width: 10px;
  height: 10px;
  border-radius: 50%;
  background: var(--gold);
}
.t-date{
  display:block;
  font-family: 'Cinzel', serif;
  font-size: 0.85rem;
  color: var(--gold);
  margin-bottom: 0.2rem;
}
.timeline h3{ font-size: 1.1rem; margin-bottom: 0.3rem; color: var(--ink); }

/* Cards */
.card-grid{
  display:grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 1.2rem;
}
.card{
  background: var(--sand);
  border: 1px solid var(--line);
  padding: 1.2rem 1.3rem;
  border-radius: 2px;
}
.card h3{ font-size: 1.05rem; margin-bottom: 0.4rem; color: var(--lapis); }
.card p{ font-size: 0.95rem; color: #3A2F22; }

.sources{
  list-style: disc;
  padding-left: 1.4rem;
  color: #4A3E2E;
  display:flex;
  flex-direction:column;
  gap:0.4rem;
}

footer{
  text-align:center;
  padding: 2.5rem 1.5rem 3rem;
  font-size: 0.9rem;
  color: #6B5D45;
}

a:focus-visible, button:focus-visible{
  outline: 2px solid var(--gold);
  outline-offset: 2px;
}

@media (max-width: 600px){
  .hero h1{ font-size: 2.2rem; }
  .card-grid{ grid-template-columns: 1fr; }
  #topnav{ flex-direction: column; align-items:flex-start; }
}

@media (prefers-reduced-motion: reduce){
  html{ scroll-behavior: auto; }
}
