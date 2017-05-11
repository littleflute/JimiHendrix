[v0.0.6](https://github.com/littleflute/JimiHendrix/edit/master/Experience%20Hendrix/readme.md)

[show this page](https://littleflute.github.io/JimiHendrix/Experience%20Hendrix)

[home](..)



<audio controls id="player"> 
  <source src="https://littleflute.github.io/JimiHendrix/Experience%20Hendrix/cd/01_曲目 1.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio>
<div id="xd"> 
</div>
<script>
var d = document.getElementById("xd"); 
var html = d.innerHTML; 
html += fNewBtn(1);
for(var n=5; n<=20; n++)
{	
 	html += fNewBtn(n);

} 
d.innerHTML = html;

var p = document.getElementById("player");
function f(i)
{
    var s = "https://littleflute.github.io/JimiHendrix/Experience%20Hendrix/cd/";
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



