<div align="center">

## Proper Indentation


</div>

### Description

Teaches the basics of Proper Indentation in your php source.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Steve Oliver](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/steve-oliver.md)
**Level**          |Beginner
**User Rating**    |4.3 (26 globes from 6 users)
**Compatibility**  |PHP 3\.0, PHP 4\.0
**Category**       |[Coding Standards](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/coding-standards__8-33.md)
**World**          |[PHP](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/php.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/steve-oliver-proper-indentation__8-288/archive/master.zip)





### Source Code

I think it is a basic coding standard to Indent each function, loop, etc. This not only helps others that may be working with your source, But it also helps when you go back and look at your source. Below are some examples of right and wrong.<br>
<br>
wrong way:<br>
if($foo==""){$var="1");}<br>
should be:<br>
if($foo=="")<br>
{<br>
&nbsp;&nbsp;&nbsp;$var="1";<br>
}<br>
<br>
wrong way:<br>
While(List($blah)=mysql_fetch_row($results)){<br>
if($blah==""){echo $blah;}else{echo "none";}}<br>
<br>
should be:<br>
While(List($blah)=mysql_fetch_row($results))<br>
{<br>
&nbsp;if($blah=="")<br>
&nbsp;{<br>
&nbsp;&nbsp;&nbsp;echo $blah;<br>
&nbsp;}<br>
&nbsp;else<br>
&nbsp;{<br>
&nbsp;&nbsp;&nbsp;echo "none";<br>
&nbsp;}<br>
}<br>
<br>
wrong way:<br>
function doit($var){<br>
if($var==""){$var="false";}else{$var="true";}<br>
return $var;}<br>
<br>
should be:<br>
function doit($var)<br>
{<br>
&nbsp;if($var=="")<br>
&nbsp;{<br>
&nbsp;&nbsp;&nbsp;$var="false";<br>
&nbsp;}<br>
&nbsp;else<br>
&nbsp;{<br>
&nbsp;&nbsp;&nbsp;$var="true";<br>
&nbsp;}<br>
&nbsp;return $var;<br>
}<br>
<br>
I think you get the basic Idea. Although it may seem long and drawn out, trust me, it will help you in the long run.<br><br>
-Steve

