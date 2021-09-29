---
title: test
permalink: /test
---
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

.flex-container {
  display: flex;
  flex-wrap: wrap;
  font-size: 30px;
  text-align: center;
}

.flex-item-left {
  padding: 10px;
  flex: 70%;
}

.flex-item-right {
  padding: 10px;
  flex: 30%;
}
	/* Responsive layout - makes a one column-layout instead of a two-column layout */
@media (max-width: 800px) {
  .flex-item-right, .flex-item-left {
    flex: 100%;
  }
}
</style>
</head>
<body>

<h4>The Forgotten Murals of Paya Lebar Airport
</h4>


<div class="flex-container">
  <div class="flex-item-left"><img src=" /images/vol-17-issue-2/murals/Mural_Main2.jpg"  style="float:left; width:500px; height:auto;  border:10px solid #FFFFFF; class=responsive">
</div>
  <div class="flex-item-right">Three large murals used to grace the walls of Paya Lebar Airport. Dahlia Shamsuddin has the inside story of how they came to be.

</div>
</div>

</body>
</html>