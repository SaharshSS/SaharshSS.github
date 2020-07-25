<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  
        
        
 
  <title>Build with Saharsh</title>

  <style>
  body{
    background:rgb(166, 200, 161);
  }
.head{
background-color:green;
margin-right:50%;
font-family:sans-serif;  
}
.head:hover{
  background:steelblue;
}
  #container {
            width: px;
            margin:auto;
        }
  #jar {
    background:rgb(166, 200, 161);
    float: right;
     width: 20%;
    border-left: 3px dashed green;
    padding:6px;
   height:100%;
    overflow:auto;
   
    
  }
#clicker{
  background-color:green;
  margin-left:42%;
  
  
            
}
#clicker:hover {
                background-color: steelblue;
                color:black;
  font-family:sans-serif;
                transition: font-size 0.5s linear;
            }
#button{
  background:green;
}
#button:hover{
  background-color:steelblue;
}
#info{
  color:gray;
}
  </style>

</head>

<body>
  
  <div>
        <label>What's your name?
        <input id="name" type="text">
        </label>
        <br>
        <label>What language do you speak?
        <select id="lang">
            <option value="en">English</option>
            <option value="es">Español</option>
            <option value="fn">Française</option>
           <option value="tm">தமிழ்</option>
           <option value="cn">中文</option>
          <option value="hi">हिन्दी भाषा
          <option value="jap">日本人</option>
           <option value="ko">한국인</option>
           <option value="swa">Kiswahili</option>
        </select>
        </label>
        <br>
        <button id="button" type="button">Greet me, please!</button>
        <div id="message"></div>
    </div>
  
  <div id="jar">
    <h2 class=links link1>Links</h2>

    <p><a href="https://www.youtube.com/channel/UCoGTC716ggWiI_PpcNV8mSA" class="links"> My YouTube Channel </a></p>
    <h3>My Videos</h3>
    <p><a href="https://www.youtube.com/channel/UCoGTC716ggWiI_PpcNV8mSA" class="links"> Lego Drill </a></p>
    <p><a href="https://www.youtube.com/channel/UCoGTC716ggWiI_PpcNV8mSA" class="links"> Hummingbird Carousel </a></p>
    <p><a href="https://www.youtube.com/channel/UCoGTC716ggWiI_PpcNV8mSA" class="links"> Lego RC car with Motorized steering </a></p>
    <p><a href="https://www.youtube.com/channel/UCoGTC716ggWiI_PpcNV8mSA" class="links"> Lego Wind Machines </a></p>
    <p><a href="https://www.youtube.com/channel/UCoGTC716ggWiI_PpcNV8mSA" class="links"> Trebuchet </a></p>
    <p><a href="https://www.youtube.com/channel/UCoGTC716ggWiI_PpcNV8mSA" class="links"> Lego Spirograph </a></p>
    <p>And Much More...</p>
    <h3>Set Reviews</h3>
  </div>
  <h1>Build With Saharsh</h1>
  <div id=container>
    <img id = "image" src="https://https://www.en.wikipedia.org/wiki/Lego" alt="lego canvas">

    <h1 class="head">About Me</h1>
    <p class="aboutMe">Welcome to Build with Saharsh! This is where I would like to inspire everyone to follow their passion of building cool things.</p>
    <iframe src="https://www.youtube.com/channel/UCoGTC716ggWiI_PpcNV8mSA" title="My Channel"></iframe>
    <h1 class="head">Video Recomendations</h1>
        <button id="clicker">Recomend Anything</button>

  </div>
  <div id = "clicky"></div>
  
  
    <div id="info"></div>
 
  <script>var buildEl = document.getElementById("clicker");
var onBuildClick = function(){
buildEl.innerHTML = "Send Recommendation to emailsaharsh@gmail.com";}
buildEl.addEventListener("click", onBuildClick);

//Form.multilingualGreeting
// Step 1: Find the element we want the event on
  var button = document.getElementById("button");
  // Step 2: Define the event listener function
     
  var onButtonClick = function() {
    var name = document.getElementById("name").value;
    var lang = document.getElementById("lang").value;
    var greeting;
    if (lang === "es") {
        greeting = "Hola, " + name + ". Gracias por visitar Construir con Saharsh! ";
    } else if (lang === "fn") {
        greeting = "Bonjour, " + name + "Merci d'avoir visité Build with Saharsh! ";
    } else if (lang === "en") {
        greeting = "Hello, " + name + ". Thank you for visiting Build with Saharsh! ";
    }else if (lang === "tm") {
        greeting = "வணக்கம், " + name + ". பில்ட் வித் சஹர்ஷைப் பார்வையிட்டதற்கு நன்றி! ";
    }else if (lang === "cn") {
        greeting = "你好, " + name + ". 感谢您访问Build with Saharsh! ";
    }else if (lang === "hi") {
        greeting = "नमस्ते, " + name + ". सहर्ष के साथ बिल्ड में आने के लिए धन्यवाद! ";
    }else if (lang === "jap") {
        greeting = "こんにちは, " + name + ". Build with Saharshにアクセスしていただきありがとうございます! ";
    }else if (lang === "swa") {
        greeting = "Hujambo, " + name + ". Asante kwa kutembelea Jenga na Saharsh! ";
    }else if (lang === "ko") {
        greeting = "여보세요, " + name + ". Saharsh로 빌드를 방문해 주셔서 감사합니다! ";
    }
    document.getElementById("message").textContent += greeting;  
  };
  // Step 3: Attach event listener to element
  button.addEventListener("click", onButtonClick); 


console.log(infoDiv);
var infoDiv = document.getElementById("info");
infoDiv.textContent = "HI iaa";
infoDiv.textContent = "Your current user agent is " + window.navigator.userAgent;

console.log(infoDiv);


</script>
    <script>
slideShow(document.getElementById("slideshow"));
    </script>
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.4/jquery.min.js"></script>
  <script>
var headingFromJ = $("#button"); // jQuery collection
headingFromJ.html("Greet <strong>Me</strong>!");
    
  </script>
  </body> </html>
