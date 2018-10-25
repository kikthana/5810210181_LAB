<!DOCTYPE html>
<html lang="en">
<head>
  <title>Bootstrap Example</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
</head>
<body>
  
  <nav id="site-nav">
<ul>
   <li><a href="#home" class="active">Home</a> </li>
   <li><a href="#news">News</a></li>
   <li><a href="#contact">Contact</a></li>
   <li><a href="#about">About</a></li>
  <a href="javascript:void(0);" class="icon" onclick="myFunction()">
    <i class="fa fa-bars"></i>
  </a>
</ul>
</nav>

<div class="container">
  <h2What is Responsive Web Design?</h2>
  <p>Responsive Web Design is about using HTML and CSS to automatically resize, hide, shrink, or enlarge, a website, to make it look good on all devices (desktops, tablets, and phones):</p><br>
  <div class="media">
    <div class="media-left">
      <img src="img_avatar1.png" class="media-object" style="width:45px">
    </div>
    <div class="media-body">
      <h4 class="media-heading">John Doe <small><i>Posted on February 19, 2016</i></small></h4>
      <p>Responsive web design makes your web page look good on all devices.</p>
      
      <!-- Nested media object -->
      <div class="media">
        <div class="media-left">
          <img src="img_avatar2.png" class="media-object" style="width:45px">
        </div>
        <div class="media-body">
          <h4 class="media-heading">John Doe <small><i>Posted on February 19, 2016</i></small></h4>
          <p>Responsive web design uses only HTML and CSS.</p>

          <!-- Nested media object -->
          <div class="media">
            <div class="media-left">
              <img src="img_avatar3.png" class="media-object" style="width:45px">
            </div>
            <div class="media-body">
              <h4 class="media-heading">John Doe <small><i>Posted on February 19, 2016</i></small></h4>
              <p>Responsive web design is not a program or a JavaScript.</p>
            </div>
          </div>
          
        </div>
      </div>
      
    </div>
  </div>
</div>

</body>
</html>
