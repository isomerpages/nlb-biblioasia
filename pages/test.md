---
title: test
permalink: /test
---
<html lang="en">
	<head>
		<meta charset="UTF-8">
		<meta name="viewport" content="width=device-width, intial-scale=1.0">
		<title>Document</title>
		<style>
			body{
			margin:0;
			display: flex;
						}
			.container{
			width: 90%;
			display: grid;
			grid-template-columns: repeat(auto-fit,mixmax(250px, 1fr));
			grid-gap: 20px;
		}
			.box{
			height: 200px;
			colour: white;
			border: 2px solid white;
			postition: relative;
						}
			h2{
			margin: 0;
			position: absolute;
			top: 50%;
			left: 50%;
			transform: translate(-50%, -50%);
			}
			
			</style>
	</head>
	<body>
		<div class="container">
			<div class="box">
				<h2> box 1</h2>
			</div>
						<div class="box">
				<h2> box 2</h2>
			</div>				
</body>
</html>