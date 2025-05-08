<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>To My Deadly Gergeous Sayaaang</title>
  <link href="https://fonts.googleapis.com/css2?family=Quicksand:wght@400;600&display=swap" rel="stylesheet"/>
  <style>
    body {
      background: linear-gradient(to right, #ffdce0, #ffe6f0);
      font-family: 'Quicksand', sans-serif;
      text-align: center;
      padding: 40px;
      color: #5a2a2a;
      overflow: hidden;
    }

    .container {
      max-width: 600px;
      margin: 0 auto;
      background: #fff0f5;
      padding: 30px;
      border-radius: 25px;
      box-shadow: 0 10px 25px rgba(255, 182, 193, 0.4);
      border: 2px solid #ffccd5;
      position: relative;
      z-index: 1;
    }

    h1 {
      font-size: 2.2em;
      color: #d63384;
      margin-bottom: 15px;
    }

    #pembuka {
      font-size: 1.2em;
      color: #6d214f;
    }

    button {
      margin: 10px;
      padding: 12px 28px;
      font-size: 1em;
      background: #ffb6c1;
      color: #fff;
      border: none;
      border-radius: 20px;
      cursor: pointer;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      transition: background 0.3s ease, transform 0.2s ease;
    }

    button:hover {
      background: #ff80ab;
      transform: scale(1.05);
    }

    #surat {
      display: none;
      margin-top: 25px;
    }

    #isiSurat {
      white-space: pre-line;
      text-align: left;
      color: #6d214f;
      font-size: 1.2em;
      line-height: 1.6em;
      margin-top: 15px;
    }

    .love {
      position: fixed;
      top: -20px;
      font-size: 20px;
      color: #ff5e78;
      animation: fall 5s linear infinite;
      z-index: 0;
    }

    @keyframes fall {
      0% { transform: translateY(-20px) rotate(0deg); opacity: 1; }
      100% { transform: translateY(100vh) rotate(360deg); opacity: 0; }
    }
  </style>
</head>
<body>

  <div class="container">
    <h1>To My Deadly Gergeous Sayaaang 💘</h1>
    <p id="pembuka">HAAAII SAYAAANG, apa kabaar :D</p>
    <button onclick="tampilkanSurat()">Klik untuk buka suratnya 🥺</button>

    <div id="surat">
      <div id="isiSurat"></div>

      <p><strong>sayaaang kalaau maau maafin akuuu, akuu kasiiikkk sesuatuu deeeh :D</strong></p>

      <button onclick="dimaafin()">nawfaal maafin fikaa cantiik💖</button>
      <button onclick="masihKesel()">masih kesel 😤</button>
    </div>
  </div>

  <!-- Musik YouTube (autoplay) -->
  <iframe id="musik" width="0" height="0" src="https://www.youtube.com/embed/3eT464L1YRA?autoplay=1&loop=1&playlist=3eT464L1YRA" frameborder="0" allow="autoplay" allowfullscreen></iframe>

  <script>
    function tampilkanSurat() {
      document.getElementById("surat").style.display = "block";
      ketikSurat();
    }

    const isi = `im heres just want to let u know thaat. lately, i feel guilty of what ive done to u  
and to be real I really am sorry sayaaang. especially after everything that u do for me :(.  
Im so grateful to have u in my life, more than u ever imagined.  
im sorry if i dont show u that side of me,  
im sorry that i sometimes be so cranky :(  
maafin aku yaaa sayaang :(  
aku haraap we can be..... (kamu maunyaaa apaaah :D)  
SAYAAAANGG, kalaau kamu masii maraaa bilaaang yaaahh.  
jangan dipendam sayaaaang :(`;

    function ketikSurat() {
      const elemen = document.getElementById("isiSurat");
      elemen.innerHTML = "";
      let i = 0;

      const interval = setInterval(() => {
        elemen.textContent += isi.charAt(i);
        i++;
        if (i >= isi.length) {
          clearInterval(interval);
        }
      }, 40);
    }

    function dimaafin() {
      alert("YAYYYY! baaikknyaaah sayaangku iniih🥹💖 nantiiik aku kasiiik apaapuun yaang sayaang mau deeehh 🤗");
    }

    function masihKesel() {
      alert("yaaah, sayaangkuu masii keseel, akuu ngertiii koo sayaang😭 tapi jangan dipendam yaa, cerita ke aku pelan-pelan 🩷");
    }

    // Love animation
    setInterval(() => {
      const love = document.createElement("div");
      love.className = "love";
      love.style.left = Math.random() * window.innerWidth + "px";
      love.innerText = "💗";
      document.body.appendChild(love);
      setTimeout(() => love.remove(), 5000);
    }, 300);
  </script>

</body>
</html>
