# ADP-project
Home page code:
<!DOCTYPE html>
<html>
<head>
    <style>
h1{
    background-color:blueviolet; color:cyan;
    font-family: 'Courier New', Courier, monospace;
    text-align: center;
    border:5px outset blueviolet;
}
body
{
    
    background: linear-gradient(cyan,purple);
} 
.navbar
{
    overflow:hidden;
}
.navbar a
{
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    float:right;color:blueviolet;text-align:center;
    padding :10px 10px;text-decoration: none;
    font-size:14px;background-color:rgb(215, 249, 249);
    border:2px outset rgb(215, 249, 249)
}
.navbar a:hover
{
    background-color:darkgrey;color:black
}
.navbar a:active
{
    background-color:blueviolet;color:white
}
table
{
width:100%
}
th
{
    text-align:center
}
    </style>
    <title>Domazon Super Market</title>
</head>
<body>
    <div class="head1">

        <h1 >WELCOME TO DOMAZAN SUPER MARKET<br><br><br></h1>
    </div>
    
    <div class="navbar">
        <nav>
        <a href="#home">HOME</a>
        <a href="#fv">FRUITS & VEGETABLES</a>
        <a href="#pack">PACKAGED FOOD</a>
        <a href="#essent">DAILY ESSENTIALS</a>
        <a href="login.html">LOGIN</a>
        </nav>
    </div>

<div id="home" class="homepage">
<h2>TODAY 30% OFFERS ON</h2>
<marquee scrollamount="12">
<table align="center">
<th>
<a href="#pack"><img src="Packaged-Food-min.webp"></a>
</th>
<th>and</th>
<th>
<a href="#essent"><img src="Daily-Essentials-min.webp"></a>
</th></tr></table>
</marquee>
<h2>SHOP BY CATEGORY</h2>
<table>
    <tr>
        <th><a href="#essent"><img src="Daily-Essentials-min.webp"></a></th>
        <th><a href="#pack"><img src="Packaged-Food-min.webp"></a></th>
        <th><a href="#fv"><img src="FV-min.webp"></a></th>
    </tr>
</table>
</div>
<br><br><br><br><br><br><Br>
<div id="essent" class="essentials">
    <h2>DAILY ESSENTIALS</h2>
    <table>
        <tr>
            <th><img src="100027051.webp"></th>
            <th><img src="100047825.webp"></th>
            <th><img src="128647567.webp"></th>
        </tr>
    </table>
</div>
<div id="pack" class="packaged">
    <h2>PACKAGED FOOD</h2>
    <table>
        <tr>
            <th><img src="122960448.webp"></th>
            <th><img src="100015325.webp"></th>
            <th><img src="127255924.webp"></th>
        </tr>
    </table>
</div>

<div id="fv" class="fruits&veggie">
    <h2>FRUITS & VEGETABLES</h2>
    <table>
        <tr>
            <th><img src="100025957-05032021.webp"></th>
            <th><img src="119910167-221220.webp"></th>
            <th><img src="100026731-060820.webp"></th>
        </tr>
    </table>
</div>
    

</body>
</html>

Login page code:
<html>
<head>
    <title>Login Page</title>
    <style>
        h1{
    background-color:blueviolet; color:cyan;
    font-family: 'Courier New', Courier, monospace;
    text-align: center;
    border:5px outset blueviolet;
}
tr{text-align:center}
body
{
    margin: 0;
    padding: 0;
    background-color:#6abadeba;
    font-family: 'Arial';
}
.log{
        width: 30%;
        margin: 0 0 0 400px;
        padding: 80px;
        background: #23463f;
        border-radius: 15px ;

}
h2{
    text-align: center;
    color: #277582;
    padding: 20px;
}
label{
    color: #08ffd1;
    font-size: 17px;
}
#username,#password,#sub{
    width: 300px;
    height: 30px;
    padding-left: 4px;
}



    </style>
</head>
<body>
    <div class="head1">

        <h1 >WELCOME TO AKASH SUPER MARKET<br><br><br></h1>
    </div>
    <br><br><br>
    <div class="log">
        <h2 >Login Form</h2>
        <table align="center">
            <tr>
                <th>
                    <label for="username">Username:</label><br>
                </th>
                <th>
                    <input type="text" id="username" name="username"><br>
                </th>
            </tr>
            <tr>
                <th><label for="password">Password:</label><br></th>
                <th><input type="password" id="password" name="password"><br><br></th>
            </tr>
            <tr><th colspan="2"><input type="submit" value="Submit" id="sub" onclick="validateForm()"></th></tr>
        </table>
    
    <form>
        
        
        
        
        
    </form> 
    </div>
    <script>
        function validateForm() {
            var username = document.getElementById("username").value;
            var password = document.getElementById("password").value;
            console.log(username,password)
            if (username == "user" && password == "pass") {
                window.alert("Login successful");
                return true;
            } else {
                window.alert("Invalid login credentials");
                return false;
            }
        }
    </script>
</body>
</html>

