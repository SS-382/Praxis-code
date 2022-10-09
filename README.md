# Praxis-code
<!DOCTYPE html>
<html lang="en">
<title>Webpage Design</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="main">
        <div class="navbar">
            <div class="icon">
                <h2 class="logo">Praxis Code</h2>
            </div>

            <div class="menu">
                <ul>
                    <li><a href="#home">HOME</a></li>
                    <li><a href="#about">ABOUT</a></li>
                    <li><a href="#service">SERVICE</a></li>
                    <li><a href="#design">DESIGN</a></li>
                    <li><a href="#contact">CONTACT</a></li>
                </ul>
            </div> 

                <section id="home">
                    <div class="search">
                        <input class="srch" type="search" name="" placeholder="Type To text">
                        <a href="#"> <button class="btn">Search</button></a>
                    </div>
                <div class="content">
                    <h1>Web Design &<br><span>Development</span> <br>Course</h1>
                    <p class="par">Lorem ipsum dolor sit amet consectetur adipisicing elit. Sunt neque 
                         expedita atque eveniet <br> quis nesciunt. Quos nulla vero consequuntur, fugit nemo ad delectus 
                        <br> a quae totam ipsa illum minus laudantium?</p>
        
        
                        <div class="form">
                            <h2>Login Here</h2>
                            <input type="email" name="email" placeholder="Enter Email Here">
                            <input type="password" name="" placeholder="Enter Password Here">
                            <button class="btnn"><a href="#">Login</a></button>
        
                            <p class="link">Don't have an account<br>
                            <a href="#">Sign up </a> here</a></p>
                            <p class="liw">Log in with</p>
        
                            <div class="icons">
                                <a href="#"><ion-icon name="logo-facebook"></ion-icon></a>
                                <a href="#"><ion-icon name="logo-instagram"></ion-icon></a>
                                <a href="#"><ion-icon name="logo-twitter"></ion-icon></a>
                                <a href="#"><ion-icon name="logo-google"></ion-icon></a>
                                <a href="#"><ion-icon name="logo-skype"></ion-icon></a>
                            </div>
        
                          </div>
                            </div>
                        </div>
                </div>
            </div>

                  </section>
                <section id="about">
                    <h1>About</h1>
                    <p class="lead">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Commodi, quis!</p>
                </section>
                <section id="service">
                    <h1>Service</h1>
                    <p class="lead">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Commodi, quis!</p>
                </section>
                <section id="contact">
                    <h1>Contact</h1>
                    <div class="container">
                        <div class="contact-box">
                            <div class="left"></div>
                            <div class="right">
                                <h2>Contact Us</h2>
                                <input type="text" class="field" placeholder="Your Name">
                                <input type="text" class="field" placeholder="Your Email">
                                <input type="text" class="field" placeholder="Phone">
                                <textarea placeholder="Message" class="field"></textarea>
                                <button class="btn">Send</button>
                            </div>
                        </div>
                    
                </section>
            </div>

            
    <script src="https://unpkg.com/ionicons@5.4.0/dist/ionicons.js"></script>
</body>
</html>

** CSS Code **
*{
    margin: 0;
    padding: 0;
}

.main{
    width: 100%;
    background:url(background2.webp);
    background-position: center;
    background-size: cover;
    height: 100vh;
}
.navbar{
    width: 1200px;
    height: 75px;
    margin: auto;
}
.icon{
    width: 200px;
    float: left;
    height: 70px;
}
.logo{
    color: #ff7200;
    font-size: 35px;
    font-family: Arial;
    padding-left: 20px;
    float: left;
    padding-top: 10px;
    margin-top: 5px
}
.menu{
    width: 400px;
    float: left;
    height: 70px;
}
ul{
    float: left;
    display: flex;
    justify-content: center;
    align-items: center;
}
ul li{
    list-style: none;
    margin-left: 62px;
    margin-top: 27px;
    font-size: 14px;
}
ul li a{
    text-decoration: none;
    color: #fff;
    font-family: Arial;
    font-weight: bold;
    transition: 0.4s ease-in-out;
}
ul li a:hover{
    color: #ff7200;
}
.search{
    width: 330px;
    float: left;
    margin-left: 270px;
}
.srch{
    font-family: 'Times New Roman';
    width: 200px;
    height: 40px;
    background: transparent;
    border: 1px solid #ff7200;
    margin-top: 13px;
    color: #fff;
    border-right: none;
    font-size: 16px;
    float: left;
    padding: 10px;
    border-bottom-left-radius: 5px;
    border-top-left-radius: 5px;
}
.btn{
    width: 100px;
    height: 40px;
    background: #ff7200;
    border: 2px solid #ff7200;
    margin-top: 13px;
    color: #fff;
    font-size: 15px;
    border-bottom-right-radius: 5px;
    border-bottom-right-radius: 5px;
    transition: 0.2s ease;
    cursor: pointer;
}
.btn:hover{
    color: #000;
}
.btn:focus{
    outline: none;
}
.srch:focus{
    outline: none;
}
.content{
    width: 1200px;
    height: auto;
    margin: auto;
    color: #fff;
    position: relative;
}
.content .par{
    padding-left: 20px;
    padding-bottom: 25px;
    font-family: Arial;
    letter-spacing: 1.2px;
    line-height: 30px;
}
.content h1{
    font-family: 'Times New Roman';
    font-size: 50px;
    padding-left: 20px;
    margin-top: 9%;
    letter-spacing: 2px;
}
.content .cn{
    width: 160px;
    height: 40px;
    background: #ff7200;
    border: none;
    margin-bottom: 10px;
    margin-left: 20px;
    font-size: 18px;
    border-radius: 10px;
    cursor: pointer;
    transition: .4s ease;
    
}
.content .cn a{
    text-decoration: none;
    color: rgb(34, 21, 79);
    transition: .3s ease;
}
.cn:hover{
    background-color: #fff;
}
.content span{
    color: #ff7200;
    font-size: 65px
}
.form{
    width: 250px;
    height: 380px;
    background: linear-gradient(to top, rgba(0,0,0,0.8)50%,rgba(0,0,0,0.8)50%);
    position: absolute;
    top: -20px;
    left: 870px;
    transform: translate(0%,-5%);
    border-radius: 10px;
    padding: 25px;
}
.form h2{
    width: 220px;
    font-family: sans-serif;
    text-align: center;
    color: #ff7200;
    font-size: 22px;
    background-color: #fff;
    border-radius: 10px;
    margin: 2px;
    padding: 8px;
}
.form input{
    width: 240px;
    height: 35px;
    background: transparent;
    border-bottom: 1px solid #ff7200;
    border-top: none;
    border-right: none;
    border-left: none;
    color: #fff;
    font-size: 15px;
    letter-spacing: 1px;
    margin-top: 30px;
    font-family: sans-serif;
}
.form input:focus{
    outline: none;
}
::placeholder{
    color: #fff;
    font-family: Arial;
}
.btnn{
    width: 240px;
    height: 40px;
    background: #ff7200;
    border: none;
    margin-top: 30px;
    font-size: 18px;
    border-radius: 10px;
    cursor: pointer;
    color: #fff;
    transition: 0.4s ease;
}
.btnn:hover{
    background: #fff;
    color: #ff7200;
}
.btnn a{
    text-decoration: none;
    color: #000;
    font-weight: bold;
}
.form .link{
    font-family: Arial, Helvetica, sans-serif;
    font-size: 17px;
    padding-top: 20px;
    text-align: center;
}
.form .link a{
    text-decoration: none;
    color: #ff7200;
}
.liw{
    padding-top: 15px;
    padding-bottom: 10px;
    text-align: center;
}
.icons a{
    text-decoration: none;
    color: #fff;
}
.icons ion-icon{
    color: #fff;
    font-size: 30px;
    padding-left: 14px;
    padding-top: 5px;
    transition: 0.3s ease;
}
.icons ion-icon:hover{
    color: #ff7200;
}


@media screen and (max-width:1200px) {
    /*Normal Screen*/

    .navbar{
        width: 100%;
        height: 100px;
    }
    ul{
        margin-left: 30px;
    }   
    ul li{
        margin-left: 60px;
    }
    ul li a{
       font-size: 1.6vw; 
    }
    .search{
        margin-top: 3px;
        margin-left: 290px;
    }
    .srch{
        height: 40px;
        width: 190px;
        font-size: 14px;
    }
    .btn{
        height:40px;
        width: 80px;
    }
    .content{
        width: 100%;
    }
    .content h1, .content span{
        font-size: 4.5vw; 
    }
    .content .par{
        width: 90%;
        font-size: 1.5vw;
    }
    .content .cn{
        width: 13%;
        height: 3.5vw;
        font-size: 1.8vw;
    }
    .content a{
        font-size: 1.6vw
    }
}

@media screen and (max-width:1170px) {
    /*Login-box*/
    .main{
        padding-left: 20px;
        height: 180vh;
    }
    .form{
        margin-left: -30px;
        width: 250px;
        height: 370px;
        background: linear-gradient(to top, rgba(0,0,0,0.8)50%,rgba(32, 14, 132, 0.8)50%);
        position: absolute;
        top: 420px;
        left: 50px;
        transform: translate(0%,-5%);
        border-radius: 10px;
        padding: 25px;
    }
    .form input{
        width: 240px;
        height: 35px;
        background: transparent;
        border-bottom: 1px solid #ff7200;
        border-top: none;
        border-right: none;
        border-left: none;
        color: #fff;
        font-size: 15px;
        letter-spacing: 1px;
        margin-top: 30px;
        font-family: sans-serif;
    }
    .btnn a{
        font-size: 16px;
    }
    .form .link a{
        font-size: 16px;
    }
}

@media screen and (max-width: 830px){
    /*For tablet*/
   
    .content{
        margin-top: 120px;
        width: 80%;   
        margin-left: 40px;  
    }
    .content h1, .content span{
        font-size: 6vw; 
    }
    .content .par{
        width: 90%;
        font-size: 1.8vw;
    }
    .content .cn{
        width: 15%;
        height: 4.5vw;
        font-size: 2vw;
    }
    .content a{
        font-size: 2vw
    }
    .logo{
        margin-left: 240px;
        width: 100%;
        margin-top: 15px;
        font-size: 5vw;
    }
    .menu{
        width: 100%;
    }
    ul{
        margin-top: -5px;
        margin-left: 5px;
    }
    ul li{
        margin-left: 60px;
    }
    ul li a{
       font-size: 2vw; 
    }
    .search{
        margin-top: -20px;
        margin-left: 60px;   
    }   
    .srch{
        height: 30px;
        width: 160px;
        font-size: 12px;
    }
    .btn{
        height:30px;
        width: 70px;
    }
    .main{
        padding-left: 20px;
        height: 180vh;
    }
    .form{
        margin-left: -30px;
        width: 250px;
        height: 370px;
        background: linear-gradient(to top, rgba(0,0,0,0.8)50%,rgba(16, 28, 114, 0.8)50%);
        position: absolute;
        top: 430px;
        left: 50px;
        transform: translate(0%,-5%);
        border-radius: 10px;
        padding: 25px;
    }
    .form input{
        width: 240px;
        height: 35px;
        background: transparent;
        border-bottom: 1px solid #ff7200;
        border-top: none;
        border-right: none;
        border-left: none;
        color: #fff;
        font-size: 15px;
        letter-spacing: 1px;
        margin-top: 30px;
        font-family: sans-serif;
    }
    .btnn a{
        font-size: 16px;
    }
    .form .link a{
        font-size: 16px;
    }
}

@media screen and (max-width: 600px){
    /*IPAD*/
    
    .content{
        margin-top: 80px;
        margin-left: 20px;
    }
    .search{
        margin-top: -40px;
        margin-left: 42px;
    }
    .logo{
        margin-left: 180px;
        font-size: 4vw;
    }
    ul{
        margin-top: -25px;
        margin-left: -5px;
    }
    ul li {
        margin-left: 50px;
    }
    ul li a{
        font-size: 2vw;
    }   
}

@media screen and (max-width: 450px){
    /*mobile*/
    .logo{
        margin-left: 140px;
        font-size: 4vw;
    }
    ul{
        margin-top: -25px;
    }
    ul li {
        margin-left: 42px;
    }
    ul li a{
        font-size: 2vw;
    }  
    .search{
        margin-top: -40px;
        margin-left: 38px;
    } 

}
section {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    text-align: center;
    width: 100%;
    height: 100vh;
   
    /* Scroll Snap */
    scroll-snap-align: center;
  }
  
  section h1 {
    font-size: 4rem;
  }
  
  /* Section Images */
  
  section#about {
    background:url(background2.webp);
  }
  
  section#service {
    background:url(background2.webp);
  }
  
  section#contact {
    background:url(background2.webp);
  }
  /*  contact form*/
 

.container{
	position: relative;
	width: 100%;
	height: 100%;
	display: flex;
	justify-content: center;
	align-items: center;
	padding: 20px 100px;
}

.container:after{
	content: '';
	position: absolute;
	width: 100%;
	height: 100%;
	left: 0;
	top: 0;
	background: url("background2.webp") no-repeat center;
	background-size: cover;
	filter: blur(50px);
	z-index: -1;
}
.contact-box{
	max-width: 850px;
	display: grid;
	grid-template-columns: repeat(2, 1fr);
	justify-content: center;
	align-items: center;
	text-align: center;
	background-color: #fff;
	box-shadow: 0px 0px 19px 5px rgba(0,0,0,0.19);
}

.left{
	background: url("background2.webp") no-repeat center;
	background-size: cover;
	height: 100%;
}

.right{
	padding: 25px 40px;
}

h2{
	position: relative;
	padding: 0 0 10px;
	margin-bottom: 10px;
}

h2:after{
	content: '';
    position: absolute;
    left: 50%;
    bottom: 0;
    transform: translateX(-50%);
    height: 4px;
    width: 50px;
    border-radius: 2px;
    background-color: #cc9a2e;
}

.field{
	width: 100%;
	border: 2px solid rgba(0, 0, 0, 0);
	outline: none;
	background-color: rgba(230, 230, 230, 0.6);
	padding: 0.5rem 1rem;
	font-size: 1.1rem;
	margin-bottom: 22px;
	transition: .3s;
}

.field:hover{
	background-color: rgba(0, 0, 0, 0.1);
}

textarea{
	min-height: 150px;
}

.btn{
	width: 100%;
	padding: 0.5rem 1rem;
	background-color: #cc8a2e;
	color: #fff;
	font-size: 1.1rem;
	border: none;
	outline: none;
	cursor: pointer;
	transition: .3s;
}

.btn:hover{
    background-color: #ae6627;
}

.field:focus{
    border: 2px solid rgba(30,85,250,0.47);
    background-color: #fff;
}

@media screen and (max-width: 880px){
	.contact-box{
		grid-template-columns: 1fr;
	}
	.left{
		height: 200px;
	}
}
