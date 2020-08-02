      <!DOCTYPE html>
           <html>
        <body>
    <style>
    h1{
    position: absolute;
    top: 150px;
    left:190px;
    color: #fca500;
    font-family: fantasy;
    font-size: 100px;
    font-style: italic;
    z-index: 1;

    }
    body{
    background: url(
      https://cdn-media-1.freecodecamp.org/imgr/MJAkxbh.png
    );
    }
    #b{
    position:absolute;
    top: 51px;
    left: 271px;
    background-color: red;
    height: 32px;
    width: 117px;
    border-radius: 95% 95% 120% 120%;
    border-color: black;
    border-style: solid;
    border-width: 2px;
    z-index: 1;
    animation-name: h1;
    animation-iteration-count: 1;
    animation-duration: 0.5s;
    animation-timing-function: linear;
    animation-delay: 0.5s;
    
    }
    .b1{
    position: absolute;
    top: 50px;
    left: 270px;
    background-color: red;
    height: 58px;
    width: 120px;
    border-radius: 100% 100% 120% 120%;
    border-color: black;
    border-style: solid;
    border-width: 2px;
    z-index: 0;
    animation-name: h1;
    animation-iteration-count: 1 ;
    animation-duration: 0.5s;
    animation-timing-function: linear;
    animation-delay: 0.5s;
    
  }
  

    #b2{
    position: absolute;
    top: 68px;
    left: 260px;
    background-color: green;
    height: 65px;
    width: 140px;
    border-radius: 100% 100% 120% 120%;
    border-color: black;
    border-style: solid;
    border-width: 2px;
    z-index: -1;  
    animation-name: h2;
    animation-iteration-count: 1;
    animation-duration: 0.5s;
    animation-timing-function: linear;
    animation-delay: 0.5s;
    }

    #b3{
    position: absolute;
    top: 85px;
    left: 246px;
    background-color: cyan;
    height: 75px;
    width: 170px;
    border-radius: 100% 100% 120% 120%;
    border-color: black;
    border-style: solid;
    border-width: 2px;
    z-index: -2;
    animation-name: h3;
    animation-iteration-count: 1;
    animation-duration: 0.5s;
    animation-timing-function: linear;
    animation-delay: 0.5s;

    }
    .ball{
    position: absolute;
    top: 5px;
    left: 820px;
    background-color: #76ff03;
    height: 45px;
    width: 45px;
    border-radius: 50%;
    border-color: black;
    border-style: solid;
    border-width: 2px;
    animation-name: hit;
    animation-iteration-count: 1;
    animation-duration: 1s;
    animation-timing-function: linear;
    animation-fill-mode: forwards;
    
    }


    @keyframes hit{
    50%{
    top: 50px;
    left: 400px;

    }
    100%{
    top: 250px;
    left: 321px;
    }

    }
    @keyframes h1{
     100%{
    top: 0px;
    left: 50px;

    }
    }
    @keyframes h2{
 
    100%{
    top: 50px;
    left: 30px;

     }
    }
    @keyframes h3{
      100%{
    top: 85px;
    left: 150px;

    }
    }



     </style>
    <body>
    <h1>Lik ch</h1>
    <div id="b"></div>
    <div class="b1">
    
    </div>
  
    <div id="b2"></div>
    <div id="b3"></div>
    <div class="ball"></div>

    </body>
    
    
    
    
    
    
    
    
    
    
    
    
    
    </body>

  

    </html>
