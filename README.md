# Carousel-javascript
<!DOCTYPE html>
<html>
    <header>
    	<title> Carousel</title>    
    	<link rel="stylesheet" type="text/css" href="css/style.css">	
		
		<script type="text/javascript" src="css/scripts/jquery.js"></script>
		<script type="text/javascript" src="css/scripts/jCarouselLite.js"></script>
			<script type="text/javascript">
				$(function() {
					$(".carousel").jCarouselLite({
						btnNext:".next",
						btnPrev:".prev",
						auto:3000,
						speed:1000,
						visible:3,
					})
 
				})
	   </script>
		
    </header>
    <body>
			<div id="carousel">
				<div class="carousel">
					<ul>
						<li><img src="css/imagens/dbz.jpg" alt=""/></li>
						<li><img src="css/imagens/korra1.jpg" alt=""/></li>
						<li><img src="css/imagens/korra2.jpg" alt=""/></li>
						<li><img src="css/imagens/moon.jpg" alt=""/></li>
						<li><img src="css/imagens/wolf.jpg" alt=""/></li>
						<li><img src="css/imagens/yin.jpg" alt=""/></li>
						<li><img src="css/imagens/yang.jpg" alt=""/></li>
						
					</ul>
					<button class="prev">Anterior</button>
					<button class="next">proximo</button>
			
				</div>	
			</div>
	
	</body>

</html>
