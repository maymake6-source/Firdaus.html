<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Untuk Firdaus ❤️</title>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap');

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body{
  font-family: 'Poppins', sans-serif;
  background: linear-gradient(135deg, #000814, #001d3d, #003566, #000814);
  background-size: 400% 400%;
  color: white;
  overflow: hidden;
  animation: bgMove 15s ease infinite;
}

@keyframes bgMove {
  0% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
  100% { background-position: 0% 50%; }
}

.heart{
  position: absolute;
  top: -10px;
  color: #90e0ef;
  animation: fall linear forwards;
  pointer-events: none;
  text-shadow: 0 0 10px #48cae4;
}

@keyframes fall{
  to{
    transform: translateY(110vh) rotate(360deg);
    opacity: 0;
  }
}

.page{
  display: none;
  height: 100vh;
  padding: 20px;
  animation: fade 0.8s ease;
}

.active{
  display: flex;
  align-items: center;
  justify-content: center;
}

@keyframes fade{
  from{ opacity: 0; transform: scale(0.9); }
  to{ opacity: 1; transform: scale(1); }
}

.box{
  max-width: 600px;
  width: 90%;
  background: rgba(0, 0, 0, 0.6);
  backdrop-filter: blur(10px);
  padding: 30px 25px;
  border-radius: 20px;
  line-height: 1.9;
  box-shadow: 0 0 30px rgba(144, 224, 239, 0.3);
  border: 1px solid rgba(144, 224, 239, 0.2);
}

h1{
  text-align: center;
  color: #90e0ef;
  margin-bottom: 20px;
  font-weight: 600;
  text-shadow: 0 0 15px rgba(144, 224, 239, 0.5);
}

p {
  font-weight: 300;
  font-size: 16px;
}

button{
  margin-top: 25px;
  padding: 12px 30px;
  border: none;
  border-radius: 50px;
  background: linear-gradient(45deg, #90e0ef, #48cae4);
  color: #000814;
  font-weight: 600;
  font-family: 'Poppins', sans-serif;
  cursor: pointer;
  transition: all 0.3s ease;
  box-shadow: 0 5px 15px rgba(72, 202, 228, 0.4);
}

button:hover{
  transform: translateY(-3px);
  box-shadow: 0 8px 20px rgba(72, 202, 228, 0.6);
}

button:active{
  transform: translateY(0px);
}

.center{ text-align: center; }
.progress {
  position: fixed;
  bottom: 20px;
  left: 50%;
  transform: translateX(-50%);
  display: flex;
  gap: 8px;
}
.dot {
  width: 8px;
  height: 8px;
  border-radius: 50%;
  background: rgba(255,255,255,0.3);
  transition: all 0.3s ease;
}
.dot.active {
  background: #90e0ef;
  width: 25px;
  border-radius: 10px;
}
.music-btn {
  position: fixed;
  top: 20px;
  right: 20px;
  background: rgba(0,0,0,0.5);
  border: 1px solid #90e0ef;
  color: #90e0ef;
  width: 45px;
  height: 45px;
  border-radius: 50%;
  font-size: 20px;
}
</style>
</head>

<body>

<audio id="bgMusic" loop>
  <source src="https://www.bensound.com/bensound-music/bensound-tenderness.mp3" type="audio/mpeg">
</audio>

<button class="music-btn" onclick="toggleMusic()">🔇</button>

<!-- PAGE 1 -->
<div class="page active" id="p1">
  <div class="box">
    <h1>Selamat Ulang Tahun, Firdaus</h1>
    <p>
Hari ini hari spesial kamu... dan aku cuma mau kamu tahu satu hal: kamu berarti banget buat aku. Lebih dari yang bisa aku jelasin pake kata-kata.
    </p>
    <div class="center"><button onclick="next(2)">Buka ya ❤️</button></div>
  </div>
</div>

<!-- PAGE 2 -->
<div class="page" id="p2">
  <div class="box">
    <h1>Awal Kita</h1>
    <p>
Aku masih ingat semuanya mulai dari hal kecil. Chat pertama, canda pertama, sampai diem-dieman pertama. Nggak ada yang langsung besar, tapi entah kenapa kamu terus ada di pikiran aku sejak itu.
    </p>
    <div class="center"><button onclick="next(3)">Lanjut</button></div>
  </div>
</div>

<!-- PAGE 3 -->
<div class="page" id="p3">
  <div class="box">
    <h1>Kenapa Aku Sayang Kamu</h1>
    <p>
Aku sayang kamu bukan karena kamu sempurna. Tapi karena kamu jadi diri kamu sendiri. Cara kamu ketawa, cara kamu marah, cara kamu peduli. Itu semua... cukup buat aku. Lebih dari cukup.
    </p>
    <div class="center"><button onclick="next(4)">Lanjut</button></div>
  </div>
</div>

<!-- PAGE 4 -->
<div class="page" id="p4">
  <div class="box">
    <h1>Hal Kecil Tentang Kamu</h1>
    <p>
Aku sering mikirin kamu. Udah makan belum, lagi capek atau nggak, lagi senyum atau diam. Hal-hal kecil yang mungkin kamu gak sadar, tapi selalu mampir di kepala aku tiap hari.
    </p>
    <div class="center"><button onclick="next(5)">Lanjut</button></div>
  </div>
</div>

<!-- PAGE 5 -->
<div class="page" id="p5">
  <div class="box">
    <h1>Terima Kasih</h1>
    <p>
Makasih ya karena kamu ada. Kamu bikin hari aku lebih tenang tanpa kamu sadar. Kamu jadi alasan aku belajar jadi lebih baik. Makasih udah jadi kamu.
    </p>
    <div class="center"><button onclick="next(6)">Lanjut</button></div>
  </div>
</div>

<!-- PAGE 6 -->
<div class="page" id="p6">
  <div class="box">
    <h1>Harapan Aku Buat Kamu</h1>
    <p>
Di umur kamu yang baru ini, aku berharap semua yang kamu mau bisa tercapai. Sehat terus, rezekinya lancar, dikelilingi orang baik. Dan semoga... aku masih boleh ada di tiap cerita ulang tahun kamu berikutnya.
    </p>
    <div class="center"><button onclick="next(7)">Terakhir</button></div>
  </div>
</div>

<!-- PAGE 7 -->
<div class="page" id="p7">
  <div class="box" id="finalBox">
    <h1>Untuk Firdaus</h1>
    <p>
Aku nggak tahu masa depan kita gimana. Tapi aku senang kamu ada di hidup aku sekarang. Makasih udah lahir ke dunia. Makasih udah ketemu aku. 
<br><br>
Dan satu hal yang pasti…
    </p>
    <div class="center">
      <button onclick="finish()">Pencet ini</button>
    </div>
  </div>
</div>

<!-- Progress Dots -->
<div class="progress" id="progress"></div>

<script>
// Bikin hati jatuh
function createHearts(){
  setInterval(()=>{
    let h=document.createElement("div");
    h.classList.add("heart");
    h.innerHTML="❤";
    h.style.left=Math.random()*100+"vw";
    h.style.fontSize=(10+Math.random()*20)+"px";
    h.style.animationDuration=(3+Math.random()*5)+"s";
    document.body.appendChild(h);
    setTimeout(()=>h.remove(),8000);
  },300);
}
createHearts();

// Pindah page
let currentPage = 1;
function next(n){
  document.getElementById("p"+currentPage).classList.remove("active");
  document.getElementById("p"+n).classList.add("active");
  currentPage = n;
  updateDots();
}

// Progress dots
function createDots(){
  const progress = document.getElementById("progress");
  for(let i=1;i<=7;i++){
    let dot = document.createElement("div");
    dot.classList.add("dot");
    if(i===1) dot.classList.add("active");
    progress.appendChild(dot);
  }
}
function updateDots(){
  const dots = document.querySelectorAll(".dot");
  dots.forEach((dot, i) => {
    if(i+1 === currentPage) dot.classList.add("active");
    else dot.classList.remove("active");
  });
}
createDots();

// Musik
const music = document.getElementById("bgMusic");
let isPlaying = false;
function toggleMusic(){
  const btn = document.querySelector(".music-btn");
  if(isPlaying){
    music.pause();
    btn.innerHTML = "🔇";
  } else {
    music.play();
    btn.innerHTML = "🔊";
  }
  isPlaying = !isPlaying;
}

// Fungsi FINISH paling nendang
function finish(){
  document.getElementById("finalBox").innerHTML = `
    <h1 style="font-size: 28px;">Aku sayang kamu, Firdaus ❤️</h1>
    <p class="center" style="font-size: 18px; margin-top: 30px;">
      Dari yang selalu mikirin kamu tiap hari.<br>
      Selamat ulang tahun ya, sayang.
    </p>
    <div class="center" style="font-size: 50px; margin-top: 20px; animation: fade 1s ease;">❤️❤️❤️</div>
  `;
  
  // Hujan hati brutal
  for(let i=0;i<50;i++){
    setTimeout(() => {
      let h=document.createElement("div");
      h.classList.add("heart");
      h.innerHTML="❤";
      h.style.left=Math.random()*100+"vw";
      h.style.fontSize=(20+Math.random()*30)+"px";
      h.style.animationDuration=(2+Math.random()*3)+"s";
      document.body.appendChild(h);
      setTimeout(()=>h.remove(),5000);
    }, i * 50);
  }
  
  document.getElementById("progress").style.display = "none";
}
</script>

</body>
</html>
