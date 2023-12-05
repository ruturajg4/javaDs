<html>
<head>
<script type="text/javascript">
function msg(){
alert("Hello");
}
</script>
</head>
<body>
<p>Welcome to Javascript</p>
<form>
<input type="button" value="click" onclick="msg()"/>
</form>
</body>
</html>

mouseover 

<html>  
<head>   
<h1> Javascript Events </h1>  
</head>  
<body>  
<script language="Javascript" type="text/Javascript">  
    <!--  
    function mouseoverevent()  
    {  
        alert("This is JavaTpoint");  
    }  
    //-->  
</script>  
<p onmouseover="mouseoverevent()"> Keep cursor over me</p>  
</body>  
</html>  

Alert

<html>
<body>
<button onclick="msg()">Click me</button>
<script type="text/javascript">  
function msg(){  
alert("Hello Alert Box");  }
  </script>
</body>
</html>

Confirm

<html>
<body>
<h1>The Window Object</h1>
<h2>The alert() Method</h2>
<p>Click the button to see line-breaks in an alert box.</p>
<button onclick="msg()">Delete</button>
<script type="text/javascript">  
function msg(){  
var v= confirm("Are u sure?");  
if(v==true){  
alert("ok");  
}  
else{  
alert("cancel");  
}  
  
}  
</script>
</body>
</html>

Prompt

<html>
<body>
<button onclick="msg()">Click me</button>
<script type="text/javascript">  
function msg(){  
var v= prompt("Who are you?");  
alert("I am "+v);  
}
  </script>
</body>
</html>

Open
<html>
<body>
<button onclick="msg()">ERP</button>
<script type="text/javascript">  
function msg(){  
open("http://www.nmvpmerp.com");   
}
  </script>
</body>
</html>


