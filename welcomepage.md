<!DOCTYPE html>
<html>
    <head>
 <meta charset="UTF-8"/>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css"/>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.0/jquery.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
    <meta name="viewport" content="width=device-width, initial-scale=1"/>
        <style>
        
            .navbar{
                 margin-bottom: 0;
                border-radius: 0;
                border: 0;
                background-color:black;
            }
            .logo{
                float: left;
                width: 450px;
                margin-top: 20px;
            }
            .navbar-nav li{
                display:inline-block;
                color: white;
                box-sizing: border-box;
                padding: 12px 15px 12px 39px;
                
            }
            .navbar-nav a{
                text-decoration:none;
                color: azure;
	            text-align:center;
	            float:right;
	            font-size:21px;
	            font-weight:bold;
                
            }
            .text-block{
                position:absolute;
                left: 50%;
                top: 50%;
                transform: translate(-50%,-50%);
                background-color:black;
                    color:white;
                padding-left:80px;
                padding-right:80px;
                
                
            }
            .h1{
                color: white;
                size:30px;
            }
            
            .footer{
	            background:#3b3a36;
                text-align:center;
                color:white;
                height:10%;
                 }
           
        </style>
    </head>
<body>


<nav class ="navbar navbar-default navbar-fixed-top ">
    <div class="container">
    <div class="navbar-header">
        <div class="logo">
        <img src ="./img/logo.png" width="65px" height="65px"></div>
        <button class="navbar-toggle" data-toggle="collapse" data-target="#indexNavbar" type="button">
        <span class="icon-bar" > </span>
            <span class="icon-bar" > </span>
            <span class="icon-bar" > </span>
        </button>
         
        </div>
        <div class="collapse navbar-collapse" id="indexNavbar">
        <ul class="nav navbar-nav">
            <li><a href="#">Home</a></li>
             <li><a href="#">About US </a></li>
             <li><a href="#">Sign Up</a></li>
             <li><a href="#">Register</a></li>
            </ul>
        </div>
    </div>
    </nav>
   <div class="image">
  <img  src="./img/College.jpg" alt="Chania" width="100%" height="100%"> 
   <div class="text-block">
       <h1>Welcome </h1><br>
       <p>Lasalle Portfolio</p><br>
       <p>Ocean of Opporunities</p>
       </div>
</div>
    
<div class="footer">
		<br>
				copyright &copy; LasalleCollege
		</div>
</body>
</html>