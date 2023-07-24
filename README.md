# abhidnya

//setcontent DOM

<!doctype html>
<html>
<head>
<title>The jQuery Example</title>
<script src="jquery-3.2.1.min.js"></script>
<script>
   $(document).ready(function() {
      $("#text").click(function(){
         $("p").html("The quick <b>brown fox</b> jumps over the <b>lazy dog</b>");
      });
      $("#html").click(function(){
         $("p").text("The quick <b>brown fox</b> jumps over the <b>lazy dog</b>");
      });
   });
</script>
</head>
<body>
   <p>Click on any of the two buttons to see the result</p>
   
   <button id="text">Set Text</button>
   <button id="html">Set HTML</button>
</body>
</html>

//get content DOM

<!doctype html>
<html>
<head>
<title>The jQuery Example</title>
<script src="jquery-3.2.1.min.js"></script>
<script>
   $(document).ready(function() {
      $("#text").click(function(){
         alert($("p").text());
         alert($("p").html());
      });
      $("#html").click(function(){
         alert($("div").html());
         alert($("div").text());
      });
   });
</script>
</head>
<body>
   <p><i>Mayuri</i> <b>and</b> <i>Abhidnya</i> <b>are friends.</b></p>
   <div><i>Isha</i> <b>and</b> <i>Pradnya</i> <b>are friends.</b></div>
   <button id="text">Abhidnya</button>
   <button id="html">Mayuri</button>
   

</body>
</html>


//class selector

<!DOCTYPE html>
<html>
<head>
<script src="jquery-3.2.1.min.js"></script>
<script>
$(document).ready(function(){
  $("button").click(function(){
    $(".yuti").hide();
  });
});
</script>
</head>
<body>

<h2 >Hello welcome/h2>

<p class="yuti">Hi everyone there.</p>
<p>Ghari java ata.</p>

<button>Click me</button>

</body>
</html>

//id selector

<html>
<head>
<title>The jQuery Example</title>
<script type="text/javascript"
src="jquery-3.2.1.min.js">
</script>

<script type="text/javascript" language="javascript">
         $(document).ready(function(){
            $("#myid").css("background-color","pink");
});
</script>
</head>
	
<body>
<div>
<p class="myclass">My name is Abhidnya.</p>
<p id="myid">I like pineapples.</p>
<p>Yutika is my friend.</p>
</div>
</body>
</html>


//element selector (p)

<!DOCTYPE html>
<html>
<head>
<script src="jquery-3.2.1.min.js"></script>
<script>
$(document).ready(function(){
  $("button").click(function(){
    $("p").hide();

  });
});
</script>
</head>
<body>

<h2>This is a heading</h2>

<p>Welcome</p>
<p>Hello</p>

<button>click</button>

</body>
</html>

//dblclick evehandling

<html>
<head>
<title>The jQuery Example</title>
<script src="jquery-3.2.1.min.js"></script>
<script>
   $(document).ready(function() {
      $("div").dblclick(function(){
         alert('Hi there!');
         
      });
   });
</script>
<style>
    div{padding:12px; border:2px dotted #d44b4b; width:60px;cursor:pointer; color: black;}
    .class{
       
        width: 1500px;
        height: 1000px;
        background-color:pink;
    }
    .class p{
        font-size: large;
        color: white;
    }
   
</style>
</head>
<body>
    <div class="class">
   
   <p>Click on any of the squares to see the result:</p>
   
   <div>ABHI</div>
   <div>MAYURI</div>
   <div>ISHA</div>
   </div>
</body>
</html>


//mouseenter evehandling

<!DOCTYPE html>
<html>
<head>
<script src="jquery-3.2.1.min.js"></script>
<script>
$(document).ready(function(){
    $("body").on({
        mouseenter: function(){
            $(this).css("background-color", "gray");
        },  
    });    
});
</script>
</head>
<body>
<p>Move the mouse pointer on the page to change the background color.</p>
</body>
</html>


//click

<!doctype html>
<html>
<head>
<title>The jQuery Example</title>
<script src="jquery-3.2.1.min.js"></script>
<script>
   $(document).ready(function() {
      $("div").click(function(){
         alert('Hi there!');
      });
   });
</script>
<style>
    div{ margin:10px;padding:12px; border:2px solid #666; width:60px;cursor:pointer}
    
   div{ margin:10px;padding:12px; border:2px solid #666; width:60px;cursor:pointer}
</style>
</head>
<body>
   <p>Click on any of the squares to see the result:</p>

   <div>abhi</div>
   <div>isha</div>
   <div>pradnya</div>
</body>
</html>

