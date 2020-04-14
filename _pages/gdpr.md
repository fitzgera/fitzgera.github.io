---
permalink: /gdpr/
title: "GDPR39"
---


# GDPR Page
<p>
  hello before
  <p>
<script>

document.write("hello<br>");
var x1 = document.getElementsByTagName("article");
document.write("hello2<br>");
 document.write(x1[0].tagName + "<br>");
document.write("hello2a<br>"); 
document.write(x1.length + "<br>");
document.write("hello3<br>"); 
var y = x1[0].getElementsByClassName("*");
document.write("hello3a<br>"); 
document.write("scroll width: " + x1[0].scrollWidth);
document.write("hello36<br>"); 
document.write(y.length + "<br>");
document.write("hello4<br>"); 
document.write(y[0].className + "<br>");
document.write("hello4a<br>"); 
document.write("scroll width: " + y[0].scrollWidth);
document.write("hello5<br>"); 
document.write("hello between<br>");

x = document.getElementsByTagName("*");
l = x.length;
for (i = 0; i < l; i++) {
  document.write(x[i].tagName + "<br>");
  document.write(x[i].nodeName + "<br>");
  document.write(x[i].className + "<br>");
  document.write(x[i].id + "<br>");
  document.write(x[i].scrollWidth + "<br>");        

}


const width  = window.innerWidth || document.documentElement.clientWidth || document.body.clientWidth;  

document.write( width); 
</script>
<p>
  hello after
<p>


<iframe width="1000" height="5000" src="gdprcollapse" frameborder="0" allow="encrypted-media" allowfullscreen></iframe>

