<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
</head>
<body>

<h1></h1> Pick your favourite season </h1>

Pick you favorite season.<div class="container">
  <img src="snow.jpeg" alt="Snow" style="width:20%">
  <button type="button" onclick="Winter()">Winter</button>
  <img src="sun.jpg" alt="Sun" style="width:20%">
  <button type="button" onclick="Summer()">Summer</button>
  <img src="Autumn.jpg" alt="Autumn" style="width:20%">
   <button type="button" onclick="Autumn()">Autumn</button>
  <img src="Spring.jpg" alt="Spring" style="width:20%">
    <button type="button" onclick="Spring()">Spring</button>
</div>

<p id="demo1"></p>


<script>

function Winter() {
document.getElementById("demo1").style.color = "blue";
document.getElementById("demo1").style.fontFamily = "Arial";
document.getElementById("demo1").style.fontSize = "larger";

  document.getElementById("demo1").innerHTML = "You Like Winter";

}
function Summer() {
document.getElementById("demo1").style.color = "Green";
  document.getElementById("demo1").innerHTML = "You Like Summer";
  document.body.style.backgroundColor = "Green";
}



function Autumn() {
document.getElementById("demo1").style.color = "Yellow";
  document.getElementById("demo1").innerHTML = "You Like Autumn";
  document.getElementById("demo1").style.backgroundColor = "red";

}
function Spring() {
document.getElementById("demo1").style.color = "Red";
  document.getElementById("demo1").innerHTML = "You Like Spring";

}

</script>

</body>
