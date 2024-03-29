+++
title = 'quadtree_rs'
date = 2024-03-29T11:28:59-05:00
draft = false
+++

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Quadtree Visualization</title>
    <style>
    body {
	position: absolute;
	top: 0;
	left: 0;
	width: 100%;
	height: 100%;
	display: flex;
	flex-direction: column;
	align-items: center;
	justify-content: center;
    }
    </style>
  </head>
  <body>
    <noscript>This page contains webassembly and javascript content, please enable javascript in your browser.</noscript>
    <canvas id="quadtree-canvas"></canvas>
	{{<quadtree>}}
  </body>
</html>
