[v0.0.2](https://github.com/littleflute/JimiHendrix/edit/master/Power of soul-a tribute to Jimi Hendrix/readme.md)
[show this page](https://littleflute.github.io/JimiHendrix/Power of soul-a tribute to Jimi Hendrix)

[home](..)



<audio controls id="player"> 
  <source src="https://littleflute.github.io/JimiHendrix/Power of soul-a tribute to Jimi Hendrix/cd/01_曲目 1.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio>
<div id="xd"> 
</div>
<script>
var d = document.getElementById("xd"); 
var html = d.innerHTML; 

html += fNewBtn(1);
html += fNewBtn(2);
html += fNewBtn(3);
html += fNewBtn(4);
html += fNewBtn(5);
html += fNewBtn(6);
html += fNewBtn(7);
html += fNewBtn(8); 
 
d.innerHTML = html;

var p = document.getElementById("player");
function f(i)
{
    var s = "https://littleflute.github.io/JimiHendrix/Power of soul-a tribute to Jimi Hendrix/cd/";
    if(i<10) 
    {
    	s += "0";
    } 
    s += i;
    s += "_曲目 ";
    s += i;
    s += ".mp3";
    
	p.src = s; 
    p.play();
}
function fNewBtn(i)
{
	var rHTML = "";
    rHTML = "<button onclick='f(";
    rHTML += i;
    rHTML += ");'>";
    rHTML += i;
    rHTML += "</button>";
    return rHTML;
}
</script>



