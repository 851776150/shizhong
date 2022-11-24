<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>21016021731</title>
	<style type="text/css">
				
				#all{
					position: absolute;
					left:50%;
					top:50%;
					transform: translate(-50%, -50%);
					text-align: center;
				}

				#hh{
				 height: 80px;
				 width: 500px;
				 background-color: lawngreen;
				 float: left;
				 font-size: 30px;
				 text-align: center;
				 line-height: 30px;
							}

</style>
</head>
<body>
<div id="all">
<div id="hh">
<div id="times">
</div>
<script type="text/javascript">
    function  getDate(){
        var date=new Date();
        var yyyy=date.getFullYear();  
        var MM=date.getMonth();       
        var dd=date.getDate();        
        var hh=date.getHours();       
        var mm=date.getMinutes();     
        var ss=date.getSeconds();
		var tt=date.getDay()
        var div1=document.getElementById("times"); 
        div1.innerHTML =yyyy+"年"+MM+"月"+dd+"日"+hh+"点"+mm+"分"+ss+"秒"+"星期"+tt;
        
    }
    setInterval("getDate();",1000);

</script>
</body>
</html>
