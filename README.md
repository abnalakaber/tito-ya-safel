<!doctype html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>Mohamed Gomaa</title>
    <link rel="stylesheet" href="Style.css">
<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto+Condensed:ital,wght@0,100..900;1,100..900&display=swap');

*{
  font-family: 'Roboto Condensed', sans-serif; 
  padding: 0;
  margin: 0;
}
a{
  color: white;
  text-decoration: none;
}

body{
  background-image: linear-gradient(to right, #01022d, #000);
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
}
.container{
  background-image:
  linear-gradient(to right, #01022de5 30%,#00000088),url(hrz.jpg);
  width: 90%;
  height: 640px;
  background-repeat: no-repeat;
  background-size: cover;
}
container:hover{
  background-image:
  linear-gradient(to right, #01022de5 30%,transparent),url(hrz.jpg);
  width: 90%;
  height: 640px;
}
header{
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px;
}
.logo{
  font-size: 30px;
  text-transform: uppercase;
}
ul{
  width: 60%;
  list-style: none;
  display: flex;
  justify-content: space-evenly;
}
ul a{
  border-bottom: 2px solid transparent;
}
ul a:hover{
  border-bottom-color: white;
}
.content{
  background-position: center;
  color: white;
  width: 50%;
  margin-top: 50px; 
  padding: 30px;
}
.content h2{
  font-size: 100px;
  font-transform: uppercase;
}
.content p{
  letter-spacing: 3px;
  width: 350px;
  padding: 20px 0;
}
.content button{
  font-size: 30px;
  padding: 6px 10px;
  border-radius: 10px;
  border: 2px solid transparent;
  cursor: pointer;
}
.content button:hover{
  background-color: transparent;
  border-color: white;
  color: white;
}
</style>
</head>

<body>
   <div class="container">
       <header>
           <a href="#" class="logo">kelvn</a>
           <ul>
               <li><a href="#">Home</a></li>
               <li><a href="#">Clans</a></li>
               <li><a href="#">Videos</a></li>
               <li><a href="#">Photos</a></li>
               <li><a href="#">About</a></li>
           </ul>
       </header>
       <div class=content>
       <h2>kelvn</h2>
       <p> lorem lorem lorem lorem lorem lorem lorem lorem lorem lorem lore</p>
       <button> click her</button>
       </div>
   </div>
</body>

</html>
