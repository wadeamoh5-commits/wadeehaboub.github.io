# wadeehaboub.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="The personal portfolio of Wadee Haboub, Software Engineering student.">
  <title>Wadee Haboub | Software Engineering Student</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
  <style>
*{margin:0;padding:0;box-sizing:border-box}
:root{--ease:cubic-bezier(.22,1,.36,1)}
:root{--bg:#09080f;--surface:#12101b;--surface2:#171421;--text:#f7f5fb;--muted:#a7a1b3;--purple:#a879ff;--purple2:#7541d8;--line:rgba(255,255,255,.09);--shadow:0 24px 80px rgba(0,0,0,.28)}
body.light{--bg:#f7f5fb;--surface:#fff;--surface2:#f0edf7;--text:#171221;--muted:#696276;--line:rgba(30,20,50,.12);--shadow:0 24px 80px rgba(40,20,70,.09)}
html{scroll-behavior:smooth;scroll-padding-top:90px}
body{font-family:Inter,Arial,sans-serif;background:var(--bg);color:var(--text);line-height:1.65;overflow-x:hidden;transition:background .3s,color .3s}
a{color:inherit;text-decoration:none}
.ambient{position:absolute;width:380px;height:380px;border-radius:50%;filter:blur(110px);opacity:.15;pointer-events:none;background:#873cff}.ambient-one{top:100px;left:-220px}.ambient-two{top:650px;right:-250px}
.site-header{height:82px;max-width:1180px;margin:auto;padding:0 28px;display:flex;align-items:center;justify-content:space-between;position:sticky;top:0;z-index:20;background:color-mix(in srgb,var(--bg) 86%,transparent);backdrop-filter:blur(18px);border-bottom:1px solid var(--line)}
.brand{font-size:25px;font-weight:800;letter-spacing:-2px}.brand span{color:var(--purple)}
nav{display:flex;gap:27px}nav a{font-size:14px;color:var(--muted);font-weight:600;transition:.2s}nav a:hover,nav a.active{color:var(--purple)}
.theme-toggle,.menu-toggle{background:var(--surface2);border:1px solid var(--line);color:var(--text);width:38px;height:38px;border-radius:50%;font-size:18px;cursor:pointer}.menu-toggle{display:none}
.section{max-width:1124px;margin:auto;padding:115px 28px;position:relative}.hero{min-height:690px;display:grid;grid-template-columns:1.1fr .9fr;align-items:center;padding-top:80px;padding-bottom:100px}
.eyebrow,.section-kicker,.social-note,.project-label,.skill-level,.contact-links a>span{font-size:12px;font-weight:700;letter-spacing:2px;color:var(--purple)}
.status-dot{display:inline-block;width:7px;height:7px;border-radius:50%;background:#8fe2a8;box-shadow:0 0 12px #8fe2a8;margin-right:8px}
.hello{color:var(--muted);font-size:18px;margin-top:24px}.hero h1{font-size:clamp(62px,8vw,100px);line-height:.98;letter-spacing:-3px;font-weight:800;margin:9px 0 20px}.hero h1 span,.section-heading-row h2 span,.contact-box h2 span{color:var(--purple)}
.hero h2{font-size:18px;font-weight:600;letter-spacing:.2px}.hero-description{color:var(--muted);font-size:17px;max-width:500px;margin:18px 0 28px}
.hero-actions{display:flex;gap:12px;flex-wrap:wrap}.button{padding:14px 22px;border-radius:8px;font-size:14px;font-weight:700;transition:.25s}.button{transition:transform .5s var(--ease),box-shadow .5s var(--ease)}.button:hover{transform:translateY(-3px);box-shadow:0 14px 34px rgba(117,65,216,.28)}.primary{background:var(--purple);color:#130d20}.primary span{margin-left:12px}.secondary{border:1px solid var(--line);color:var(--text)}
.social-note{font-size:12px;color:var(--muted);margin-top:52px;letter-spacing:1.5px}.social-note span{color:var(--purple);padding:0 8px}
.hero-visual{height:440px;display:grid;place-items:center;position:relative}.avatar-card{width:275px;height:330px;border:1px solid rgba(168,121,255,.35);border-radius:18px;background:linear-gradient(145deg,#25183c,#100e19 65%);box-shadow:0 30px 90px rgba(116,57,205,.22);padding:18px;position:relative;z-index:2;transform:rotate(3deg);animation:float 7s ease-in-out infinite}
.avatar{height:245px;border-radius:11px;background:radial-gradient(circle at 50% 35%,#9d70e8,#56318e 48%,#211632 80%);display:grid;place-items:center;font-size:75px;font-weight:800;letter-spacing:-7px;color:#fff;text-shadow:0 8px 30px #27133f}
.avatar-caption{padding:14px 5px 0;display:flex;flex-direction:column}.avatar-caption span{font-size:14px;font-weight:800;letter-spacing:1px;color:#fff}.avatar-caption small{font-size:13px;color:#bcb0d0}
.orbit{position:absolute;border:1px solid rgba(168,121,255,.2);border-radius:50%;width:380px;height:380px}.orbit-b{width:440px;height:440px;border-style:dashed;opacity:.5}.floating-tag{position:absolute;z-index:3;padding:10px 14px;background:var(--surface2);border:1px solid var(--line);border-radius:8px;font-size:13px;font-weight:700;box-shadow:var(--shadow)}.tag-top{top:45px;right:0;color:var(--purple)}.tag-bottom{bottom:45px;left:-5px;color:var(--text)}.purple-glow{position:absolute;width:220px;height:220px;background:#823cff;filter:blur(100px);opacity:.3}
.scroll-cue{position:absolute;bottom:32px;left:28px;color:var(--muted);font-size:12px;letter-spacing:2px}.scroll-cue span{color:var(--purple);margin-left:10px}
.section-kicker{margin-bottom:18px}.section-heading-row{display:flex;align-items:end;justify-content:space-between;gap:30px;margin-bottom:42px}.section-heading-row h2{font-size:clamp(34px,5vw,52px);letter-spacing:-2.5px;line-height:1.1}.section-heading-row>p{max-width:320px;color:var(--muted);font-size:15px}
.about-grid{display:grid;grid-template-columns:1.2fr .8fr;gap:18px}.about-card,.fact-card,.skill-card,.project-card,.goal-panel{background:var(--surface);border:1px solid var(--line);border-radius:13px}
.about-main{padding:34px}.card-icon{font-size:28px;color:var(--purple)}.about-main h3{font-size:21px;margin:15px 0}.about-main p{font-size:16px;color:var(--muted);margin-top:12px;max-width:650px}
.fact-stack{display:grid;gap:12px}.fact-card{display:flex;align-items:center;gap:18px;padding:16px 20px}.fact-card>span,.goal-list>div>span{font-size:11px;color:var(--purple);font-weight:800}.fact-card div{display:flex;flex-direction:column}.fact-card small{font-size:12px;letter-spacing:1.5px;color:var(--muted)}.fact-card strong{font-size:15px}
.skills-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:14px}.skill-card{padding:23px;min-height:180px}.skill-card.in{transition:transform .5s var(--ease),border-color .3s,box-shadow .5s var(--ease)}.skill-card.in:hover{transform:translateY(-6px);border-color:rgba(168,121,255,.5);box-shadow:0 20px 50px rgba(117,65,216,.18)}.skill-symbol{display:grid;place-items:center;width:35px;height:35px;border-radius:9px;background:rgba(168,121,255,.13);color:var(--purple);font-weight:800;font-size:13px}.skill-card h3{font-size:15px;margin:15px 0 5px}.skill-card p{font-size:14px;color:var(--muted);min-height:36px}.skill-level{display:block;font-size:12px;letter-spacing:1px;margin-top:14px}.honest-note{color:var(--muted);font-size:13px;margin-top:16px}
.project-card{display:grid;grid-template-columns:.85fr 1.15fr;overflow:hidden}.project-art{min-height:300px;background:radial-gradient(circle at 50% 45%,#50317e,#1c142b 65%);display:grid;place-items:center;position:relative}.project-window{width:205px;height:150px;border-radius:9px;background:#0d0b13;border:1px solid #7953a9;padding:15px;box-shadow:0 20px 45px #09060f}.window-dots{display:flex;gap:5px;margin-bottom:20px}.window-dots i{width:6px;height:6px;border-radius:50%;background:#a879ff}.mock-line{height:6px;width:90%;background:#413153;border-radius:8px;margin:10px 0}.mock-line.short{width:35%;background:#a879ff}.mock-line.medium{width:65%}.mock-pill{height:18px;width:55px;background:#8052c3;border-radius:4px;margin-top:17px}.project-number{position:absolute;bottom:18px;left:20px;font-size:12px;letter-spacing:2px;color:#c7b2e8}.project-info{padding:38px}.project-label{font-size:12px}.project-info h3{font-size:26px;margin:12px 0}.project-info p{font-size:16px;color:var(--muted);max-width:470px}.chips{display:flex;gap:8px;margin:20px 0}.chips span{font-size:12px;padding:5px 10px;border-radius:30px;background:var(--surface2);color:var(--purple)}.in-progress{font-size:12px;letter-spacing:1px;color:var(--purple);font-weight:700}
.goal-panel{padding:35px;display:grid;grid-template-columns:.8fr 1.2fr;gap:35px}.goal-star{font-size:28px;color:var(--purple)}.goal-intro h3{font-size:22px;margin:12px 0}.goal-intro p{font-size:15px;color:var(--muted);max-width:300px}.goal-list>div{display:grid;grid-template-columns:30px 1fr auto;gap:12px;align-items:center;padding:15px 0;border-bottom:1px solid var(--line)}.goal-list>div:last-child{border:0}.goal-list p{font-size:15px}.goal-list b{font-size:12px;letter-spacing:1px;color:var(--purple)}
.contact-box{background:linear-gradient(120deg,#211632,#171020);border:1px solid rgba(168,121,255,.25);border-radius:16px;padding:48px;display:grid;grid-template-columns:1fr 1fr;gap:35px}.contact-box h2{font-size:clamp(38px,5vw,58px);line-height:1.08;letter-spacing:-3px;margin:17px 0}.contact-copy{font-size:15px;color:#b9afc8;max-width:350px}.contact-links{display:flex;flex-direction:column;justify-content:center;gap:12px}.contact-links a{padding:17px;border:1px solid rgba(255,255,255,.12);border-radius:8px;display:flex;flex-direction:column;gap:5px;transition:transform .4s var(--ease),border-color .3s}.contact-links a:hover{border-color:var(--purple);transform:translateX(4px)}.contact-links a>span{font-size:12px}.contact-links strong{font-size:15px;color:#fff;overflow-wrap:anywhere}
footer{max-width:1124px;margin:auto;padding:25px 28px 35px;border-top:1px solid var(--line);display:flex;align-items:center;justify-content:space-between}footer p,footer .back-top{font-size:12px;letter-spacing:1.4px;color:var(--muted)}footer .back-top:hover{color:var(--purple)}
.rv{opacity:0;transform:translateY(28px);transition:opacity .9s var(--ease),transform .9s var(--ease)}.rv.in{opacity:1;transform:none}.hero-visual.rv{transition-delay:.2s}.skill-card:nth-child(2n).rv{transition-delay:.08s}.skill-card:nth-child(3n).rv{transition-delay:.16s}
@keyframes float{50%{transform:rotate(3deg) translateY(-12px)}}
.site-header{transition:height .4s var(--ease),background .3s}.site-header.scrolled{height:66px;background:color-mix(in srgb,var(--bg) 94%,transparent)}
:focus-visible{outline:2px solid var(--purple);outline-offset:3px}
@media (prefers-reduced-motion:reduce){*{animation:none!important;transition:none!important}.rv{opacity:1;transform:none}}
@media(max-width:760px){.site-header{height:70px;padding:0 20px}nav{display:none;position:absolute;top:70px;left:0;right:0;padding:20px;background:var(--surface);border-bottom:1px solid var(--line);flex-direction:column;gap:18px}nav.open{display:flex}.menu-toggle{display:block;margin-left:9px}.site-header{justify-content:flex-end}.brand{margin-right:auto}.hero{grid-template-columns:1fr;padding-top:65px;gap:20px}.hero h1{font-size:75px}.hero-visual{height:390px}.avatar-card{width:245px;height:300px}.avatar{height:215px}.orbit{width:320px;height:320px}.orbit-b{width:360px;height:360px}.tag-top{right:5px}.tag-bottom{left:0}.section{padding:82px 22px}.section-heading-row{display:block}.section-heading-row>p{margin-top:15px}.about-grid,.project-card,.goal-panel,.contact-box{grid-template-columns:1fr}.skills-grid{grid-template-columns:repeat(2,1fr)}.project-art{min-height:250px}.project-info{padding:27px}.goal-panel{padding:25px;gap:20px}.contact-box{padding:30px 24px}footer{padding:22px;gap:12px;flex-wrap:wrap}footer p{order:3;width:100%}.scroll-cue{left:22px}}
@media(max-width:420px){.hero h1{font-size:64px;letter-spacing:-2px}.skills-grid{grid-template-columns:1fr}.skill-card{min-height:150px}.goal-list>div{grid-template-columns:22px 1fr}.goal-list b{grid-column:2}.social-note{font-size:8px}.contact-box h2{font-size:43px}}

</style>
</head>
<body>
  <div class="ambient ambient-one"></div>
  <div class="ambient ambient-two"></div>

  <header class="site-header">
    <a class="brand" href="#home">WH<span>.</span></a>
    <nav id="nav">
      <a href="#home" class="nav-link active">Home</a>
      <a href="#about" class="nav-link">About</a>
      <a href="#skills" class="nav-link">Skills</a>
      <a href="#projects" class="nav-link">Projects</a>
      <a href="#goals" class="nav-link">Goals</a>
      <a href="#contact" class="nav-link">Contact</a>
    </nav>
    <button class="theme-toggle" id="themeToggle" aria-label="Switch color theme">☼</button>
    <button class="menu-toggle" id="menuToggle" aria-label="Open navigation">☰</button>
  </header>

  <main>
    <section class="hero section" id="home">
      <div class="hero-copy reveal">
        <div class="eyebrow"><span class="status-dot"></span> FIRST-YEAR SOFTWARE ENGINEERING STUDENT</div>
        <p class="hello">Hello, I'm</p>
        <h1>WADEE<br><span>HABOUB</span></h1>
        <h2>Software Engineering Student</h2>
        <p class="hero-description">Building my future one line of code at a time. Curious about technology, passionate about learning, and working toward becoming a freelance developer.</p>
        <div class="hero-actions">
          <a class="button primary" href="#projects">Explore my work <span>↗</span></a>
          <a class="button secondary" href="#contact">Get in touch</a>
        </div>
        <div class="social-note">PALESTINE <span>•</span> SOFTWARE ENGINEERING <span>•</span> FOOTBALL LOVER</div>
      </div>
      <div class="hero-visual reveal">
        <div class="orbit orbit-a"></div><div class="orbit orbit-b"></div>
        <div class="avatar-card">
          <!-- Replace this WH avatar with your photo later if you want. -->
          <div class="avatar">WH</div>
          <div class="avatar-caption"><span>WADEE HABOUB</span><small>Learning. Building. Growing.</small></div>
        </div>
        <div class="floating-tag tag-top">✦ Always learning</div>
        <div class="floating-tag tag-bottom"><span class="status-dot"></span> Open to opportunities</div>
        <div class="purple-glow"></div>
      </div>
      <a class="scroll-cue" href="#about">SCROLL TO EXPLORE <span>↓</span></a>
    </section>

    <section class="section about-section" id="about">
      <div class="section-kicker">01 / ABOUT ME</div>
      <div class="section-heading-row">
        <h2>A little <span>about me.</span></h2>
        <p>Every expert starts as a beginner. This is where my journey begins.</p>
      </div>
      <div class="about-grid">
        <article class="about-card about-main">
          <div class="card-icon">✳</div>
          <h3>Who am I?</h3>
          <p>I'm Wadee Haboub, a 19-year-old Palestinian student in my first year of Software Engineering at AUG. I'm new to the world of development and excited to turn what I learn into real projects.</p>
          <p>Outside technology, I love football. I'm interested in IT, creative problem-solving, and building a future where I can work independently with clients around the world.</p>
        </article>
        <div class="fact-stack">
          <div class="fact-card"><span>01</span><div><small>FIELD OF STUDY</small><strong>Software Engineering</strong></div></div>
          <div class="fact-card"><span>02</span><div><small>BASED IN / FROM</small><strong>Palestine</strong></div></div>
          <div class="fact-card"><span>03</span><div><small>ENGLISH LEVEL</small><strong>B1 — Intermediate</strong></div></div>
          <div class="fact-card"><span>04</span><div><small>FAVORITE INTEREST</small><strong>Football ⚽</strong></div></div>
        </div>
      </div>
    </section>

    <section class="section skills-section" id="skills">
      <div class="section-kicker">02 / WHAT I'M LEARNING</div>
      <div class="section-heading-row">
        <h2>My learning <span>toolkit.</span></h2>
        <p>I'm at the beginning of my journey, developing the foundations step by step.</p>
      </div>
      <div class="skills-grid">
        <div class="skill-card"><span class="skill-symbol">5</span><h3>HTML</h3><p>Learning the structure of web pages</p><span class="skill-level">CURRENTLY LEARNING</span></div>
        <div class="skill-card"><span class="skill-symbol">✳</span><h3>CSS</h3><p>Exploring layouts, styling and responsive design</p><span class="skill-level">CURRENTLY LEARNING</span></div>
        <div class="skill-card"><span class="skill-symbol">JS</span><h3>JavaScript</h3><p>Building a foundation in web interactivity</p><span class="skill-level">TO LEARN</span></div>
        <div class="skill-card"><span class="skill-symbol">J</span><h3>Java</h3><p>Starting my programming fundamentals</p><span class="skill-level">CURRENTLY LEARNING</span></div>
        <div class="skill-card"><span class="skill-symbol">⌘</span><h3>VS Code</h3><p>My code editor and development workspace</p><span class="skill-level">USING</span></div>
        <div class="skill-card"><span class="skill-symbol">IT</span><h3>Information Technology</h3><p>A field I'm curious to explore further</p><span class="skill-level">INTEREST</span></div>
      </div>
      <p class="honest-note">This section reflects my current learning journey, not professional-level experience.</p>
    </section>

    <section class="section projects-section" id="projects">
      <div class="section-kicker">03 / MY PROJECTS</div>
      <div class="section-heading-row">
        <h2>My first steps <span>into building.</span></h2>
        <p>Every project is a chance to learn something new.</p>
      </div>
      <article class="project-card">
        <div class="project-art"><div class="project-window"><div class="window-dots"><i></i><i></i><i></i></div><div class="mock-line short"></div><div class="mock-line"></div><div class="mock-line medium"></div><div class="mock-pill"></div></div><span class="project-number">PROJECT 001</span></div>
        <div class="project-info"><span class="project-label">FIRST PERSONAL PROJECT</span><h3>My Personal Portfolio</h3><p>A personal website introducing who I am, what I'm learning, and where I want to go. This is the first project in my development journey, and the beginning of many more.</p><div class="chips"><span>HTML</span><span>CSS</span><span>JavaScript</span></div><span class="in-progress">✦ FIRST PROJECT</span></div>
      </article>
    </section>

    <section class="section goals-section" id="goals">
      <div class="section-kicker">04 / THE ROAD AHEAD</div>
      <div class="section-heading-row">
        <h2>Focused on <span>what's next.</span></h2>
        <p>Big goals are reached through small, consistent steps.</p>
      </div>
      <div class="goal-panel">
        <div class="goal-intro"><span class="goal-star">✦</span><h3>My vision</h3><p>Graduate, keep improving my skills, and build a career that gives me the freedom to work with people and companies around the world.</p></div>
        <div class="goal-list">
          <div><span>01</span><p>Successfully complete my university degree.</p><b>IN PROGRESS</b></div>
          <div><span>02</span><p>Build strong programming and practical development skills.</p><b>LEARNING</b></div>
          <div><span>03</span><p>Create real projects and grow a professional portfolio.</p><b>UP NEXT</b></div>
          <div><span>04</span><p>Start working as a freelancer and collaborate with clients.</p><b>FUTURE GOAL</b></div>
        </div>
      </div>
    </section>

    <section class="section contact-section" id="contact">
      <div class="section-kicker">05 / LET'S CONNECT</div>
      <div class="contact-box">
        <div><p class="eyebrow">HAVE A PROJECT OR AN IDEA?</p><h2>Let's make<br><span>something great.</span></h2><p class="contact-copy">I'm at the start of my journey and always happy to connect, learn, and explore new opportunities.</p></div>
        <div class="contact-links">
          <a href="mailto:wadee.priv7@gmail.com"><span>EMAIL</span><strong>wadee.priv7@gmail.com ↗</strong></a>
          <a href="https://wa.me/201040381805" target="_blank" rel="noopener"><span>WHATSAPP</span><strong>+20 104 038 1805 ↗</strong></a>
        </div>
      </div>
    </section>
  </main>

  <footer><a class="brand" href="#home">WH<span>.</span></a><p>© <span id="year"></span> WADEE HABOUB. BUILT WITH CURIOSITY.</p><a href="#home" class="back-top">BACK TO TOP ↑</a></footer>
  <script>
const themeToggle = document.getElementById("themeToggle");
const menuToggle = document.getElementById("menuToggle");
const nav = document.getElementById("nav");
const header = document.querySelector(".site-header");

// Theme (remembered between visits)
function setTheme(light) {
  document.body.classList.toggle("light", light);
  themeToggle.textContent = light ? "☾" : "☼";
  try { localStorage.setItem("theme", light ? "light" : "dark"); } catch (e) {}
}
try { if (localStorage.getItem("theme") === "light") setTheme(true); } catch (e) {}
themeToggle.addEventListener("click", () => setTheme(!document.body.classList.contains("light")));

// Mobile menu
menuToggle.addEventListener("click", () => {
  nav.classList.toggle("open");
  menuToggle.textContent = nav.classList.contains("open") ? "✕" : "☰";
});

document.querySelectorAll(".nav-link").forEach(link => {
  link.addEventListener("click", () => {
    nav.classList.remove("open");
    menuToggle.textContent = "☰";
    document.querySelectorAll(".nav-link").forEach(item => item.classList.remove("active"));
    link.classList.add("active");
  });
});

// Header shrinks a little after scrolling
window.addEventListener("scroll", () => {
  header.classList.toggle("scrolled", window.scrollY > 30);
}, { passive: true });

// Reveal on scroll
const io = new IntersectionObserver((entries) => {
  entries.forEach(e => {
    if (e.isIntersecting) { e.target.classList.add("in"); io.unobserve(e.target); }
  });
}, { threshold: 0.15 });
document.querySelectorAll(".reveal, .section-heading-row, .about-card, .fact-card, .skill-card, .project-card, .goal-panel, .contact-box")
  .forEach(el => { el.classList.add("rv"); io.observe(el); });

// Highlight the nav link of the section you are viewing
const links = document.querySelectorAll(".nav-link");
const spy = new IntersectionObserver((entries) => {
  entries.forEach(e => {
    if (e.isIntersecting) {
      links.forEach(l => l.classList.toggle("active", l.getAttribute("href") === "#" + e.target.id));
    }
  });
}, { rootMargin: "-45% 0px -50% 0px" });
document.querySelectorAll("main section[id]").forEach(s => spy.observe(s));

document.getElementById("year").textContent = new Date().getFullYear();

</script>
</body>
</html>
