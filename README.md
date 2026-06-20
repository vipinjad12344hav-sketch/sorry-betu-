# sorry-betu-😭🌸
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sorry 💔</title>

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
    background:linear-gradient(135deg,#ff9aa2,#ffc3a0,#ffd1dc);
}

.card{
    width:90%;
    max-width:650px;
    background:white;
    padding:40px;
    border-radius:25px;
    text-align:center;
    box-shadow:0 15px 40px rgba(0,0,0,0.15);
}

h1{
    color:#ff4d6d;
    font-size:42px;
}

.emoji{
    font-size:55px;
    margin:15px 0;
}

.text{
    color:#555;
    font-size:18px;
    line-height:1.8;
    margin-top:10px;
}

button{
    margin-top:30px;
    padding:14px 34px;
    border:none;
    border-radius:40px;
    background:#ff4d6d;
    color:white;
    font-size:18px;
    cursor:pointer;
    transition:0.3s;
}

button:hover{
    transform:scale(1.08);
}

.hidden{
    display:none;
    margin-top:25px;
    padding:25px;
    border-radius:18px;
    background:#fff1f4;
    animation:fade 1s ease;
}

.hidden h2{
    color:#ff4d6d;
}

.hidden p{
    margin-top:15px;
    color:#444;
    line-height:1.9;
}

@keyframes fade{
from{
opacity:0;
transform:translateY(20px);
}
to{
opacity:1;
transform:translateY(0);
}
}
</style>
</head>

<body>

<div class="card">

<h1>Sorry 😔</h1>

<div class="emoji">🥺💔</div>

<p class="text">
I know you're upset with me…  
and I just wanted to say I’m really sorry.
</p>

<button onclick="showSorry()">
Click Here ❤️
</button>

<div class="hidden" id="msg">

<h2>I’m Sorry… Please Forgive Me 🥺❤️</h2>

<p>
I never wanted to hurt you.  
If my words made you sad, I truly regret it.
</p>

<p>
You matter to me more than this mistake.
I know saying sorry doesn’t fix everything instantly,
but I want you to know that I mean it from my heart.
</p>

<p>
Aage se aisa nahi hoga ❤️  
I’ll do better and be more careful because seeing you upset hurts me too.
</p>

<p>
Please forgive me when you feel ready 🌹🥺
</p>

</div>

</div>

<script>
function showSorry(){
document.getElementById("msg").style.display="block";
}
</script>

</body>
</html>
