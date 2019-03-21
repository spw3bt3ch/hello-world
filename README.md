# hello-world
This is a repository on Microsoft Trademark with HTML and CSS
<!DOCTYPE html>
<html>
	
	<head>
		<title>JS Reminder</title>
		<script type="text/javascript"></script>
		<style>
			
			.background{
				
				width: 500px;
				height: 500px;
				background-color: white;
				position: relative;
				left: 500px;
				top: 90px;
				border: 1.5px grey solid;
			}
			
			.sq{
				
				width: 100px;
				height: 100px;
				margin: 10px;
				
			}
			#win1{
				background-color: red;
				position: relative;
				left: 135px;
				top: 150px;
			}
			#win2{
				background-color: #019FE8;
				position: relative;
				top: 155px;
				left: 135px;
			}
			#win3{
				background-color: #75AC00;
				position: relative;
				left: 250px;
				top: -70px
			}
			#win4{
				background-color: yellow;
				position: relative;
				left: 250px;
				top: -65px;
			}
			button{
				position: relative;
				left: 180px;
				width: 100px;
				background-color: white;
				color: darkred;
				font-weight: bold;
				border-radius: 5px;
			}
			#Microsoft{
				text-align: center;
				color: darkred;
			}
		</style>
	</head>
	<body>
		<h1 id="Microsoft">MICROSOFT NIGERIA</h1>
		<div id="windows" class="background">
			<div id="win1" class="sq"></div>
			<div id="win2" class="sq"></div>
			<div id="win3" class="sq"></div>
			<div id="win4" class="sq"></div>
			<button id="btn">PLAY</button>
		</div>
	</body>
	<script>
		
		document.getElementById("btn").onclick = function(){
			alert("You're about to commence a Microsoft game.");
		}
		
		document.getElementById("background").onclick = function(){
			document.getElementById("background").style.backgroundColor = "#9CB1E2";
		}
		
	</script>
</html>
