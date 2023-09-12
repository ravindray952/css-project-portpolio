# css-project-portpolio
css portpolio from shreyansian coding school
<h1>first page</h1>
 <h6>html part</h6>

 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portpolio</title>
       <link rel="stylesheet" href="style.css">  
      <link href="https://cdn.jsdelivr.net/npm/remixicon@3.5.0/fonts/remixicon.css" rel="stylesheet"> 
</head>
<body>
    <div id="main">
         <div id="page">
            <div id="nav">
                <div id="center-nav">
                    <a href="#">ABOUT</a>
                    <a href="#">SERVICES</a>
                    <a href="#">PORTPOLIO</a>
                    <a href="#">CONTACT</a>
                </div>
               <input type="text" placeholder="search">
            </div>
            <img src="./pic.jpg" alt="">
            <div id="text">
                 <h5>Hello</h5>
                <h1>Front-End <br>React Developer 👋<br></h1>
                <h4>Hi, I am Ravindra yadav, a zealous Front-end React Developer hailing from Utter pradesh, India. 📍</h4>
                <div id="buttons">
                    <button id="b1">LET'S TALK  <i class="ri-telegram-line"></i></button>
                    <button id="b2">PORTPOLIO   <i class="ri-arrow-right-up-fill"></i></button>
                </div>
            </div>
        
        </div>
        <div id="page1"></div>
    </div>
</body>
</html>


<h6>css part</h6>

*{
    margin: 0%;
    padding: 0%;
    box-sizing: border-box;
    font-family: montserrat;
}

html,body {
    height: 100%;
    width: 100%;
}
#main{
    position: relative;
    overflow: hidden;
}
#page{
    position: relative;
    height: 100vh;
    width: 100vw;
    background-color: white;
}
#page>img{
    position: absolute;
    width: 35%;
    /* height: 70%; */
    top:52%;
    right:10%; 
    transform: translateY(-50%);
}
#page>#nav{
    display: flex;
    align-items: center;
    padding: 0px 30px;
    justify-content:space-between;
    position: absolute;
    z-index: 9;
    height: 10%;
    width: 100%;
    /* background-color: tomato; */
}
#center-nav{
    display: flex;
    gap: 20px;
}
#center-nav>a{
    text-decoration: none;
    color: black;
    font-weight: 540;
    font-size: 17px;
}
#nav>input{
    padding: 10px 5px;
    border-radius: 10px;
     border:1px solid #dadada ;
    text-transform: uppercase;
}

#page1{
    height: 100vh;
    width: 100vw;
    background-color: indigo;
}

#text{
    padding: 30px 50px;
    position:relative;
    top: 18%;
    left: 8%;
    height: 75%;
    width: 35%;
    scale: 1.1;
    /* background-color: brown; */
}
#text>h1 {
      margin: 20px;
      font-size: 60px;
      line-height: 1;
}
#text>h4{
    margin-top: 20px;
    color: #2b2b2b;
   font-size: 17px;
   font-weight: 500;     
}
#text>h5{
    color: #8873ef;
    transform: rotate(-20deg);
    position: absolute;
    left: 3%;
}
#buttons{
    position: absolute;
     left: 0%; 
   bottom: 2%;
    height: 20%;
    width: 100%;
  
}
#buttons>button{
   padding: 10px 32px;
   border-radius: 10px;
   border: none;
   font-weight:500; 
}
#button>button>i{
    font-size: 17px;

}

#buttons>#b1{
    margin-left: 20px;
    background-color:#8873ef ;
   
}
#buttons>#b2{
    margin-left: 20px;
    background-color: #8873ef;
   
}
[21 min] tk
<br> <br> <br>

