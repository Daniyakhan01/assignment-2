# assignment-2
1.<script language="javascript">  
     function ChangeColor()   
     {  
          document.getElementById('btn1').style.backgroundColor = 'Red';  
          setTimeout("ChangeColor2()", 2000);  
     }  
  
     function ChangeColor2()   
     {  
          document.getElementById('btn1').style.backgroundColor = 'Pink';  
          setTimeout("ChangeColor3()", 2000);  
     }  
  
     function ChangeColor3()   
     {  
          document.getElementById('btn1').style.backgroundColor = 'Green';  
          setTimeout("ChangeColor4()", 2000);  
     }  
  
     function ChangeColor4()   
     {  
          document.getElementById('btn1').style.backgroundColor = 'Red';  
     }  
</script>  

2.var buttonShort = document.createElement("button");
buttonShort.innerHTML = "Generate Short Password";

var body = document.getElementsByTagName("body")[0];
body.appendChild(buttonShort);

buttonShort.addEventListener ("click", function() {
  var newWindow = window.open();
  newWindow.document.write("The generated Password is: '" + short() + "'");
  newWindow.focus()
});

3.document.getElementById("button5").addEventListener(
  "click",
  function() {
    document.getElementById("box").remove();
  }
);
<!-- <script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.1.0/jquery.min.js"></script> -->

<p>Press the buttons to change the box!</p>
<div id="box" style="height:150px; width:150px; background-color:orange; margin:25px"></div>

<button id="button1">Grow</button>
<button id="button2">Blue</button>
<button id="button3">Fade</button>
<button id="button4">Reset</button>
<button id="button5">Surprise</button>

4.document.getElementById("btn1").onclick = function() {
  document.getElementById("output").style.visibility = "hidden";
}
<input id="btn1" type="button" value="Click me" onclick="onClick1()" style="height: 100px; width: 100px;">
<div style="margin-top: 40px;"></div>
<div id="output">
  <img src="/images/person1.jpg">
  <img src="/images/person1.jpg">
  <img src="/images/person1.jpg">
  <img src="/images/person1.jpg">
  <img src="/images/person1.jpg">
</div>
