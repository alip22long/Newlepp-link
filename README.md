<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Newlepp Link</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial, sans-serif;
}

body{
height:100vh;
display:flex;
justify-content:center;
align-items:center;
background:#000;
overflow:hidden;
color:white;
}

/* Background neon bergerak */

body::before{
content:"";
position:fixed;
width:200%;
height:200%;
background:linear-gradient(45deg,#00ffff,#0011ff,#00ffff,#00ffcc);
animation:bgmove 10s linear infinite;
opacity:0.15;
}

@keyframes bgmove{
0%{transform:translate(-25%,-25%)}
50%{transform:translate(-50%,-50%)}
100%{transform:translate(-25%,-25%)}
}

/* Container */

.container{
position:relative;
width:90%;
max-width:420px;
text-align:center;
padding:20px;
}

/* Profile image */

.profile{
width:120px;
border-radius:20px;
margin-bottom:15px;
box-shadow:0 0 20px #00ffff;
}

/* Name */

.name{
font-size:28px;
color:#00ffff;
margin-bottom:25px;
text-shadow:0 0 10px #00ffff,0 0 25px #00ffff;
}

/* Button */

.link{
display:block;
width:100%;
margin:15px 0;
padding:15px;
border:2px solid #00ffff;
border-radius:14px;
color:#00ffff;
text-decoration:none;
font-size:18px;
transition:0.3s;
box-shadow:0 0 10px #00ffff;
}

.link:hover{
background:#00ffff;
color:black;
box-shadow:0 0 25px #00ffff,0 0 40px #00ffff;
transform:scale(1.05);
}

/* Mobile adjustment */

@media (max-width:480px){

.name{
font-size:24px;
}

.link{
font-size:16px;
padding:14px;
}

.profile{
width:100px;
}

}

</style>
</head>

<body>

<div class="container">

<img src="clown.png" class="profile">

<div class="name">NEWLEPP</div>

<a class="link" href="https://sociabuzz.com/newlep/tribe">
💎 Donate / Sociabuzz
</a>

<a class="link" href="https://chat.whatsapp.com/Fzyso8euJDXBMlJZ6PEoxd?mode=hq2tcla">
📞 Join WhatsApp Group
</a>

</div>

</body>
</html>
