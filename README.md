!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>student result management system </title>
    <link rel="stylesheet" href="style.css">
    
</head>
<body background="student result/592d7dcc-d325-4714-86de-2e9ada8a3ee6_SliderImage_Main Campus GEC.jfif">
    
    <div class="full-page">
        <div class="sub-page">
            <div class="navigation-bar">
                <div class="logo">
                    <a>Premier University</a>
                    <img  class="nall" src="student result/Logo_of_Premier_University_(PU).png" alt="">
                </div>
             
                <nav>
                    <ul id='MenuItems'>
                        <li><a href='#'>Home</a></li>
                        <li><a href='#'>Services</a></li>
                        <li><a href='#'>Contact</a></li>
                        <li><a href='#'>Notice</a></li>
                        <li><a href='#'>Admission</a></li>
                    </ul>
                </nav>
            </div>
            <div class="row">
                <div class="col-1">
                    <div class="form-box">
                        <div class="form">
                            <form class="login-form">
                                <center><h1 class="main-heading">Login Form</h1></center>
				                <input type="text"placeholder="user name-id"/>
				                <input type="password"placeholder="password"/>
				                <button>LOGIN</button>
				                <p class="message">Not Registered? <a href="#">Register</a></p>
				            </form>
                            <form class="register-form">
                                <center><h1 class="main-heading">Register Form</h1></center>
				                <input type="text" placeholder="user name-id "/>
				                <input type="text" placeholder="email-id"/>
				                <input type="password" placeholder="password"/>
				                <button>REGISTER</button>
				                <p class="message">Already Registered?<a href="#">Login</a>
				                </p>
				            </form>
			             </div>
	                </div>
                </div>
                <div class="col-1">
                    <p class='defination'><br> <br><br></p>
                </div>
            </div>
        </div>
    </div>
    <script src='https://code.jquery.com/jquery-3.2.1.min.js'>
    </script>
    <script>
        $('.message a').click(function(){$('form').animate({height: "toggle",opacity: "toggle"},"slow");});
    </script>
</body>
</html>
