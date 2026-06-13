#   
<!DOCTYPE html>  
<html lang="en">  
<head>  
<meta charset="UTF-8">  
<meta name="viewport" content="width=device-width, initial-scale=1.0">  
<title>For Simran 🤍</title>  
  
<style>  
*{  
margin:0;  
padding:0;  
box-sizing:border-box;  
font-family:'Poppins',sans-serif;  
}  
  
body{  
min-height:100vh;  
display:flex;  
justify-content:center;  
align-items:center;  
background:linear-gradient(-45deg,#ff9a9e,#fad0c4,#ffd1ff,#ffc3a0);  
background-size:400% 400%;  
animation:bg 12s ease infinite;  
overflow:hidden;  
padding:20px;  
}  
  
@keyframes bg{  
0%{background-position:0% 50%;}  
50%{background-position:100% 50%;}  
100%{background-position:0% 50%;}  
}  
  
.card{  
max-width:800px;  
background:rgba(255,255,255,0.18);  
backdrop-filter:blur(15px);  
padding:35px;  
border-radius:25px;  
text-align:center;  
color:white;  
box-shadow:0 8px 32px rgba(0,0,0,0.2);  
z-index:2;  
animation:fadeIn 1.5s ease;  
}  
  
h1{  
font-size:40px;  
margin-bottom:20px;  
}  
  
p{  
font-size:18px;  
line-height:1.8;  
margin-bottom:15px;  
}  
  
button{  
padding:14px 30px;  
font-size:18px;  
border:none;  
border-radius:12px;  
cursor:pointer;  
background:white;  
color:#ff4d6d;  
font-weight:bold;  
transition:.3s;  
margin-top:15px;  
}  
  
button:hover{  
transform:scale(1.05);  
}  
  
#thankyou{  
display:none;  
margin-top:20px;  
font-size:26px;  
font-weight:bold;  
}  
  
.heart{  
position:absolute;  
bottom:-50px;  
font-size:20px;  
animation:float linear infinite;  
color:white;  
}  
  
@keyframes float{  
0%{  
transform:translateY(0);  
opacity:1;  
}  
100%{  
transform:translateY(-110vh);  
opacity:0;  
}  
}  
  
@keyframes fadeIn{  
from{  
opacity:0;  
transform:translateY(30px);  
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
<h1>For Simran 🤍</h1>  
  
<p>  
Mujhe pata hai ki tum mujhse gussa ho, aur shayad meri kuch baaton ne tumhe ye mehsoos karaya ki main tumse sirf apna mann lagane ke liye baat karta hoon.  
</p>  
  
<p>  
Lekin sach ye nahi hai.  
</p>  
  
<p>  
Agar mujhe sirf waqt pass karna hota, to main tumhari narazgi, tumhari khushi aur tumhari feelings ki itni parwah nahi karta. Shayad main har baar apni feelings aur intentions sahi tareeke se express nahi kar paaya, lekin mera dil jaanta hai ki tum mere liye important ho.  
</p>  
  
<p>  
Mujhe sabse zyada bura is baat ka lag raha hai ki meri wajah se tumhe aisa feel hua. Main tumhe hurt karna nahi chahta tha aur na hi kabhi tumhe use kiya hai.  
</p>  
  
<p>  
Main bas itna chahta hoon ki tum meri galti ko meri niyat mat samjho. Galat main ho sakta hoon, lekin meri feelings jhoothi nahi hain.  
</p>  
  
<p>  
Main perfect nahi hoon, galtiyan mujhse bhi hoti hain, lekin tumhari feelings mere liye important hain. Main apni galti samajh chuka hoon aur uske liye dil se maafi maang raha hoon.  
</p>  
  
<p>  
Mera intention kabhi bhi tumhe upset karna nahi tha. Jo bhi hua, uska mujhe sach mein regret hai.  
</p>  
  
<p>  
Main bas itna chahta hoon ki tum jaan lo ki meri apology sachchi hai.  
</p>  
  
<p><b>I'm Truly Sorry, Simran. 🤍</b></p>  
  
<button onclick="forgive()">Forgive Me ❤️</button>  
  
<div id="thankyou">  
Thank You For Reading, Simran ❤️  
</div>  
  
</div>  
  
<script>  
function forgive(){  
document.getElementById("thankyou").style.display="block";  
}  
  
for(let i=0;i<40;i++){  
let heart=document.createElement("div");  
heart.className="heart";  
heart.innerHTML="❤";  
heart.style.left=Math.random()*100+"vw";  
heart.style.fontSize=(15+Math.random()*25)+"px";  
heart.style.animationDuration=(5+Math.random()*7)+"s";  
document.body.appendChild(heart);  
}  
</script>  
  
</body>  
</html>  
