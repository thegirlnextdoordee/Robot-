# Robot-

<!DOCTYPE html >
   <html>
     <head> <title> Android Bot </title>
       <! --creating an android bot --> </head>
     <body>
       <style>
         body {
           text-align:  center;
         }
        div {
         background-color: #512a9b;
         }
         .head {
          height : 350px;
           width: 600px;
           border-radius: 50% 50% 0% 0%;
           position: absolute;
           top: 30px;
           right: 200px;
         }
         .right-eye {
          height: 40px;
           width: 60px;
           border-radius: 100% 100% 100% 100%;
           border-style: solid;
           position: absolute;
           background-color: white !important;
           right: 350px;
           top: 150px;
           animation-name: why;
           animation-duration: 2s;
           animation-iteration-count: infinite;
         }
         .mouth {
           height: 50px;
           width: 90px;
            border-radius: 0% 0% 100% 100%;
           position: absolute;
           left: 430px;
           top: 250px;
           background-color: white !important;
           animation-name: black;
           animation-duration: 5s;
         }
         .left-eye  {
           height: 40px;
           width: 60px;
           border-radius: 100% 100% 100% 100%;
           border-style: solid;
           position: absolute;
           background-color: white !important;
           left: 300px;
           top: 150px;
           animation-name: more;
           animation-duration: 2s;
           animation-iteration-count: infinite;
         }
         .right-hand {
          height: 400px;
           width: 150px;
           border-radius: 30% 30% 30% 30%;
           position: absolute;
           right: 25px;
           top: 420px;
           animation-name: move;
           animation-duration: 2s;
           animation-iteration-count: infinite;
           animation-timing-function: linear;
           
         }
         .left-hand {
           height: 400px;
           width: 150px;
           border-radius: 30% 30% 30% 30%;
           position: absolute;
           top: 420px;
           left: 10px;
           animation-name: color;
           animation-duration: 2s;
           animation-iteration-count: infinite;
           animation-timing-function: linear;
         }
         .body {
           height: 500px;
           width: 600px;
           border-radius: 0% 0% 10% 10%;
           position: absolute;
           right: 200px;
           top: 400px;
           animation-name: green;
           animation-duration: 5s;
         }
         .right-leg  {
          height: 300px;
           width: 150px;
           border-radius: 0% 0% 30% 30%;
             position: absolute;
           left: 260px;
           top: 800px;
           animation-name: bezier;
           animation-duration: 2s;
           animation-iteration-count: infinite;
           animation-timing-function: linear;
         }
         .left-leg {
           height: 300px;
           width: 150px;
           border-radius: 0% 0% 30% 30%;
           position: absolute;
           right: 290px;
           top: 800px;
           animation-name: cloth;
           animation-duration: 2s;
           animation-iteration-count: infinite;
           animation-timing-function: linear;
         }
         .right-horn {
           height: 100px;
           width: 20px;
             border-radius: 20% 20% 0% 0%;
           position: absolute;
           right: 290px;
           top:0px;
           animation-name: purple;
           animation-duration: 2s;
           animation-iteration-count: infinite;
           animation-timing-function: linear;
         }
         .left-horn {
           height: 100px;
           width:20px;
           border-radius: 20% 20% 0% 0%; 
           position: absolute;
           left: 250px;
           top: 0px;
           animation-name: brown;
           animation-duration: 2s;
           animation-iteration-count: infinite;
           animation-timing-function: linear;
         }
         @keyframes move {
           0% {
             
             top: 270px;
           }
           100% {
             
             bottom: 240px;
           }
         }
             @keyframes color {
               0% {
                 bottom: 240px;
               }
               100% {
                 top: 270px;
               }
         }
         @keyframes bezier {
           0% {
             top: 700px;
           }
           100% {
             bottom: 300px;
           }
         }
         @keyframes cloth {
           0% {
             bottom: 300px;
           }
           100% {
             top: 700px;
           }
         }
         @keyframes why {
           20% {
             transform: scale(0.5);
           }
         }
         @keyframes more {
             100% {
             transform: scale(0.5);
           }
         }
         @keyframes brown {
           0% {
             top: 50px;
           }
           100% {
             bottom: 50px;
           }
         }
         @keyframes purple {
           0% {
           bottom: 50px;
         }
           100% {
             top: 50px;
           }
         } 
       </style>
        
       <div class="head">    </div>
       
       <div class="right-eye"> </div>
       
       <div class="left-eye"> </div>
       
       <div class="body"> </div>
       
       <div class="right-hand"> </div>
       
       <div class="left-hand"> </div>
       
       <div class="right-leg"> </div>
       
       <div class="left-leg"> </div>
       
       <div class="right-horn"> </div>
       
       <div class="left-horn">  </div>
         
       <div class="mouth"> </div>
       
     </body>
</html>
