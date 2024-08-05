# Personalportfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>


    <style>
        *{
            font-family: sans-serif;
        }
    #a{
        width:100%;
        height:90px;
        background-color:black;
        border:2px solid;
        color:white;
        text-align: right;
        font-size: 25px;
        word-spacing:30px;
        padding-top:25px;
        padding-right: 35px;
        
    }

    a:link{
        text-decoration: none;
        color:white;
    }
     
    a:hover{
         color:white;
         text-decoration:underline;
    }
    #login{
        border:2px solid white;
        width:10%;
        height: 55px;
        padding :15px 20px;
        font-size: 20px;
        border-radius: 10px;
        text-decoration: none;
        outline :none;
    }
     
     #login{
        transition-duration:0.4s ;
     }

     #login:hover{
        background-color:rgb(192, 235, 240);
        color:white;
     }
     ul{
        list-style-type: none;
        margin:0px;
        padding:0px;
     }

     li{
        display: inline;
     }

     img{
      margin-top: 50px;
      margin-right: 40px;
        padding-top:50px;
        padding-right:70px;
        border:2px solid rgb(155, 11, 102);
        border-radius: 50%;
        padding-left: 40px;
        background-color: rgb(212, 154, 193);
     }
     img:hover{
        background-color: aqua;
        transition:0.4s;
        
     }

     header{
      margin-top: 20px;
     }

     .container {
          width: 100%;
          height: 90vh;
          display: flex;
          background-color: rgb(180, 219, 237);
          margin-top: 20px;
          color:rgb(189, 43, 226);
       }

          .left {
           flex: 40%;
           text-align: left;
           padding-top :195px;
           padding-left:125px;
         }

         span:hover{
            color:white;
            transition:0.4s;
         }



         .right { 
          flex: 50%;
           border: 2px solid black;
           padding-top:50px;
           padding-right: 90px;
           border:none;
           border-radius: 50%;

          }
         
</style>

</head>
<body>

    <div id="a">
         <header>
            <nav>
            <ul>
           <li><a href="#top">Home</a></li>
           <li><a href="#top">Services</a></li>
           <li><a href="#top">Contact</a></li>
           <li><a href="#top">About</a></li>
           <li><input type="submit" id="login" value="Login"></li>
            </ul>
            </nav>
         </header>
         <div class="container">
            <div class="left">
              <span style="font-size:45px;font-family:cursive;">RISHITA JAISWAL</span><br>
            <span style="font-size: 20px;font-family:cursive;">Frontend Developer</span><br>
             <span style="font-size: 20px;font-family:cursive;">Competitive Programmer in java Language</span>
            </div>
            <div id="right">
                <img src="female.png"  width="350px"  height="350px"; align="right">
            </div>
         </div>
        
    </div>
</body>
</html>
