<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    :root {
      --paper: #fffaf2;
      --ink: #5c4650;
      --pink: #f3d5dc;
      --rose: #c77f94;
      --deep-rose: #9d526d;
      --sage: #dfe8d8;
      --line: #ead8d1;
    }
    * { box-sizing: border-box; }
    body {
      margin: 0;
      min-height: 100vh;
      padding: 24px 14px 40px;
      color: var(--ink);
      font-family: Georgia, "Times New Roman", serif;
      background:
        radial-gradient(circle at 10% 15%, #ffffffa8 0 2px, transparent 3px),
        radial-gradient(circle at 85% 25%, #ffffffa8 0 2px, transparent 3px),
        linear-gradient(135deg, #f8e8e7, #f6eee2 55%, #e8eee2);
      background-size: 35px 35px, 45px 45px, auto;
    }
    button { font: inherit; cursor: pointer; }
    .journal {
      width: min(100%, 720px);
      margin: 0 auto;
      padding: clamp(18px, 5vw, 38px);
      border: 1px solid #ffffff;
      border-radius: 22px;
      background: #ffffff7a;
      box-shadow: 0 16px 45px #73525b1c;
    }
    .topline {
      display: flex;
      justify-content: space-between;
      gap: 12px;
      align-items: center;
      margin-bottom: 16px;
      font-size: 12px;
      letter-spacing: 2px;
      text-transform: uppercase;
      color: var(--deep-rose);
    }
    .book {
      position: relative;
      overflow: hidden;
      min-height: 430px;
      padding: clamp(22px, 6vw, 46px);
      border-radius: 12px 22px 22px 12px;
      border: 1px solid #f0e0d6;
      background:
        repeating-linear-gradient(to bottom, transparent 0 31px, #d6b6b62b 32px 33px),
        var(--paper);
      box-shadow: inset 8px 0 0 #eedbd5, 0 8px 22px #795e5e12;
    }
    .book::before {
      content: "";
      position: absolute;
      left: 25px;
      top: 0;
      bottom: 0;
      width: 1px;
      background: #dbaab24a;
    }
    .page { display: none; position: relative; z-index: 1; animation: fadeIn .25s ease; }
    .page.active { display: block; }
    @keyframes fadeIn { from { opacity: .35; transform: translateY(4px); } to { opacity: 1; transform: none; } }
    h1, h2 { color: var(--deep-rose); font-weight: normal; }
    h1 { font-size: clamp(34px, 7vw, 54px); line-height: 1.1; margin: 14px 0; }
    h2 { font-size: clamp(27px, 5vw, 36px); margin: 4px 0 20px; }
    p { font-size: 17px; line-height: 1.85; margin: 12px 0; }
    .small-caps { text-transform: uppercase; letter-spacing: 3px; font-size: 11px; }
    .script { font-family: "Brush Script MT", "Segoe Script", cursive; font-size: 40px; }
    .center { text-align: center; }
    .subtitle { color: #987784; font-style: italic; }
    .sticker { text-align: center; color: var(--rose); margin: 20px 0; }
    .art {
      display: block;
      width: 100%;
      max-width: 390px;
      margin: 16px auto 0;
      overflow-x: auto;
      white-space: pre;
      text-align: left;
      font-size: 7px;
      line-height: 1;
      color: #9c7180;
      font-family: monospace;
    }
    .note-card {
      margin: 16px 0;
      padding: 18px 20px;
      border: 1px dashed #d6a2b1;
      border-radius: 8px;
      background: #fff3f4d9;
      transform: rotate(-.5deg);
    }
    .list p { margin: 8px 0; padding: 7px 10px; border-bottom: 1px dashed var(--line); }
    .photo-grid { display: grid; grid-template-columns: repeat(2, minmax(0, 1fr)); gap: 14px; margin-top: 18px; }
    .polaroid { background: white; padding: 8px 8px 13px; box-shadow: 0 4px 12px #76555b20; transform: rotate(-1deg); }
    .polaroid:nth-child(even) { transform: rotate(1.5deg); }
    .photo-frame { display: grid; place-items: center; aspect-ratio: 1 / 1; overflow: hidden; background: #f6e8e7; color: #a47e87; font-size: 13px; text-align: center; }
    .photo-frame img { width: 100%; height: 100%; object-fit: cover; display: block; }
    .photo-frame input { width: 100%; font-size: 11px; }
    .caption { text-align: center; font-size: 13px; margin: 8px 0 0; }
    .wish-button, .nav-button, .music-button {
      border: 1px solid #d9a5b4;
      border-radius: 999px;
      padding: 11px 17px;
      background: #fff5f6;
      color: var(--deep-rose);
      transition: transform .15s, background .15s;
    }
    .wish-button:hover, .nav-button:hover, .music-button:hover { background: var(--pink); transform: translateY(-1px); }
    .navigation { display: flex; justify-content: space-between; align-items: center; gap: 10px; margin-top: 18px; }
    #pageCount { font-size: 13px; color: #987784; text-align: center; }
    .controls { display: flex; flex-wrap: wrap; justify-content: center; gap: 10px; margin-top: 14px; }
    .tiny { font-size: 12px; line-height: 1.5; color: #987784; }
    .wish-result { min-height: 28px; color: var(--deep-rose); font-style: italic; }
    .edit-tip { margin-top: 20px; padding: 12px 14px; background: #ffffff80; border-radius: 10px; font-size: 13px; line-height: 1.6; }
    @media (max-width: 430px) {
      .book { min-height: 420px; padding: 26px 22px 28px 32px; }
      .book::before { left: 18px; }
      p { font-size: 16px; }
      .navigation { flex-wrap: wrap; }
      #pageCount { order: 3; width: 100%; }
      .art { font-size: 5px; }
    }
  </style>
</head>
<body>
  <main class="journal">
    <div class="topline">
     
    </div>

    <section class="book" aria-live="polite">
      <!-- PAGE 1: COVER -->
      <article class="page active">
        <div class="center">
           <div class="sticker script">୨ৎ</div>
<p class="script">Happy birthday!</p>     



            <p class="bold">Ready to open it?</p>
       
      
          <div class="sticker">✧･ﾟ: *✧･ﾟ:* *:･ﾟ✧*:･ﾟ✧</div>
        </div>
      </article>

      <!-- PAGE 2 -->
      <article class="page">
        <h2>Things I Love About You ♡</h2>
        <div class="list">
          <p>♡ Kung paano ka makinig at magbigay ng advice sa ibang tao.</p>
          <p>♡ Your kindness and beautiful heart</p>
          <p>♡ Kindness, sweetnes, clinginess</p>
          <p>♡ Your laugh that makes moments better</p>
          <p>♡ All about YOU!</p>
        </div>
        <div class="sticker">────୨ৎ────</div>
        <p class="center subtitle">Never forget how lovely you are.</p>
      </article>

<!-- PAGE 3: MEMORIES -->
<article class="page">

  <h2>SNAPS</h2>
  <p style="font-size: 20px;">More memories to come ♡</p>

  <div class="photo-grid">

    <div class="Film strip style">
      <div class="photo-frame">
        <img src="/image10.jpeg"
                
     </div>

      <p class="caption" contenteditable="true">
      </p>
    </div>

    <div class="Film strip style">
      <div class="photo-frame">
        <img src="/image9.jpeg"
        
      </div>
      <p class="caption" contenteditable="true">
        
      </p>
    </div>
    
    
    <div class="Film strip style">
      <div class="photo-frame">
        <img src="/image6.jpeg" 
      </div>
      <p class="caption" contenteditable="true">
        
      </p>
    </div>
    
    <div class="Film strip style">
      <div class="photo-frame">
        <img src="/image8.jpg"
      </div>
      <p class="caption" contenteditable="true">
      
      </p>
    </div>


  </div>

</article>
      <!-- PAGE 4: SHORT NOTE, NOT A LONG LETTER -->
      <article class="page">
        <div class="note-card">
          <p class="script">just a little reminder ♡</p>
          <p>Life is not a race. </p>
          <p> Never forget how amazing you are, Maria. You deserve all the little things that make you smile. ୨ৎ</p>
          <p class="script">stay pretty, stay happy, stay you! ♡</p>
        </div>
        <div class="sticker">────୨ৎ────</div>
        <pre class="art">⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⡖⠙⡢⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣠⣿⡏⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣼⣿⡿⣿⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣀⣤⠶⠞⠛⠿⣿⣿⡿⣿⣇⡀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡾⠋⢠⠄⠀⠀⠀⠀⠈⠉⡉⠈⠛⢦⡀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⣤⠀⠀⠀⠀⠀⠻⢦⣴⣀⣀⠀⠀⠀⠀⢈⠁⣀⡄⠀⠹⣆⠀⠀⠀
⠀⠀⠀⠀⢰⠓⡄⠀⠀⠀⠀⠀⢸⡇⠉⠉⠙⠛⠛⠛⠛⠛⠉⠀⠀⠀⠹⣆⠀⠀
⢠⣒⣊⢍⣩⢙⣩⣍⡩⡇⠀⠀⢸⠃⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢻⡀⠀
⣸⣀⣈⣁⣀⣉⣀⣀⣠⣇⠀⠀⢸⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢠⡆⠘⣇⠀
⠉⠉⠉⠛⠿⠻⣯⠉⠉⠉⠀⢀⣾⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⡇⠀⢿⠀
⠀⠀⠀⠀⠀⠀⠈⢳⣄⠀⢠⡞⣿⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⡇⠀⢸⡇
⠀⠀⠀⠀⠀⠀⠀⠀⠉⠛⠋⠀⢸⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣸⠁⠀⠘⣇
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣿⠀⠀⠀⣿
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⠄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠙⠟⠁⠀⠀</pre>
      </article>

      <!-- PAGE 5: WISH -->
      <article class="page">
        <div class="center">
          <h2>Make a Wish!</h2>
          <p>Close your eyes, make a wish, and imagine blowing out your birthday candles.</p>
          <div style="font-size:64px; margin:18px 0;">🎂</div>
          <button class="wish-button" onclick="makeWish()">Make a wish ♡</button>
          <p id="wishResult" class="wish-result"></p>
          <p> I hope this new chapter bring you happiness, good health, courage, and beautiful opportunities.</p>
        </div>
      </article>


<!-- PAGE 6: MY MESSAGE -->
<article class="page">
  <h2>My Message for You ♡</h2>

  <div class="note-card">
    <div class="center">
      <div class="sticker script">Happy Birthday, Maria!</div>

      <p>Hi, Julie! Happy-happy birthday po. I hope you keep smiling, growing, and believing in yourself.</p>

      <p>Just want you to know kung gaano ako ka-thankful na naging part ka ng life ko. I'm so lucky na may friend akong puwedeng kulitin anytime, kausapin about random things, at takbuhan kapag hindi okay ang lahat.</p>

      <p>Kahit anong mangyari, I'm always rooting for you. I'll always be proud of you, kahit sa mga small achievements mo.</p>

      <p>I hope you remember na may isang tao dito na willing makinig sa'yo, umintindi sa'yo, at mag-remind sa'yo kung gaano ka ka-special.</p>

  </div>
</article>

        </div>
      </article>
      
            <!-- PAGE 7: LETTER, NOT A LONG LETTER -->
      <article class="page">
        <h2>My message for you</h2>
        <div class="note-card">
          <p>Gusto ko lang malaman mo ulit na sobrang grateful ako sa'yo, palagi Thank you for the laughs, the memories, and for being my comfort person.
          <p> I hope this new chapter of your life brings you peace, love, and all the beautiful things you deserve </p>
          <p>Thank you for being my best friend. Thank you for being YOU. I'm genuinely happy na nakilala kita.♡</p>
          <p> Sana matupad mo rin ang pangarap mo sa buhay, ang goal mo and kung ano pa man ang gusto g abutin.</p>
          <p class="script">Always remember that you are loved and appreciated by me. </p>
            <div class="sticker" style="font-size:28px;">♡ ୨ৎ ♡</div>
          <p class="script"> I love you.</p>
          <p>────୨ৎ────</p>
          


</article>
    </section>
    

    <nav class="navigation" aria-label="Journal page navigation">
      <button class="nav-button" id="backButton" type="button" onclick="changePage(-1)">← Back</button>
      <span id="pageCount">Page 1 of 6</span>
      <button class="nav-button" id="nextButton" type="button" onclick="changePage(1)">Open Me ♡</button>
    </nav>

    <div class="controls">
      <button class="music-button" id="musicButton" type="" onclick="toggleMusic()">♫ Play Music</button>
      <button class="music-button" type="button" 
    </div>

<audio id="bgm" controls>
  <source src="/hmm.mp3" type="audio/mpeg">
  
</audio>

    </div>
  </main>

  <script>
    const pages = Array.from(document.querySelectorAll(".page"));
    let currentPage = 0;

    function showPage() {
      pages.forEach((page, index) => {
        page.classList.toggle("active", index === currentPage);
      });

      const backButton = document.getElementById("backButton");
      const nextButton = document.getElementById("nextButton");

      backButton.style.visibility = currentPage === 0 ? "hidden" : "visible";

      if (currentPage === pages.length - 1) {
        nextButton.textContent = "Read Again ♡";
      } else if (currentPage === 0) {
        nextButton.textContent = "Open Me ♡";
      } else if (currentPage === pages.length - 2) {
        nextButton.textContent = "Next Page →";
      } else {
        nextButton.textContent = "Next Page →";
      }

      document.getElementById("pageCount").textContent =
        `Page ${currentPage + 1} of ${pages.length}`;
    }

    function changePage(direction) {
      currentPage += direction;
      if (currentPage >= pages.length) currentPage = 0;
      if (currentPage < 0) currentPage = 0;
      showPage();
      window.scrollTo({ top: 0, behavior: "smooth" });
    }

    function loadPhoto(input) {
      const file = input.files && input.files[0];
      if (!file) return;
      if (!file.type.startsWith("image/")) {
        alert("Please choose an image file.");
        input.value = "";
        return;
      }

      const frame = input.closest(".photo-frame");
      const reader = new FileReader();
      reader.onload = function (event) {
        frame.querySelectorAll("img, .placeholder").forEach(el => el.remove());
        const img = document.createElement("img");
        img.src = event.target.result;
        img.alt = "Selected memory photo";
        frame.prepend(img);
        input.style.display = "none";
      };
      reader.readAsDataURL(file);
    }

    function makeWish() {
      const wishes = [
        "May this year bring you little joys every day. ♡",
        "May your heart feel loved, safe, and happy. ୨ৎ",
        "May your dreams get closer one step at a time.",
        "Your wish is between you and the universe."
      ];
      const choice = wishes[Math.floor(Math.random() * wishes.length)];
      document.getElementById("wishResult").textContent = choice;
    }

    const music = document.getElementById("music");
    function toggleMusic() {
      const button = document.getElementById("musicButton");
      if (music.paused) {
        music.play().then(() => {
          button.textContent = "♫ Pause Music";
        }).catch(() => {
          alert("Add the music file named youll-be-safe-here.mp3 beside this HTML file first.");
        });
      } else {
        music.pause();
        button.textContent = "♫ Play Music";
      }
    }

    showPage();
  </script>
</body>
</html>
