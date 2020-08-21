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
    animation-name: fade;
    animation-iteration-count: 1;
    animation-delay: 0s;
    animation-timing-function: linear; 
    animation-duration: 1s;

    }
     body{
    background: url(
    https://cdn-media-1.freecodecamp.org/imgr/MJAkxbh.png
    );
    }
    #b,#b1,#b2,#b3{
     animation-iteration-count: 1;
     animation-duration: 0.5s;
     animation-timing-function: linear;
     animation-delay: 0.5s;
     border-color: black;
     border-style: solid;
     border-width: 2px;

    }
    #b1{
     position: absolute;
     top: 50px;
     left: 270px;
     background-color: red;
     height: 58px;
     width: 120px;
     border-radius: 100% 100% 120% 120%;
     z-index: 0;
     animation-name: h1;

    }


    #b2{
     position: absolute;
     top: 68px;
     left: 260px;
     background-color: green;
     height: 65px;
     width: 140px;
     border-radius: 100% 100% 120% 120%;
     z-index: -1;  
     animation-name: h2;
 
    }

    #b3{
     position: absolute; 
     top: 85px;
     left: 246px;
     background-color: cyan;
     height: 75px;
     width: 170px;
     border-radius: 100% 100% 120% 120%;
     z-index: -2;
     animation-name: h3;

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
    #play,#ins,#set{
     color: #b5651d;
     background-color: white;
     font-family: monospace;
     font-size: 45px;
     font-style: italic;
     padding-right: 10px;
     padding-bottom: 55px;
     animation-name: display;
     animation-iteration-count: 1;
     animation-fill-mode: backwards;
     animation-timing-function: ; 
     animation-duration: 1s;
    }
    #play{
     position: absolute;
     top: 350px;
     left: 250px;
     width: 150px;
     height: 50px;
     animation-delay: 800ms;

    }
    #ins{
     position: absolute;
     top: 415px;
     height: 0px;
     left: 160px;
     animation-delay: 1200ms;

    }
    #set{
     height: 0px;
     position: absolute;
     top: 480px;
     left: 215px;
     animation-delay: 1.6s;
 
    }
    #play:hover,#set:hover,#ins:hover{
     transform: scale(1.1);
     background-color: #f7dbbb;

    }


    @keyframes hit{
     50%{
      top: 50px;
      left: 400px;

     }
     100%{
      top: 240px;
      left: 310px;
     height: 60px;
     width: 60px;
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
    @keyframes fade{
     0%{
      opacity: 0%;
      left: -500px;
     }
     80%{
      opacity: 70%
     }
     100%{
      opacity: 100%;
     }
    }
    @keyframes display{
     0%{
      opacity: 0%;
      left: 1000px
     }
     100%{
      opacity: 100%;
     }
    }
    

    </style>
     <body>
      <h1>Lik ch</h1>
      <div id="b"></div>
      <div id="b1"></div>
      <div id="b2"></div>
      <div id="b3"></div>
      <div class="ball"></div>

     <button id="play">PLAY</button>
     <button id="ins">INSTRUCTIONS</button>
     <button id="set">SETTINGS</button>



     </body>
    </html>
