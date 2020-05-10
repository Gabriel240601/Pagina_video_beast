# Pagina_video_beast
Es una simple pág que muestra un video
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<meta http-equiv="X-UA-Compatible" content="ie=edge">	
	
        <link href="https://vjs.zencdn.net/7.7.6/video-js.css" rel="stylesheet" />
           <script src="https://vjs.zencdn.net/ie8/1.1.2/videojs-ie8.min.js"></script>
           <link rel="stylesheet" href="css/video-js.css">
           <script src="js/video.js"></script>
	<link rel="stylesheet" href="css/video-js.css">
	<script src="js/video.js"></script>
	
	<link href="https://fonts.googleapis.com/css?family=Open+Sans:300,400" rel="stylesheet">
	<link rel="stylesheet" href="css/estilos.css">
	<title>Video.js</title>
        
        <link rel="stylesheet" href="D:\6__FundamentosDiseñoWeb\BlogWeb\BlogWeb\src\externoBlog3.css" type="text/css">
</head>
<body>
	<header>
		<h1 class="titulo">Openings</h1>
	</header>

	<main>
            
        
        
		<div class="contenedor">
                    
        
        
     
                    
                    
                    
			<video class="fm-video video-js vjs-16-9 vjs-big-play-centered" data-setup="{}" controls id="fm-video">
				<source src="video/Beastars.mp4" type="video/mp4">
			</video>
                    
	
			<article>
				<h2>BEASTARS</h2>
                                  <img src="BEASTARS.jpg" alt="" title="demon Slayer">
                                <h2 id="subtitulo">Descripción:</h2>
				<p>La historia se desarrolla en un mundo de animales antropomórficos civilizados con una división cultural entre carnívoros y herbívoros.
            Legoshi, un gran lobo gris, es un estudiante tímido y tranquilo de la Academia Cherryton, donde vive con varios estudiantes carnívoros,
            incluido su amigo labrador, Jack. Como miembro del club de teatro de la escuela, Legoshi trabaja como escenógrafo y apoya a los actores 
            del club, encabezados por el alumno estrella Rouis, un ciervo rojo.</p><br />
	
				<p></p>
			</article>
		</div>
	</main>

	<script>
		var reproductor = videojs('fm-video', {
			fluid: true
		});
	</script>
</body>
</html>
