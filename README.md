# <!DOCTYPE html>
<html lang="en">
  <head>
    <meta name="viewport" content="width=device-width,initial-scale=1">
    <meta charset="utf-8">
    <meta name="generator" content="CoffeeCup HTML Editor (www.coffeecup.com)">
    <meta name="dcterms.created" content="Sun, 03 Jul 2022 09:06:46 GMT">
    <meta name="description" content="">
    <meta name="keywords" content="">
    <title></title>
	<style>
	ul{
	   background-color:rgb(12, 141, 109);
	   list-style-type:none;
	   overflow:hidden;
	   padding:0;
	   margin:0;


	 }
	li{
	float:left;
	
    } 
	li a, .dpbtn{
     text-align:center;
	 color:#FFFFD0;
     text-decoration:none;
	 display:inline-block;
	 padding:4% 6%;
	 }
	li:hover{
	background-color:rgb(18, 211, 163) } 
	
	.content{
	  display: none;
  	  position: absolute;
	  top:50px;
  	  background-color: #f9f9f9;
  	  min-width: 160px;
  	  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  	  z-index: 1;
	}
	.drop{
	display:inline-block;
	 }
	.drop:hover content{
	display:block;

	 }
	</style>
    
    <!--[if lt IE 9]>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/html5shiv/3.7.3/html5shiv.js"></script>
    <![endif]-->
  </head>
  <body>
  <ul>
  <li><a href="#">L1</a></li>
  <li><a href="#">L2</a></li>
  <li class="drop"><a class="dpbtn" href="#">L3</a></li>
  <div class=content>
  	   <a href="#">L1</a>
	   <a href="#">L2</a>
	   <a href="#">L3</a>
  </div>
  <li><a href="#">L4</a></li>
  <li style="float:right;" ><a href="#">L5</a></li>
  </ul>
  </body>
</html>second
