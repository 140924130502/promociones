<html>
<head> 
	<meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Promociones </title>
<style>
	* {
		box-sizing: border-box;
	}

	body {
		font-family: century ghotic; 
		padding: 50px;
		background: #FFFFCC;
	}

	/* Header/Blog Title */
	.header {
		padding: 30px; 
		text-align: center; 
		background: yellow;
	}

	.header h1 { 
		font-size: 60px;
	}

	/* Style the top navigation bar*/
	.topnav {
		overflow: hidden; 
		background-color: #663300;
	}

	/* Style the topnav links */ 
	.topnav a {
		float: left;
		display: block; 
		color: #ffffff; 
		text-align: center;
		padding: 16px 16px; 
		text-decoration: none;
	}

	/* Change color on hover */ 
	.topnav a:hover {
		background-color: #ffffff; 
		color: black;
	}

	/* Create two unequal columns that floats next to each other / / Left column */
	.leftcolumn {
		float: left; 
		width: 75%;
	}

	/* Right column */
	.rightcolumn {
		float: left; 
		width: 25%;
		background-color: #663300; 
		padding-left: 10px;
	}

	/* Fake image */ 
	.fakeimg {
		background-color: #ffffff; 
		width: 100%; 
		padding: 20px;
	}

	/* Add a card effect for articles */ 
	.card {
		background-color: white;
		padding: 20px; 
		margin-top: 20px;
	}

	/* Clear floats after the columns */ 
	.row::after{
		content: ""; 
		display: table; 
		clear: both;
	}

	/* Footer */ 
	.footer{
		padding: 20px; 
		text-align: center; 
		background: #ddd; 
		margin-top: 20px;
	}

/*Responsive layout - when the screen is less than 800px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 800px) {
	.leftcolumn, .rightcolumn {
		width: 100%;
		padding: 0;
	}
}

/* Responsive layout - when the screen is less than 400px wide, make the navigation links stack on top of each other instead of next to each other */ 
@media screen and (max-width: 800px){
	.topnav a {
		float: none; 
		width: 100%;
	}
}
</style> 
</head>
<body>
	<div class="header">
		<h1 > "Promociones" </h1>

	</div>

	<div class="topnav">
		<a href="http://localhost/UV/men%C3%BA.html"> Menú </a> 
		<a href="http://localhost/UV/ubicaci%C3%B3n.html"> Ubicación </a> 
		<a href="http://localhost/UV/promociones.html"> Promociones </a>
		<a href="http://localhost/UV/sitioweb.html" style="float:right"> Inicio</a>
	</div>

	<div class="row">
		<div class="leftcolumn">
			<div class="card">
				<h1> ¡¡ NUESTRAS PROMOCIONES!!</h1>
				<div class="resposive">
		<div class="gallery">
			<a target="_blank" href="img/taco9.jpg">
				<img src="img/taco9.jpg" alt="taco9" width="1300" height="1300">
			</a>
		</div>
	</div>
	<div class="fakeimg" style="height:50px;"></div> 
					
				</div> 
				<div class="card"> 
					<h1>  Promociones validas en todas las Sucursales </h1>
					<div class="fakeimg" style="height:0px;"></div> 
							<style>
		.contenedor {
            width: 80%;
            padding: 20px;
            border: 2px solid gray;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
            margin: 0 auto;
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 10px;
        }
        

        .caja {
            width: 100%;
            height: 150px;
            padding: 1px;
            margin: 10px;
            border: 1px solid #ccc;
            text-align: center;
            line-height: 150px;
            font-size: 25px;
            color: white;
            
        }
        
		.caja1 {
            background-color: #E36B2C;
        }
        
        .caja2 {
            background-color: #EF280F;
        }
        
        .caja3 {
            background-color: #FF7F50;
        }
        
        .caja4 {
            background-color: #D2691E;
        }
        </style>
        <head>
        	 <div class="contenedor">
        <div class="caja caja1">Sucursal Formando Hogar.</div>

        <div class="caja caja2">Sucursal Reforma.</div>

        <div class="caja caja3">Sucursal La Fragua.</div>

        <div class="caja caja4">Sucursal Lomas 4.</div>
    </div>
        </head>

			</div> 
		</div>

		<div class="rightcolumn">
			<div class="card">
				

		<h2 text= "center">¡ Tacos totalmente irresistibles!</h2>
		<div class="gallery">
			<a target="_blank" href="img/taco1.jpg">
				<img src="img/taco1.jpg" alt="taco1" width="500" height="400">
			</a>
		</div>
				<div class="pizza2img" style="height: 70px;"></div> 

			</div> 

			<div class="card"> 
				<h1 text= "center"> Nuestras Redes</h1> 
			<div class="card">
		<div class="gallery">
			<a target="_blank" href="img/taco4.jpg">
				<img src="img/taco4.jpg" alt="taco4" width="450" height="400">
			</a>
		</div>
				<h3 text= "center">¡ No olvides seguirnos en nuestras redes sociales!</h3>
				<div class="pizza4img" style="height: 50px;"></div>
			</div>
		</div>
	</div>
	<div class="footer"> 

		<h2>www.TaqueAMORdidaPerfecta.com</h2>
		<h2> Contacto: 2256-874-102</h2>
		<h2> Horario de atención</h2>
		<h3> Lun-Vie:   12:00 a  22:00</h3>
		<h3> Sab-Dom:   10:00 a  24:00</h3>
		<div class="pizza4img" style="height: 200px;"></div>
	</div>
</body> 
</html>
