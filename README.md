<!DOCTTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Free Online Courses</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" integrity="sha512-iBBXm8fW90+nuLcSKlbmrPcLa0OT92xO1BIsZ+ywDWZCvqsWgccV3gFoRBv0z+8dLJgyAHIhR35VZc2oM/gI1w==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Jomhuria&display=swap" rel="stylesheet">
  
<style>
   

.U1{
    background-color: bisque;
    padding: 18px;
}

.U1 ul{
    list-style-image:url("search.png.png") ;
    list-style-type: disc;
    list-style: none;
    font-family: 'Jomhuria', cursive;
    font-size: 50px;
    margin: 20px 15px;
}
.subject{
    width: 400px;
    text-align:center;
}

.U1 li::before{
    content: '\f058';
    font-family: 'Font Awesome 5 Free';
    font-weight: bold;
    font-size: 40px;
    display: inline-block;
    margin: 20px 15px;
    align-content: center;

}
h1,h2{
    font-family:Georgia, 'Times New Roman', Times, serif;
    text-align: center;
    background-color: tomato;
    border-radius: 10px;
    box-sizing: border-box;
    margin-left:500PX;
    border: 2.5px ;
    padding: 18px;
    width: 550px;
    color: rgb(255, 255, 255);
    margin-top:15px;
    margin-bottom: 15px;
}
h1:hover{
    background-color: chartreuse;
    transition: 1s;
}
.fname, .lname, .email, .pass {
   background: burlywood;
   border-radius: 8px;
   border: none;
   cursor:-moz-grab ;
   margin: 15px;
}
.submit, .reset{
    background: aquamarine;
    border: none;
    border-radius: 8px;
    padding: 10px;
    margin: 15px;
}
.search{
    width: 5px;
    background-image: url("search.png");
    background-repeat: no-repeat;
    padding: 13px;
    background-position-y: 8px;
    background-position-x: 4px;
    padding-left: 25px;
    cursor: pointer;
    border-radius: 35px;
    margin-left: px;
}
.search:hover{
    width: 310px;
    transition: 0.7s;

}
.select{
    border-radius: 8px;
    margin-top: 15px;
}
.menu ul li{
    list-style-type: none;margin: 20px 100px; float: left;font-size: 50px; 
    
}
.menu ul li a{
    text-decoration: none;
    color: black;
}
.menu {
    width: 700;height: 90px;background-color: gold;
}
.menu ul li a:hover {
    color:cornflowerblue;
}
</style>


</head>
<body>
    <input type="search" placeholder="Search" class="search">
    <div class="menu">
        <ul>
            <li><a href="practisevs.html" target="blank"">Home</a></li>
            <li>Tutorials</li>
            <li>Contact</li>
            <li>Support</li>
        </ul>
    </div><br><br><br><br><br><br>
    <h1>Do you know what we teach here?</h1><br><br><br>
    <div class="U1">
  <ul>
    <li>English</li>
    <li>Physics</li>
    <li>Bangla</li>
    <li>Maths</li>
    <li>Biology</li>
    <li>Programming</li>
    <li>Graphics Design</li>      
  </ul>
  </div><br><br><br>
  <h2>So waiting for what? Just fill-up the forms to register! And enjoy <b>free courses</b>.</h2><br><br><br>

  <form>
      <label>First Name:</label>
      <input type="text" name="firstname" class="fname">
      <label>Second Name:</label>
      <input type="text" name="firstname" class="lname"><br>
      <label>E-mail: &nbsp;&nbsp;&nbsp;&nbsp; &nbsp;</label>
      <input type="email" name="firstname" class="email"><br>
      <label>Password:&nbsp; &nbsp;</label>
      <input type="password" name="firstname" class="pass"><br>
      <label>Choose your course:</label>
      <select class="select">
          <option>Bangla</option>
          <option>English</option>
          <option>Physics</option>
          <option>Maths</option>
          <option>Biology</option>
          <option>Programming</option>
          <option>Graphics Design</option>
      </select><br><br><br>
      <input type="submit" name="firstname" class="submit">
      <input type="reset" name="firstname" class="reset">
  </form>
</body>
</html>

