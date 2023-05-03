<!DOCTYPE html>
<html>
  <head>
    <title>Fevorite Food App</title>

        <style>
body{
    padding:0px;
    margin:0px;
    background-color:#bcd897;
}
header ul {

  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #1f1919;
}

header li {
  float: left;
  margin: 3px;
}

 header li a {
  display: block;

  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

header li a:hover {
  background-color: #8a7c7c;
}
      .text-content a{
        text-decoration:none;
        font-size: 20px;
        color:black;

      }
      .images{
        width:50%;
        margin:0 auto;
      
      }
      .labels{
        margin-left:210px;
        margin-bottom:40px;
        font-size: 20px;
      }
      .fooditem{
        width:500px;
        height:400px;
        border-radius: 10px;
      }
    </style>
  </head>
  <body>

    <!--   Header content for Nav bar  -->

    <header>
      <ul>
        <li><a href="#">Index</a></li>
        <li><a href="#">Food</a></li>
        <li><a href="#">About</a></li>
      </ul>
    </header>

      <!--  Main content of website  -->

    <main>
    <div class="main">
      <div class="text-content">
        <h2>Top 5 Favourite Foods</h2>
        <ul>
          <li><a href="#Pizzaa">Pizza</a></li>
          <li><a href="#misal">Misal</a></li>
          <li><a href="#sandwich">Sandwich</a></li>
          <li><a href="#Cold Coffee">Cold Coffee</a></li>
          <li><a href="#burger">Burger</a></li>
        </ul>
      </div> 
      <div class="images">
        <div id="Pizza"><img src="https://imgmedia.lbb.in/media/2019/07/5d242ad8e93a896e5542da0d_1562651352251.jpg" class="fooditem"></div>
        <p class="labels">Pizza</p>
        <div id="misal"><img src="https://images.travelandleisureasia.com/wp-content/uploads/sites/2/2022/06/15162526/best-misal-pav-in-pune.jpg?tr=w-1200,h-900" class="fooditem"/></div>
        <p class="labels">Misal</p>
        <div id="sandwich"><img src="https://www.eatingwell.com/thmb/vFO43UyAy2NBfjOG6wADLLCE-Kc=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc()/cucumber-sandwich-eddcc95811f5426094ea5dbea6a6b026.jpg" class="fooditem"/></div>
        <p class="labels">Sandwich</p>
        <div id="Cold coffee"><img src="https://www.whiskaffair.com/wp-content/uploads/2021/03/Cold-Coffee-2-3.jpg" class="fooditem"/></div>
        <p class="labels">Cold Coffee</p>
        <div id="burger"><img src="https://recipes.timesofindia.com/thumb/83565509.cms?width=1200&height=900" class="fooditem"/></div>
        <p class="labels">Burger</p>
      </div>
    </div>
  </main>
  </body>
</html>
