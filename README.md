# cv
je me suis entrainer a reproduire un cv pour m'améliorera en html css 


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <title>cv</title>
</head>
<body>
  <div class="btnn1">

  <a href="debutt.html "><button class="btnn2"> back </button></a>
  </div>

    <div class="resume"> 
          <div class="left">
            <h1>Anthony<br><h4 class="Loc">Cantone</h4></h1>
            <a class="Email" href="mailto:cantoneanthony5@gmail.com" target="_blank">✉</a>
            <h4>développeur web</h4>
            <hr>
            <p>BTS Informatique</p>
            <div class="buttons">
                <a href="mailto:cantoneanthony5@gmail.com" target="_blank" class="btn fill">Gmail</a>
                <a href="https://www.instagram.com/9antho.ctn/?next=%2F" class="btn" target="_blank">Instagram</a>
              </div>
              <h2>Competence</h2>
              <ul class="listSkill">
                <li><div class="circle">
                  <div class="s90"></div>
                  <div class="s180"></div>
             
                  </div>
                  HTML</li>

                <li><div class="circle">
                    <div class="s90"></div>
                    <div class="s180"></div>
                  
                  </div>
                  CSS</li>

                  <li><div class="circle">
                    <div class="s90"></div>
            
                  </div>
                    JavaScript</li>

                    <div class="block">
                      
                              <h2>Langues</h2>
                              <ul class="listSW">
                            

                                  <li>Italien
                                    <div class="bar">
                                      <div class="value p30"></div>
                                    </div>
                                  </li>

                                  <li>Anglais
                                    <div class="bar">
                                        <div class="value p30"></div>
                                    </div>
                                  </li>
                                </ul>
                              </div>
                            </div>
                            <div class="right"> 
                              <div class="block">
                                <h2>Education  </h2>
                                <ul class="listExp">
                                <li class="year">
                                  <div class="yearBlock">
                                   
                                    <span class="yearText">2022</span>
                                    <span class="yearText">2018</span>
                                  </div>
                                  <ul>
                                    <li>


                                      lycée Aubanel Avignon  <br>
                                      bts en SIO développement web <br>
                                      
                                      
                              
                                    </li> <br>

                                    <li>

                                      Lycée Montesquieu Sorgue ,2018-2022 <br>
                                      Baccalauréat Commerce Professionnel
                            
                                    </li>
                         
                                         </ul>
                                </li>
                            </div>
                       

                                    <var></var>
                                    <h2>Experience</h2>
                                    
                                      <li>  Restaurant La bonne franquette, Apt. 2017-2022 <br>
                                             Serveur ,Aide de cuisine ,Barman        
                                             </li> <br>

                                      <li> Stage à Boulanger à Sorgue , 2021-2022 <br>
                                           Vendeur , 4 stages de 4 semaines.       </li><br>

                                      <li>  Stage à Alinea à Sorgue , 2020-2021 <br>
                                        Vendeur ,  2 stages de 4 semaines.</li>
                                    


                                      <h2>Centres Intéret</h2>
                                    
                                        <li>Informatique :Développer des sites web </li>
                                        <li>Jeux vidéos</li>
                                        <li>instrument musique : Piano</li>
                                        <li>Conduire en voiture</li>


                                
                             
                                <div class="deco">
                                    <div class="profilePhoto"><img src="https://images.pexels.com/videos/6330773/pexels-photo-6330773.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" class="PP"></img></div>


                           
                                </div>
                                <h6 class="Ver">C.Anthony CV 2023</h6>
            

    
</body>
</html>


<style>
*{
    /*   border: solid 0.25px pink; */
      font-family: Arial, "Helvetica Neue", Helvetica, sans-serif;
    /*   font-size: 14px; */
    }
    
    html body{
      padding: 50px 100px;
      display: flex;
      justify-content: center;
    /*   align-items: center; */
      background-color: #1f2333;
      color: rgba(255,255,255,0.9);
      line-height: 1.5;
      font-size: 13px;
    }
    
 
    
    a{
      color: white;
      text-decoration: none;
    } 
    
    h1{
      line-height: 120%;
      margin: 0;
    }
    
    ul{
      padding: 0;
      list-style: square;
    }
    
    h2{
      margin: 0px;
      margin-top: 25px;
      margin-bottom: 10px;
    }
    
    h2::after{
      content:"";
      display: inline-block;
      width: 60px;
      height: 5px;
      background-color: #00ffbb;
      margin-left: 10px;
    }
    
    h4{
      margin: 0;
      margin-top: 20px;
      opacity: 0.8;
    }
    
    hr{
      border: none;
      border-bottom: 4px solid #00ffbb;
      width: 40%;
      margin-left: 0;
    }
    

    .resume{
      display: flex;
      max-width: 1000px;
      min-width: 640px;
      border: solid 8px white;
      padding: 50px;
      position: relative;
      border-radius: 12px; 
      transition: 0.5s;
    }
    
    .resume:hover{
        box-shadow: 0px 0px 20px #00ffbb;
    }
    
    .resume {}
    
    .left,.right{
      padding: 15px;
    }
    
    .left{
      flex: 5;
      padding-right: 40px;
      border-right: solid 4px #00ffbb;
      padding-top: 220px;
      position: relative;
    }
    
    .right{
      flex: 7;
      padding-left: 40px;
    }
    
    .deco{
      width: 180px;
      height: 250px;
      background: linear-gradient(135deg,#00ffbb,white);
      border-radius: 0px 0 100px 100px;
      position: absolute;
      left: 50px;
      top: -10px;
      box-shadow: 3px 3px 10px black;
    }
    
    .deco .profilePhoto{
      display: block;
      position: absolute;
      overflow: hidden;
      border-radius: 50%;
      border: solid 5px #1f2333;
      width: 160px;
      height: 150px;
      bottom: 10px;
     left: 6px;
    }
    
    .deco .profilePhoto .PP{
      position: absolute;
      display: block;
      width: 169%;
      left: 50%;
      top: 50%;
      transform: translate(-50%,-50%);
    }
    
    .DBF_logo{
      position: absolute;
      width: 60px;
      right: 20px;
      top: 20px;
    }
    
    .Ver{
      position: absolute;
      bottom: 0px;
      right: 20px;
      opacity: 0.5;
      font-weight: lighter;
    }
    
    .Loc{
      font-size: 14px;
      margin: 0;
    }
    
    .Email{
      font-size: 30px;
      transition: 0.3s;
      display: inline-block;
    }
    
    .Email:hover{
      text-shadow: 0px 0px 10px white;
      transform: scale(1.5)
    }
    
  
    .listExp>li{
      display: flex;
      margin-bottom: 15px;
    }
    
    .yearBlock{
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      padding: 10px 0px;
      margin: 0;
    }
    
    .yearText{
      transform: rotate(-90deg);
      font-size: 16px;
      font-weight: bold;
      opacity: 0.6;
    }
    
    .listExp>li:nth-child(1) ul{
      border-image-slice:1;
      border-image-source: linear-gradient(to bottom,#00ffbb,#2A7B6A);
    }
    
    .listExp>li:nth-child(2) ul{
      border-image-slice:1;
      border-image-source: linear-gradient(to bottom,#2A7B6A,rgba(0,0,0,0));
    }
    
    .listExp li ul{
      padding-left: 20px;
      margin-left: 0px;
      border-left: solid 3px white;
    }
    
    .listExp li ul li {
      margin-left: 0px;
    }
    
    .block_A li{
      margin-left: 15px;
    }
    
    
    .listSkill{
      display: flex;
      flex-wrap: wrap;
  
        
    }

  
    
    .listSkill li{
      width: 50%;
      padding: 10px;
      box-sizing: border-box;

      display: flex;
      flex-direction: column;
 
      font-size: 8pt;
      line-height: 1.25;
    }
    
    
    .circle{
      width: 50px;
      aspect-ratio: 1;
      background-color: rgba(0, 255, 187, 0.4);
      border-radius: 50%;
      position: relative;
      overflow: hidden;
      margin-bottom: 15px;
    }
    
    .circle::after{
      content:"";

      display: block; 

      background-color: #1f2333;
      width: calc(100% - 20px);

      aspect-ratio: 1;
      border-radius: 50%;
      position: relative;
  
      left: 50%;
      top: 50%;
      transform: translate(-50%,-50%)

    }
    
    .s90,.s180,.s270,.s360{
      width: 50%;
      height: 50%;
      position: absolute;
      left: 50%;
      top: 0;
      background-color: #00ffbb
    }
    
    .s180{
      top: 50%;
      left: 50%;
    }
    
    .s270{
      left: 0;
      top: 50%;
      }
    
    .s360{
      top: 0;
      left: 0;
    }
    

    
    .listSW .bar{
      width: 100%;
      height: 8px;
      border: solid 3px #00ffbb;
      border-radius: 4px;
  
    }
    
    .listSW li{
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding-top: 10px;
        
    }
    
    .value{
      height: 100%;
      width: 0%;
      background-color: #00ffbb;
      
    }
    
    .value.p10{
      width: 10%;
    }
    
    .value.p20{
      width: 20%;
    }
    
    .value.p30{
      width: 30%;
    }
    
    .value.p40{
      width: 40%;
    }
    
    .value.p50{
      width: 50%;
    }
    
    .value.p60{
      width: 60%;
    }
    
    .value.p70{
      width: 70%;
    }
    
    .value.p80{
      width: 80%;
    }
    
    .value.p90{
      width: 90%;
    }
    
    .value.p100{
      width: 100%;
    }
    
    .buttons{
      display: flex;
      justify-content: space-around;
    }
    .btn{
      border: solid 2px #00ffbb;
      width: 50%;
      padding: 5px;
      margin-right: 10px;
      text-align: center;
      transition: 0.3s;
      border-radius: 5px;
    }
    
    .btns2{
      margin-top: 10px;
    }
    
    .btn.fill{
      background-color: #00ffbb;
      color: initial;
    }
    
    .btn:hover{
      background-color: rgba(255,255,255,0.2);
      box-shadow: 0px 0px 10px #00ffbb;
    }
    
    .btn.fill:hover{
      color: white;
    }



    .acpage1{
      background-color: black;
    }

    
  
  .typewriter-container {
    display: flex;
    justify-content: flex-start;
    }
  
    .typewriter{
     position: absolute;
     top: 23%;
     left: 27%;
    }
  
  
    .typewriter p {
      font-family: IBM Plex Mono, monospace;
    font-size: 45px;
    font-weight: lighter;
    overflow: hidden;
    white-space: nowrap;
    position: relative;
    animation: typing 3.5s steps(24);
    color: #ffffffbf;
    }
    .typewriter p::after {
    content: "";
    position: absolute;
    display: block;
    height: 100%;
    width: 1px;
    background: #dadada;
    right: 0;
    top: 0;
    animation: cursor 1s infinite;
    }
    
    @keyframes typing {
    from {width:0}
    to {width: 100%;}
    }
    
    @keyframes cursor {
    0% {
        opacity: 1;
    }
    50% {
        opacity: 0;
    }
    100% {
        opacity: 1;
    }
    }
    
    
    
    
    
    ::before, ::after {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    }



    .tt{
      position: absolute;
      top: 2%;
    }

    .btnn1{
      position: absolute;
      left: 2%;
    
    }
 .btnn2{
  background-color: black;
    color: white;
    padding: 10px 20px;
    border-radius: 15px;
    transition: all 0.3s ease;
    border: none;
    box-shadow:  1px 1px 1px 1px #00ffbb;
 }

 .btnn2:hover{
  background-color: rgba(255,255,255,0.2);
      box-shadow: 0px 0px 10px #00ffbb;
 }
</style>
