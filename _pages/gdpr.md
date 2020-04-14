---
permalink: /gdpr/
title: "GDPR29"
---


# GDPR Page
<p>
  hello before
  <p>
<script>

document.write("hello<br>");
var x = document.getElementsByTagName("ARTICLE");
var y = x.getElementsByClassName("page");
document.write("scroll width: " + y[0].scrollWidth);


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

