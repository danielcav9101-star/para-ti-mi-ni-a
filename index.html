<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Para mi niña bella 🎀</title>
  <style>
    :root{
      --bg:#ffe6f0;
      --accent:#ff8fb1;
      --white:#ffffff;
      --pink-light:#fff4f8;
      --kitty-pink:#ffb6c1;
    }
    html,body{
      height:100%;
      margin:0;
      font-family:'Poppins', 'Comic Sans MS', Arial, sans-serif;
      background:var(--bg);
      overflow:hidden;
    }
    .container{
      min-height:100vh;
      display:flex;
      flex-direction:column;
      align-items:center;
      justify-content:center;
      text-align:center;
      padding:30px;
      background:
        radial-gradient(circle at 10% 20%, rgba(255,255,255,0.3), transparent 15%),
        radial-gradient(circle at 80% 90%, rgba(255,255,255,0.2), transparent 15%),
        var(--bg);
      position:relative;
      z-index:2;
    }
    h1{
      color:var(--accent);
      font-size:28px;
      margin-bottom:8px;
    }
    p{
      color:#a64b6a;
      font-weight:500;
    }

    .card{
      background:rgba(255,255,255,0.7);
      backdrop-filter:blur(8px);
      border:2px solid var(--kitty-pink);
      border-radius:20px;
      padding:25px;
      max-width:650px;
      box-shadow:0 10px 30px rgba(0,0,0,0.1);
    }

    #messageBox{
      min-height:100px;
      font-size:20px;
      color:#5a2440;
      margin-bottom:20px;
      padding:15px;
      background:var(--pink-light);
      border-radius:12px;
      box-shadow:inset 0 0 10px rgba(255,200,220,0.4);
    }

    .btn{
      background:linear-gradient(90deg,var(--accent),#ff6b9a);
      color:white;
      border:none;
      padding:12px 22px;
      border-radius:999px;
      font-weight:bold;
      cursor:pointer;
      transition:transform .12s ease;
      box-shadow:0 6px 20px rgba(255,100,150,0.3);
    }
    .btn:active{transform:scale(.97);}
    footer{
      margin-top:15px;
      font-size:13px;
      color:#8b5a6b;
      opacity:0.8;
    }

    canvas#hearts{
      position:fixed;
      inset:0;
      pointer-events:none;
      z-index:0;
    }

    @keyframes fadeIn {
      from{opacity:0; transform:translateY(8px);}
      to{opacity:1; transform:translateY(0);}
    }
    .fade-in{animation:fadeIn .4s ease;}
  </style>
</head>
<body>
  <canvas id="hearts"></canvas>

  <div class="container">
    <main class="card">
      <div id="messageBox" class="fade-in">
        Hola mi niña bella, este pequeño detalle es solo para ti 💗
      </div>

      <div style="display:flex;gap:10px;justify-content:center;flex-wrap:wrap;">
        <button id="nextBtn" class="btn">Siguiente</button>
      </div>
    </main>

    <footer>Diseñado con ternura y un toque Hello Kitty 🎀</footer>
  </div>

  <script>
    const mensajes = [
      "Eres mi persona favorita",
      "Siempre estaré para ti",
      "Te quiero demasiado, mi niña bella",
      "Tu presencia me da mucha tranquilidad",
      "No olvides lo valiosa que eres para mí"
    ];

    const finalTitle = "Mi Hello Kitty especial";
    const finalSubtitle = "Gracias por llenar mi mundo de ternura";

    const textEl = document.getElementById('messageBox');
    const nextBtn = document.getElementById('nextBtn');

    let index = -1;

    nextBtn.addEventListener('click', showNext);

    function showNext(){
      index++;
      if(index < mensajes.length){
        fadeText(mensajes[index]);
        popHeart();
      } else if(index === mensajes.length){
        showFinal();
      }
    }

    function showFinal(){
      textEl.innerHTML = `<strong>${finalTitle}</strong><div style="margin-top:10px;font-size:0.95em;">${finalSubtitle}</div>`;
      textEl.classList.add('fade-in');
      nextBtn.style.display = "none";
      burstHearts(25);
    }

    function fadeText(msg){
      textEl.classList.remove('fade-in');
      void textEl.offsetWidth;
      textEl.textContent = msg;
      textEl.classList.add('fade-in');
    }

    // Hearts animation
    const canvas = document.getElementById('hearts');
    const ctx = canvas.getContext('2d');
    let W = canvas.width = innerWidth;
    let H = canvas.height = innerHeight;
    window.addEventListener('resize',()=>{W=canvas.width=innerWidth;H=canvas.height=innerHeight;});

    class Heart{
      constructor(){this.reset();}
      reset(){
        this.x=Math.random()*W;
        this.y=H+Math.random()*200;
        this.size=6+Math.random()*20;
        this.vy=0.6+Math.random()*1.5;
        this.vx=-0.5+Math.random();
        this.opacity=0.5+Math.random()*0.5;
        this.color=`rgba(255,182,193,${this.opacity})`;
      }
      update(){this.y-=this.vy;this.x+=this.vx;if(this.y<-50)this.reset();}
      draw(){
        ctx.beginPath();
        const s=this.size;
        ctx.moveTo(this.x,this.y+s/4);
        ctx.bezierCurveTo(this.x,this.y,this.x-s/2,this.y,this.x-s/2,this.y+s/4);
        ctx.bezierCurveTo(this.x-s/2,this.y+s/2,this.x,this.y+s/1.2,this.x,this.y+s);
        ctx.bezierCurveTo(this.x,this.y+s/1.2,this.x+s/2,this.y+s/2,this.x+s/2,this.y+s/4);
        ctx.bezierCurveTo(this.x+s/2,this.y,this.x,this.y,this.x,this.y+s/4);
        ctx.fillStyle=this.color;
        ctx.fill();
      }
    }

    const hearts=[];
    for(let i=0;i<25;i++)hearts.push(new Heart());
    function animate(){
      ctx.clearRect(0,0,W,H);
      hearts.forEach(h=>{h.update();h.draw();});
      requestAnimationFrame(animate);
    }
    animate();

    function popHeart(){
      const h=new Heart();
      h.x=W/2+(Math.random()-0.5)*200;
      h.y=H/2;
      hearts.push(h);
      setTimeout(()=>{const i=hearts.indexOf(h);if(i>-1)hearts.splice(i,1);},1500);
    }
    function burstHearts(count){for(let i=0;i<count;i++){setTimeout(popHeart,i*30);}}
  </script>
</body>
</html>
