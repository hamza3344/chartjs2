<!-- 3D Isosurface -->
<head>
	<script src='https://cdn.plot.ly/plotly-2.16.1.min.js'></script>
</head>
<body>
	<div id='mydiv'></div>
</body>
<script>
	var data=[{
		type:"isosurface",
		x:[0,0,0,0],
		y:[0,1,0,1],
		z:[1,1,0,0],
		value:[1,2,3,4],
		isomin:2,
		isomax:4,
		colorscale:"Reds"
	}];
	var layout={};
	Plotly.newPlot('mydiv',data,layout,{showSendToCloud:true,responsive:true});
	</script>
