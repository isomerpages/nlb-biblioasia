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

<h1>Responsive Flexbox</h1>

<p>In this example, we change the percentage of flex to create different layouts for different screen sizes.</p>
<p><b>Resize the browser window to see that the direction changes when the 
screen size is 800px wide or smaller.</b></p>

<div class="flex-container">
  <div class="flex-item-left">1</div>
  <div class="flex-item-right">2</div>
</div>

</body>
</html>