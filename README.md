# ElishiaMata.github.io
<!DOCTYPE html>
<html>
<head>
  <title>Our Menu</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      text-align: center; 
    }
    h1 {
      margin-top: 50px;
      font-size: 24px;
      font-weight: bold;
    }
    .box-container {
      display: flex;
      justify-content: center;
      margin-top: 60px;
      background-color: gray;
    }
    h2 {
      margin-top: 50px;
      font-size: 24px;
      font-weight: bold;
    }
    .box {
      width: 300px;
      height: 200px;
      background-color: #d5cece;
      border: 5px solid black;
      margin: 10px;
      box-sizing: border-box;
      position: relative;
      padding: 50px;
    }
    .menu-item {
      position: absolute;
      top: 10px;
      right: 10px;
      border: 3px solid black;
      padding: 10px;
      background-color: #82a791;
    }
  </style>
</head>
<body>
  <h1>Our Menu</h1>
  <div class="box-container">
    <div class="box">
      <div class="menu-item">Chicken</div>
      <p>Chicken and Spaghetti Caprese is our most popular item on the menu 
        If you are looking for a great meal try this. 
      </menu>.</p>
    </div>
    <div class="box">
      <div class="menu-item">Beef</div>
      <p>Beef Bulgolgi is our second most popular item on the menu  
        The dish contains juicy sliced sirloin and onions
      </menu>.</p>
    </div>
    <div class="box">
      <div class="menu-item">Pork</div>
      <p>The great American pork chop is our third best item on the menu  
        This thinly sliced fried por will keep you coming for more.</p>
    </div>
  </div>
</body>
</html>