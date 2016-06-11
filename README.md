# Natasha-Restaurant.
HTML and css website

<html>
<head>
<title>Restaurant</title>

<style>
#header {
   background-color:black;
   color:white;
   text-align:center;
   padding:5px;
}
#section {
   float:left;
   padding:15px;
   width:1350px;
   background-color:cornsilk;
   }
#footer {
    background-color:snow;
    padding:5px;
}
</style>
</head>
<body>
<div id="header">
<h1><b><center><i>NATASHA RESTAURANT</i></center></b></h1>
</div>
<div id="section">
<center><img src="frontpage.jpg" alt="Restaurant" style="width:600px;height:400px;"/></center>
</div>
<div id="footer">
<center><a href="mudilaa.html">START</a></center>
</div>
</body>
</html>
<html>
<head>
<title>Restauranta</title>
</head>

<frameset rows="60,*,50" frameborder="1">
  <frame src="header.html" name="header" scrolling="no">
 
   <frame src="chumma.html" name="MENU" scrolling="no">
   
  
  <frame src="footer.html" name="footer" scrolling="no">
</frameset>
<body>

</body>
</html>
<html>
<head>
<title>restauranta</title>
</head>
<body>
   <body bgcolor="lavender">
   
   <center><h1><b><i>MENU</i></b></h1></center>
</body>
</html>  
<html>
<head>

<title>restauranta</title>
<style>
  body {
    background-image: url("http://www.ucreative.com/wp-content/uploads/2014/10/Food-photography-eastern-europe-city-illustrations-banner1.jpg");
    background-repeat: no-repeat;
    background-position: right top;
    background-attachment: fixed;
}
</style>

</head>
<body onload='hidetotal()'>
  
  <font size="4"> 
 <div id="wrap">
        <form action="" id="food item" onsubmit="return false;">
        <div>
 <pre>
<center>TABLE NO:<select name="table"></center>
<option value="1"selected>1</option><br>
<option value="2">2</option><br>
<option value="3">3</option><br>
<option value="4">4</option><br>
<option value="5">5</option><br>
<option value="6">6</option><br>
</select>
</pre>
<pre>
 <div class="cont_order">
 <fieldset>
 <color="purple"><i><b><center><legend>Ordered Food</legend></center></b></i>
   <label class='radiolabel'><input type="checkbox"  name="selectedfood" value="Cheese Sandwich"/>Cheese Sandwich - serves 2 people (Rs.100)</label> <select name="a"  onchange="calculateTotal()"><option value="1"selected>1</option><br>
<option value="2">2</option><br>
<option value="3">3</option><br>
<option value="4">4</option><br>
<option value="5">5</option><br>
<option value="6">6</option>
</select><br>
   <label class='radiolabel'><input type="checkbox"  name="selected food" value="chicken Burger"/>Chicken Sandwich - serves 1 people (Rs.200)</label> <select name="b" onchange="calculateTotal()">Chicken Burger<option value="1"selected>1</option><br>
<option value="2">2</option><br>
<option value="3">3</option><br>
<option value="4">4</option><br>
<option value="5">5</option><br>
<option value="6">6</option>
</select><br>
   <label class='radiolabel'><input type="checkbox"  name="selectedfood" value="Popcorn Chicken"/>Popcorn Chicken - serves 8 people (Rs.300)</label> <select name="c"  onchange="calculateTotal()">Popcorn Chicken<option value="1"selected>1</option><br>
<option value="2">2</option><br>
<option value="3">3</option><br>
<option value="4">4</option><br>
<option value="5">5</option><br>
<option value="6">6</option>
</select><br> 
   <label class='radiolabel'><input type="checkbox"  name="selectedfood" value="Hot Wings"/>Hot Wings - serves 1 people (Rs.270)</label> <select name="d"  onchange="calculateTotal()">Hot Wings<option value="1"selected>1</option><br>
<option value="2">2</option><br>
<option value="3">3</option><br>
<option value="4">4</option><br>
<option value="5">5</option><br>
<option value="6">6</option>
</select><br>
   <label class='radiolabel'><input type="checkbox"  name="selectedfood" value="Grilled Chicken"/>Grilled Chicken - serves 2 people (Rs.120)</label> <select name="e"  onchange="calculateTotal()">Grilled Chicken<option value="1"selected>1</option><br>
<option value="2">2</option><br>
<option value="3">3</option><br>
<option value="4">4</option><br>
<option value="5">5</option><br>
<option value="6">6</option>
</select><br>
   <label class='radiolabel'><input type="checkbox"  name="selectedfood" value="Dips Bucket"/>Dips Bucket -  serves 5 people (Rs.180)</label> <select name="f"  onchange="calculateTotal()">Dips Bucket<option value="1"selected>1</option><br>
<option value="2">2</option><br>
<option value="3">3</option><br>
<option value="4">4</option><br>
<option value="5">5</option><br>
<option value="6">6</option>
</select><br>
</pre>

<script>var Amount=getorderedfood*(5/100)
    document.getElementById("totalprice").innerHTML = Amount;
</script>
    <p><b>Total Amount for Ordered Food:Rs. <br>      (Inclusive of tax:5%)</b></p>
</fieldset>
</div>
</body>
</html>

<html>
<head>
<title>restauranta</title>
</head>
<body>
  <body bgcolor="lightgrey">
<center><form action="action_page.php"><input type="submit" value="Submit">
</form></center> 
</body>
</html>




