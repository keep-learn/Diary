##The project is just to exe how to use git
#### you can visit my own website
[website]http://www.lovezbs.com
*Hope i can be better and better
*The page is writen my markdown *

```
<?php
   $str="I am a colleage students in XianYang , i am study php , i hope 
   	i can be better and better !
   ";
   $date=date("Y-m-d H-i");
   echo "What i want say to you :".$str.$date;

?>


```
##Picture of myself 
![Taken on JiangNan university](https://avatars3.githubusercontent.com/u/9759278?v=3&s=460)

## Javascritp : Change the input style when is onfocus and blur

```
Name : <input id='test-input' type='text' />

<script type="text/javascript" src='jquery-1.10.2.js'></script>
<script type="text/javascript">
	$(function(){
		$('#test-input').focus(function(){
			$('#test-input').css('background-color','green');
		});
		$('#test-input').blur(function(){
			$('#test-input').css('background-color','red');
		});
	});
</script>

```