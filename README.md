<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Just One Question 💍</title>

<style>
body{
  margin:0;
  font-family:'Arial', sans-serif;
  background:linear-gradient(135deg,#ff758c,#ff7eb3);
  display:flex;
  justify-content:center;
  align-items:center;
  min-height:100vh;
  overflow:hidden;
}

.box{
  background:white;
  padding:25px;
  border-radius:25px;
  width:95%;
  max-width:500px;
  box-shadow:0 15px 40px rgba(0,0,0,0.3);
  animation:fadeIn 1.2s ease;
}

@keyframes fadeIn{
  from{opacity:0;transform:scale(0.9);}
  to{opacity:1;transform:scale(1);}
}

h1{
  color:#ff4d6d;
  text-align:center;
  animation:glow 2s infinite alternate;
}

@keyframes glow{
  from{text-shadow:0 0 5px #ff4d6d;}
  to{text-shadow:0 0 18px #ff4d6d;}
}

p{
  text-align:center;
  color:#555;
  font-size:15px;
}

iframe{
  width:100%;
  height:520px;
  border:none;
  margin-top:15px;
}

.heart{
  position:absolute;
  font-size:22px;
  animation:float 6s linear infinite;
}

@keyframes float{
  0%{transform:translateY(0);opacity:1;}
  100%{transform:translateY(-100vh);opacity:0;}
}
</style>
</head>

<body>

<div class="box">
  <h1>Shruti, I Love You ❤️</h1>
  <p>
    From the day you came into my life,<br>
    everything became more beautiful 💕<br><br>
    I don’t want to imagine my future without you…
  </p>

  <h2 style="text-align:center;color:#ff4d6d;">Will you be mine forever? 💍</h2>

  <!-- GOOGLE FORM -->
  <iframe src="PASTE_FORM_LINK_HERE"></iframe>
</div>

<script>
// Floating hearts
setInterval(()=>{
  const heart=document.createElement("div");
  heart.className="heart";
  heart.innerHTML="❤️";
  heart.style.left=Math.random()*100+"vw";
  heart.style.bottom="0";
  document.body.appendChild(heart);
  setTimeout(()=>heart.remove(),6000);
},300);
</script>

</body>
</html>
