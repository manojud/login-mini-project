# login-mini-project
#index.html
<!DOCTYPE html>
<html>
    <head>
        <meta name="viewport" content="width=device-width,initial-scale=1.0">
        <title>Twitter Login Page Design Using HTML And CSS</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
   <div class="login-box">
    <img src="logo.png" class="logo">
    <h2>Sign in to Twitter</h2>
    <button><img src="google.png">Sign in with Google</button>
    <button><img src="apple.png">Sign in with Apple</button>
    <hr>
    <span>Or</span>
    <form>
        <input type="text" placeholder="Phone, email or username">
        <button>Next</button>
    </form>
    <button>Forgot password?</button>
    <p>Don't have an account? <a href="#">Sign up</a> </p>
   </div>     

    </body>
</html>



#style.html

*{
    margin: 0;
    padding: 0;
    font-family: 'Poppins',sans-serif;
    box-sizing: border-box;
}
body{
    background-color: #262a2f;
}
.login-box{
    background: #fff;
    padding: 30px 120px;
    width:550px;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
    text-align: center;
    border-radius: 10px;
}
.logo{
    width: 30px;
    margin-bottom: 20px;
}
.login-box h2{
    margin-bottom: 20px;
}
.login-box button img{
    width: 18px;
    margin-right: 10px;

}
.login-box button{
    width: 100%;
    padding: 10px 0;
    display: flex;
    align-items: center;
    justify-content:center;
    margin: 20px 0;
    border-radius: 30px;
    background: transparent;
    border: 1px solid #999;
    font-weight: 500;
    cursor: pointer;
}
.login-box hr{
    border: 0;
    height: 1px;
    background: #c2c2c2;
    margin: 5px;
}
.login-box span{
    display: block;
    width: 40px;
    margin: auto;
    background: #fff;
    font-size: 14px;
    margin-top: -16px;
}
.login-box input{
    width: 100%;
    background: transparent;
    border: 1px solid #999;
    outline: 0;
    padding: 15px 10px;
    border-radius: 4px;
    margin: 10px 0;
}
::placeholder{
    font-weight: 500;
    color: #020000;
}
.login-box form button{
    background: #000;
    color: #fff;
    border: 0;
    margin-bottom: 15px;
}
.login-box p{
    text-align: left;
    font-size: 14px;
    color: #555;
    margin: 40px 0 50px;
}
.login-box p a{
    text-decoration: none;
    color: #359cf0;
}
