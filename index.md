layout: page
title: "Home"
permalink: /index/

<!DOCTYPE html>
<html lang="en">
<head>
  <title>ByteBrothers</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
  <style>
    /* Remove the navbar's default margin-bottom and rounded borders */ 
    .navbar {
      margin-bottom: 0;
      border-radius: 0;
    }
    
    /* Add a gray background color and some padding to the footer */
    footer {
      background-color: #f2f2f2;
      padding: 25px;
      float: bottom;
    }
  </style>
</head>
<body>

<nav class="navbar navbar-inverse">
  <div class="container-fluid">
    <div class="collapse navbar-collapse" id="myNavbar">
      <ul class="nav navbar-nav">
        <li class="active"><a href="#">Home</a></li>
        <li><a href="/about.html/">About</a></li>
        <li><a href="#">Gallery</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
      <ul class="nav navbar-nav navbar-right">
        <li><a href="/index.html/"><span class="glyphicon glyphicon-log-in"></span>Login</a></li>
      </ul>
    </div>
  </div>
</nav>

<div class="jumbotron">
  <div class="container text-center">
    <h1>Learn CS Without The Stress</h1>      
    <p>Computer Science Made Easy</p>
  </div>
</div>
  
<div class="container-fluid bg-3 text-center">    
  <h3>Beginner Tutorial Sets</h3><br>
  <div class="row">
    <div class="col-sm-3">
      <p>Begin Now</p>
      <button type="button" class="btn btn-primary btn-block" style="width:100%" style="height: 100%">C</button>
    </div>
    <div class="col-sm-3"> 
      <p>Begin Now</p>
      <button type="button" class="btn btn-primary btn-block" style="width:100%" style="height: 100%">Python</button>
    </div>
    <div class="col-sm-3"> 
      <p>Begin Now</p>
      <button type="button" class="btn btn-primary btn-block" style="width:100%" style="height: 100%">Boolean Algebra</button>
    </div>
    <div class="col-sm-3">
      <p>Begin Now</p>
      <button type="button" class="btn btn-primary btn-block" style="width:100%" style="height: 100%">HTML</button>
    </div>
  </div>
</div><br>

<div class="container-fluid bg-3 text-center">    
  <div class="row">
    <div class="col-sm-4">
      <p>Begin Now</p>
      <button type="button" class="btn btn-primary btn-block" style="width:100%" style="height: 100%">Neural Nets</button>
    </div>
    <div class="col-sm-4"> 
      <p>Begin Now</p>
      <button type="button" class="btn btn-primary btn-block" style="width:100%" style="height: 100%">Java</button>
    </div>
    <div class="col-sm-4"> 
      <p>Begin Now</p>
      <button type="button" class="btn btn-primary btn-block" style="width:100%" style="height: 100%">CSS</button>
  </div>
</div><br><br>

<footer class="container-fluid text-center">
  <p>ByteBrothers LLC</p>
  <p>Founded by: Alex Griffith, Devon Griffith, Riley Griffith</p>
</footer>

</body>
</html>
