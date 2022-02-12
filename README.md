

<!DOCTYPE html> 

<html lang="en"> 

<head> 

<meta http-equiv="Content-Type" content="text/html;charset=utf-8"> 

<title>HTML5</title> 

<style> 

body { 

    font-family: Verdana,sans-serif; 

    font-size: 0.9em; 

} 

div#header, div#footer { 

    padding: 10px; 

    color: White; 

    background-color:blue; 

} 

 

div#content { 

    margin: 5px; 

    padding: 10px; 

    background-color:blue; 

} 

div.article { 

    margin: 5px; 

    padding: 10px; 

    background-color:White; 

} 

div#menu ul { 

    padding: 110;  

} 

div#menu ul li { 

    display: inline; 

    margin: 12px; 

} 

</style> 

</head> 

<body> 

<div id="header"> 

<h2>SIMPLES CALCULADORA</h2> 

</div> 

 


<div id="content"> 


</div> 

<div class="article"> 


<p>

 
<head>
 <meta name="viewport" content="width=device-width, initial-scale=1">
 <title>output Tag Sample</title>
</head>

<body>

 
<h2
<span style="color:lime;"> 

MULTIPLICAR 

</span

<br>
 <form oninput="Ans.value=parseInt(Fid.value)*parseInt(Sid.value)">
  <br>
  <input type="number" id="Fid"> * <input type="number" id="Sid"> =
  <output name="Ans"></output>
 </form>

 

 
   

<span style="color:Blue;"> 

ADICIONAR

</span> 
 <form oninput="Ans.value=parseInt(Fid.value)+parseInt(Sid.value)">
  <br>
  <input type="number" id="Fid"> +<input type="number" id="Sid"> =
  <output name="Ans"></output>
 </form>


 

 
   

<span style="color:red;"> 

SUBTRAÇÃO

</span> 
 <form oninput="Ans.value=parseInt(Fid.value)-parseInt(Sid.value)">
  <br>
  <input type="number" id="Fid"> -<input type="number" id="Sid"> =
  <output name="Ans"></output>
 </form>
