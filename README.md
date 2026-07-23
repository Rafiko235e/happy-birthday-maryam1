<!DOCTYPE html>
<html>
<head>

<meta charset="UTF-8">
<title>Happy Birthday MERIEM ❤️</title>

<link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

<style>

body{
margin:0;
height:100vh;
display:flex;
justify-content:center;
align-items:center;
overflow:hidden;
background:linear-gradient(135deg,#ff9a9e,#fad0c4);
font-family:'Poppins',sans-serif;
}

.card{
background:white;
width:85%;
max-width:600px;
padding:35px;
border-radius:30px;
text-align:center;
box-shadow:0 0 40px #ff6699;
animation:show 2s;
}

h1{
font-family:'Great Vibes',cursive;
font-size:80px;
color:#ff3366;
margin:5px;
}

h2{
color:#ff4d79;
}

p{
font-size:18px;
line-height:1.8;
color:#444;
}

.heart{
font-size:55px;
animation:beat 1s infinite;
}

button{

background:#ff3366;
color:white;
border:none;
padding:15px 30px;
border-radius:30px;
font-size:18px;
cursor:pointer;
margin-top:20px;
box-shadow:0 5px 20px #ff99bb;

}

button:hover{
transform:scale(1.1);
}

#secret{

display:none;
margin-top:25px;
font-size:20px;
color:#ff3366;
font-weight:bold;
animation:fade 2s;

}


@keyframes beat{
50%{transform:scale(1.3);}
}

@keyframes show{
from{
opacity:0;
transform:translateY(50px);
}
to{
opacity:1;
}
}

@keyframes fade{
from{
opacity:0;
}
to{
opacity:1;
}
}


.fall{

position:absolute;
top:-50px;
font-size:25px;
animation:fall 6s linear infinite;

}


@keyframes fall{

to{
transform:translateY(110vh);
}

}


</style>

</head>


<body>


<audio autoplay loop>

<source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-2.mp3">

</audio>



<div class="card">


<div class="heart">❤️</div>


<h1>MERIEM</h1>

<h2>Happy Birthday 🎂</h2>


<p>

Today is a very special day because it celebrates someone who means a lot to me.

<br><br>

Having you in my life is one of the most beautiful gifts I could ever have.  
Your smile, your kindness, and your presence make my days better.

<br><br>

I hope your life is always filled with happiness, success and beautiful moments.

</p>



<button onclick="showMessage()">
Click here MERIEM ❤️
</button>


<div id="secret">

💌 My secret message 💌
<br><br>

Meriem, I just want you to know that you are truly special to me.  
You brought a beautiful feeling into my life that I will always appreciate.

Thank you for being you.  
I hope I can always see you happy and smiling.

You deserve all the love and happiness in the world. ❤️

</div>


</div>



<script>

function showMessage(){

document.getElementById("secret").style.display="block";

}


for(let i=0;i<40;i++){

let h=document.createElement("div");

h.className="fall";

h.innerHTML="❤️";

h.style.left=Math.random()*100+"%";

h.style.animationDelay=Math.random()*5+"s";

document.body.appendChild(h);

}

</script>


</body>
</html># happy-birthday-maryam1
