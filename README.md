# IBM-Project-44517-1660725000
Nutrition assistant Application
register.html
<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
<meta charset="UTF-8">
<link rel="stylesheet" href="C:\Users\Perumal\Desktop\RAMYA ASSIGNMENTS\coding\register.css">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body background="C:\Users\Perumal\Pictures\nutrition bg.png">
<div class="container">
<div class="title">Registration</div>
<div class="content">
<form action="{{url_for('register')}}" method="POST" class="login email">
<div class="user-details">
<div class="input-box">
<span class="details">Full Name</span>
<input type="text" placeholder="Enter your name" name="fullname">
</div>
<div class="input-box">
<span class="details">Username</span>
<input type="text" placeholder="Enter your username"
name="username">
</div>
<div class="input-box">
<span class="details">Email</span>
<input type="text" placeholder="Enter your email" name="email">
</div>
<div class="input-box">
<span class="details">Phone Number</span>
<input type="text" placeholder="Enter your number"
name="phonenumber">
</div>
<div class="input-box">
<span class="details">Password</span>
<input type="password" placeholder="Enter your password"
name="passwords">
</div>
<div class="input-box">
<span class="details">Confirm Password</span>
<input type="password" placeholder="Confirm your password"
name="cpassword">
</div>
</div>
<div class="button">
<input type="submit" value="Register">
 already registered?
 <a href="login.html"> login </a>
</div>
</form>
</div>
</div>
</body>
</html>
login.html
<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
<meta charset="UTF-8">
<link rel="stylesheet" href="C:\Users\Perumal\Desktop\RAMYA ASSIGNMENTS\coding\register.css">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body background="C:\Users\Perumal\Pictures\nutrition bg.png">
<div class="container">
<div class="title">Login</div>
<div class="content">
<form action="{{url_for('register')}}" method="POST" class="login email">
<div class="user-details">
<div class="input-box">
<span class="details">Username</span>
<input type="text" placeholder="Enter your username"
name="username">
</div>

<br><br>
<div class="input-box">
<span class="details">Password</span>
<input type="password" placeholder="Enter your password"
name="passwords">
</div>
</div>
<div class="button">
<input type="submit" value="login">
<button onclick="my function()">login</button>
not registered?
 <a href="register.html"> register </a>
</div>
</form>
</div>
</div>
</body>
</html>
