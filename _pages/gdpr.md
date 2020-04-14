---
permalink: /gdpr/
title: "GDPR48"
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
document.write("scroll width: " + x1[0].scrollWidth  + "<br>");

/*
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
*/
</script>

<p>
  hello after
<p>

<script>
function resizer(id)
{
  
console.log("hello from resizer"); 
/*
var doc=document.getElementById(id).contentWindow.document;

var body_ = doc.body, html_ = doc.documentElement;

var height = Math.max( body_.scrollHeight, body_.offsetHeight, html_.clientHeight, html_.scrollHeight, html_.offsetHeight );
var width  = Math.max( body_.scrollWidth, body_.offsetWidth, html_.clientWidth, html_.scrollWidth, html_.offsetWidth );
*/

var x1 = document.getElementsByTagName("article");
var width = x1[0].scrollWidth

//document.write("hello3a<br>"); 
//document.write("scroll width: " + x1[0].scrollWidth  + "<br>");
console.log("hello from resizer2 " + width); 
var iFrameobj =document.getElementById(id);
console.log("hello from resizer3 " + iFrameobj); 
iFrameobj.style.height=5000;
iFrameobj.style.width=width;
console.log("hello from resizer4 "); 
}
</script>

<IFRAME SRC="gdprcollapse" id="iframeGDPR"  onLoad="resizer('iframeGDPR');"></iframe>
<!-- 
<IFRAME SRC="gdprcollapse" id="iframeGDPR"  onLoad="resizer('iframeGDPR');"></iframe>

<iframe width="1000" height="5000" id="iframeGDPR" src="gdprcollapse" frameborder="0" allow="encrypted-media" allowfullscreen></iframe>
-->

