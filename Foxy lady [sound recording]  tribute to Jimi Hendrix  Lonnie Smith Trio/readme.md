[v0.0.6](https://github.com/littleflute/JimiHendrix/edit/master/Foxy%20lady%20%5Bsound%20recording%5D%20%20tribute%20to%20Jimi%20Hendrix%20%20Lonnie%20Smith%20Trio/readme.md)

[show this page](https://littleflute.github.io/JimiHendrix/Foxy%20lady%20%5Bsound%20recording%5D%20%20tribute%20to%20Jimi%20Hendrix%20%20Lonnie%20Smith%20Trio)

[home](..)



<audio controls id="player"> 
  <source src="https://littleflute.github.io/JimiHendrix/Foxy%20lady%20%5Bsound%20recording%5D%20%20tribute%20to%20Jimi%20Hendrix%20%20Lonnie%20Smith%20Trio/cd/01_曲目 1.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio>
<div id="xd"> 
</div>
<script>
var d = document.getElementById("xd"); 
var html = d.innerHTML; 
for(var n=1; n<=4; n++)
{	
 	html += fNewBtn(n);

} 
d.innerHTML = html;

var p = document.getElementById("player");
function f(i)
{
    var s = "https://littleflute.github.io/JimiHendrix/Foxy%20lady%20%5Bsound%20recording%5D%20%20tribute%20to%20Jimi%20Hendrix%20%20Lonnie%20Smith%20Trio/cd/";
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



