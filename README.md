<!DOCTYPE html><html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy New Year My Love ❤️</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(135deg, #2b1055, #7597de);
            color: #fff;
            text-align: center;
            overflow-x: hidden;
        }
        header {
            padding: 50px 20px;
        }
        h1 {
            font-size: 3rem;
            margin: 0;
        }
        h2 {
            font-size: 1.6rem;
            font-weight: 300;
        }
        .heart {
            font-size: 3rem;
            animation: beat 1s infinite;
        }
        @keyframes beat {
            0% { transform: scale(1); }
            50% { transform: scale(1.3); }
            100% { transform: scale(1); }
        }
        .message-box {
            max-width: 700px;
            margin: 40px auto;
            font-size: 1.3rem;
            line-height: 1.8;
            padding: 20px;
            background: rgba(255, 255, 255, 0.15);
            border-radius: 15px;
        }
        .gallery img {
            width: 250px;
            height: auto;
            border-radius: 15px;
            object-fit: cover;
            box-shadow: 0 4px 10px rgba(0,0,0,0.4);
            transition: transform 0.3s ease;
        }
        .gallery img:hover {
            transform: scale(1.05);
        }
        /* Floating Hearts */
        @keyframes floatHearts {
            0% {transform: translateY(0) scale(1); opacity:1;}
            100% {transform: translateY(-300px) scale(1.5); opacity:0;}
        }
        .heart {
            position: fixed;
            bottom: -10px;
            font-size: 25px;
            color: #ff4d6d;
            animation: floatHearts 4s linear infinite;
            z-index: 10;
        }
        /* Handwritten Font */
        @import url('https://fonts.googleapis.com/css2?family=Dancing+Script:wght@500;700&display=swap');
        #loveLetter {
            font-family: 'Dancing Script', cursive;
            font-size: 1.6rem;
        }
        /* Rose Petal Effect */
        .petal {
            position: fixed;
            top: -10px;
            width: 20px;
            height: 20px;
            background-color: #ffb3c1;
            border-radius: 50%;
            animation: fallPetals 6s linear infinite;
            opacity: 0.8;
            z-index: 5;
        }
        @keyframes fallPetals {
            0% {transform: translateY(0) translateX(0) rotate(0deg);} 
            100% {transform: translateY(700px) translateX(100px) rotate(360deg);} 
        }
        /* Fireworks */
        .firework {
            position: fixed;
            width: 5px;
            height: 5px;
            background: #fff;
            border-radius: 50%;
            pointer-events: none;
            z-index: 15;
        }
    </style>
</head>
<body><canvas class="fireworks"></canvas>

<header>
    <div class="heart">❤️</div>
    <h1>Happy New Year My Love</h1>
    <h2>2026 is ours & forever to go 💫</h2>
</header><div class="message-box">
    My dearest love, <br><br>
    I know we had our ups and downs, misunderstandings and silence... but my heart never stopped choosing you. 💖<br><br>
    Sorry... can we restart again? Not from the beginning — but from where we stopped, holding hands tighter and loving a little deeper. ✨<br><br>
    <b>Shayari:</b><br>
    <i>"Har naya saal kuch nayi kahani laata hai,<br>
    Par mera dil toh sirf teri hi nishani chhod jaata hai...<br>
    Galtiyon ke dhund se nikal kar aa jaa phir se,<br>
    Yeh dil tere bina bhi har pal tujhe hi bulaata hai..."</i><br><br>
    Let this New Year be not just a date change, but a <b>heart change</b> — a new beginning where we love better, care deeper, and never let go again. 🌙💞
</div><button id="surpriseBtn" style="margin:20px auto;display:block;padding:15px 25px;font-size:20px;background:#ff4d6d;color:white;border:none;border-radius:25px;cursor:pointer;box-shadow:0 4px 10px rgba(0,0,0,0.4);transition:0.3s;">🎁 Tap here for your Surprise</button>

<div class="slideshow-container" style="max-width:600px;margin:auto;display:none;" id="slideshow">
  <img class="slides" src="photo1.jpg" style="width:100%;border-radius:15px;display:block;">
  <img class="slides" src="photo2.jpg" style="width:100%;border-radius:15px;display:none;">
  <img class="slides" src="photo3.jpg" style="width:100%;border-radius:15px;display:none;">
  <img class="slides" src="photo4.jpg" style="width:100%;border-radius:15px;display:none;">
  <img class="slides" src="photo5.jpg" style="width:100%;border-radius:15px;display:none;">
</div><section id="loveLetter" style="display:none; max-width:700px; margin:40px auto; background:rgba(255,255,255,0.15); padding:25px; border-radius:15px; line-height:1.8; font-size:1.2rem;">
  <h2 style="text-align:center; font-size:2rem; color:#ffccd5; margin-bottom:15px;">💌 A Letter From My Heart 💌</h2>
  <p>My love,</p>
  <p>I don’t know what destiny has planned for us, but I do know that life feels more meaningful when you are a part of it. Sometimes we hurt each other without meaning to, sometimes we forget to listen, but never — not even for a second — did I forget how much your presence matters to me.</p>
  <p>I miss your smile, the way your eyes light up when you talk about something you love, and the silence between us that always felt comfortable, never empty. If this new year gives us one more chance, I want to hold your hand tighter this time — not because I fear losing you, but because I’ve learned how precious you are.</p>
  <p>Let’s write a new chapter… slow, honest, full of understanding — and may every page have your smile on it.</p>
  <p style="margin-top:20px; font-weight:bold;">Forever choosing you,<br> — Your love ❤️</p>
</section><div style="text-align:center; margin-top:20px;">
  <iframe width="300" height="200" 
    src="https://www.youtube.com/embed/EqP5dRrajn0?autoplay=1&loop=1&playlist=EqP5dRrajn0" 
    title="Until I Found You Piano Instrumental" 
    frameborder="0" allow="autoplay; encrypted-media" allowfullscreen>
  </iframe>
</div><footer>
    Made with ❤️ only for you
</footer><script>
// Floating Hearts Generator
setInterval(() => {
    let heart = document.createElement('div');
    heart.className = 'heart';
    heart.innerHTML = '❤';
    heart.style.left = Math.random() * window.innerWidth + 'px';
    document.body.appendChild(heart);
    setTimeout(() => { heart.remove(); }, 4000);
}, 800);

// Rose Petals Generator
setInterval(() => {
    let petal = document.createElement('div');
    petal.className = 'petal';
    petal.style.left = Math.random() * window.innerWidth + 'px';
    document.body.appendChild(petal);
    setTimeout(() => { petal.remove(); }, 6000);
}, 700);

// slideshow logic
let slideIndex = 0;
function showSlides(){
  let slides = document.getElementsByClassName('slides');
  for(let i=0;i<slides.length;i++){slides[i].style.display='none';}
  slideIndex++;
  if(slideIndex > slides.length){slideIndex=1;}
  slides[slideIndex-1].style.display='block';
  if(slideIndex === slides.length){
    setTimeout(()=>{
      document.getElementById('loveLetter').style.display = 'block';
      createFireworks();
    }, 2000);
  }
  setTimeout(showSlides,3000);
}

// surprise button
document.getElementById('surpriseBtn').addEventListener('click', function() {
    const slideshow = document.getElementById('slideshow');
    if(slideshow.style.display === 'none'){
        slideshow.style.display = 'block';
        this.innerText = '💖 You are My New Year Surprise 💖';
        showSlides();
    }
});

// Fireworks animation
function createFireworks(){
    for(let i=0;i<50;i++){
        let firework = document.createElement('div');
        firework.className = 'firework';
        firework.style.left = Math.random()*window.innerWidth+'px';
        firework.style.top = Math.random()*window.innerHeight+'px';
        firework.style.background = `hsl(${Math.random()*360},100%,50%)`;
        document.body.appendChild(firework);
        setTimeout(()=>firework.remove(),2000);
    }
}
</script></body>
</html>
