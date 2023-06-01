# htmlcss
style.css  
	body{  
		background-image: url(„images/bg.jpg”);  
		background-repeat: no-repeat;  
		background-attachment: fixed;  
}  
Osztály kijelölő szelektor  
.jkr {  
	border-style: solid  
border-color: #1a1e21;  
	border-width: 2px;  
	box-shadow:2px;  
}  
pl.<li><a href=”mappanev/houses.html” class=”jkr”>Houses</a></li>    
vagy egy mappával feljebb  ../  
<div>  
	<img src=”jkr.jpg” style=”width:30%; height:30%;” class=”img-fluid jkr”/>  
</div>  
CSS file importálása  
	<html>  
		<head>  
			<link rel=”stylesheet” href=”style.css”>  
			<title>Files</title>  
		</head>  
		<body>  
			<a href=”index.html”>Back</a>  
	</html>  
Vízszintesen görgethető  div.ex1{  
					   overflow: scroll;  
  }  
	vagy <div class=”table-data” style=”overflow:scroll;”>  
Tábla középre igazítva  CSS fileba   td {    
						text-align: center;    
}    
     			vagy <td style=”text-align: center;”>    
Reszponziv osztály  <div class=”table-data table-responziv”>    
  

