# Horse-Racing
Horse Racing project using only HTML and CSS

<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="stylesheet" href="horse racing.css">
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Horse Racing </title>
</head>
<body>
  <style>
  body{
  background-color: #596E5C;
}

#header{
 font-family: monospace;
 font-size: 270%;
 display: flex;
 justify-content: center;
 margin: 0 0 1.7em 0;
 color: #019875 ;
 text-shadow: -2px -2px #002408;
 
}
#track{

    background: url(https://t4.ftcdn.net/jpg/02/79/76/03/240_F_279760385_TMIljsgKvdgTFjRfefxKIHhqAqd1qT39.jpg);
    background-repeat: no-repeat;
    background-size: 100% 100%;
   
}
div{
position: relative;
display: flex;
flex-flow: column;
align-self: start;
height: 20vh;
width: 25vh;
z-index: 2;
animation-name: horse;
animation-duration: 5s;
animation-iteration-count: infinite;

}
#horse1{
animation-timing-function: ease;
}
#horse2{
animation-timing-function: ease-in;
}
#horse3{
animation-timing-function: ease-out;
}
#horse4{
animation-timing-function:ease-in-out;
}
#horse5{
animation-timing-function: linear;
}
@keyframes horse{
    0%{
        left: 0%;
    }
    
    80%{
        left: 80%;
    }
}
#contact{
    margin: 20% 0 0 45%;
}
#caption{
  font-family: monospace;
  font-size: 160%;
  margin: 0 7em 0 -2.8em;
}
#github-img{
  height: 7%;
  width: 16%;
  display: flex;
  justify-content: center;
  transition: all 0.4s linear;
}
#github-img:hover{
  transform: translate3d(10px, 0, 0);
  
}
#footer{
 background-color: #002408;
 color: #aecac4;
 margin: 4em 1em 1em 0em;
 padding: 0.8em 0.5em 1em 0em;
 text-align: right;
 width: 100%;
 
}
  </style>
    <section id="header">
  <h1> Horse Racing </h1>
    </section>
<section id="track">
    <section class="horsee">
<div id="horse1"><img src="https://i.pinimg.com/originals/80/b9/f4/80b9f49b3131c76e567945dc9bd14166.gif" class="horsee" alt="horse1"></div>
<div id="horse2"><img src="https://i.pinimg.com/originals/80/b9/f4/80b9f49b3131c76e567945dc9bd14166.gif" class="horsee" alt="horse2"></div>
<div id="horse3"><img src="https://i.pinimg.com/originals/80/b9/f4/80b9f49b3131c76e567945dc9bd14166.gif" class="horsee" alt="horse3"></div>
<div id="horse4"><img src="https://i.pinimg.com/originals/80/b9/f4/80b9f49b3131c76e567945dc9bd14166.gif" class="horsee" alt="horse4"></div>
<div id="horse5"><img src="https://i.pinimg.com/originals/80/b9/f4/80b9f49b3131c76e567945dc9bd14166.gif" class="horsee" alt="horse5"></div>
    </section>
</section>
<section id="contact">
    <p id="caption"> Follow me on my GitHub </p>
    <a href="https://github.com/Jaredd1" target="_blank" id="profile-link">
      <img id="github-img" src="https://pngimg.com/uploads/github/github_PNG15.png" alt="Github IMG"></a>
    
    </a>
  </section>
    <section id="footer">
Copyright &copy; 2021 Jared Ramon Elizan 
    </section>
  
</body>
</html>
