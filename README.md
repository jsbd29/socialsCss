/*socials icons tutorial*/
<div>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Icons Social Media</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="stylesheet" href="./styles.css">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>
<body>
    <div class="wrapper">
        <div class="button">
            <div class="icon"><i class="fa-brands fa-facebook-f"></i></div>
            <span>Facebook</span>
            </div>
            <div class="button">
                <div class="icon"><i class="fa-brands fa-instagram"></i></div>
                <span>Instagram</span>
            </div>
            <div class="button"><div class="icon"><i class="fa-brands fa-x-twitter"></i></div>
            <span>X</span> 
        </div>
            <div class="button"> <div class="icon"><i class="fa-brands fa-github"></i></div>
            <span>GitHub</span>
        </div>
            
        </div>
    </div>
</body>
</html>  
  @import url('https://fonts.googleapis.com/css2?family=Poppins&display=swap');

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'poppins', sans-serif;
}
html,body{
    display: grid;
    height: 100%;
    width: 100%;
    place-items: center;
    background:linear-gradient( 315deg, #ffffff 0%, #d7e1ec 74%);
}


.wrapper .button {
    display: inline-block;
    height: 60px;
    width: 60px;
    margin: 0 5px;
    overflow: hidden;
    background-color: #f0dada;
    border-radius: 40%;
    cursor: pointer;
    box-shadow: 0px 0px 10px rgba(0,0,0,0.1);
    transition: all 0.3s ease-in-out;
}
.wrapper .button:hover{
    width: 200px;
}
.wrapper .button .icon {
    display: inline-block;
    height: 60px;
    width: 60px;
    text-align: center;
    border-radius: 50px;
    box-sizing: border-box;
    line-height: 60px;
    transition: all 0.3s  ease-in-out;
}
.wrapper .button:nth-child(1):hover .icon{
    background: #4267B2;
}
.wrapper .button:nth-child(2):hover .icon{
    background: #c13584;
}
.wrapper .button:nth-child(3):hover .icon{
    background: #14171a;
}
.wrapper .button:nth-child(4):hover .icon{
    background: #333;
}
.wrapper .button .icon i {
    font-size: 25px;
    line-height: 60px;
    transition: all 0.3s ease-in-out;
}
.wrapper .button:hover .icon i{
    color: #fff;
    
}
.wrapper .button span{
    font-size: 20px;
    font-weight: 500;
    line-height: 60px;
    margin-left: 10px;
    transition: all 0.3s ease-in-out;
}

.wrapper .button:nth-child(1) span{
   color: #4267B2;
}
.wrapper .button:nth-child(2) span{
    color: #c13584;
}
.wrapper .button:nth-child(3) span{
    color: #14171a;
}
.wrapper .button:nth-child(4) span{
    color: #333;
}</div>
