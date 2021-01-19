<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Dev/square</title>
	<link rel="stylesheet" type="text/css" href="styles.css">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300&display=swap" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.gstatic.com">
  <link href="https://fonts.googleapis.com/css2?family=Source+Sans+Pro&display=swap" rel="stylesheet">
</head>
<body>
	<header id="header" class="page-header">
		<div class="container">
			<a class="email" href="mailto:gomemay413@gmail.com">gomemay413@gmail.com</a>
            <a class="phone" href="tel: +996550243967">+996 550 24 39 67</a>
		</div>
	</header>
	<main id="main" class="page-main">
		<div class="container">
			<h1>Junior разработчик</h1>
			<p class="languages">Cайт разработан на языках</p>
			<img class="laptop" src="img/hero-image.svg">
			 <div class="promo"><p class="ad">Здесь могла быть ваша реклама)</p></div>
			<div class="grid">
			  <div class="html-container">
			   <p class="name-html">HTML
				  <p class="text-html">С помощью “HTML” Была создана общая структура сайта. Страница была поделена на “Шапку”, “Основное содержимое” и “Подвал”</p>
			   </p>
		      </div>
		      <div class="css-container">
		    	 <p class="name-css">CSS
		    		 <p class="text-css">С помощью “CSS” Было задано расположение каждого элемента на странице. Именно эта синяя рамка сделана с помощью “CSS” </p>
		    	 </p>
		      </div>
		      <div class="JS-container">
		      	<p class="name-js">JavaSc
		      		<p class="text-js">“JavaScript” еще не был применен на этой странице. В скорем времени это исправится</p>
		      	</p>
		      </div>
		   </div>
		</div>
	</main>
	<footer id="footer" class="page-footer">
		<div class="container">
		   <div class="footer-grid">
			<p class="ceo">©Кудайкулов Нурсултан</p>
			<p class="contact">Контакты в шапке</p>
		   </div>
		</div>
	</footer>
</body>
</html>

body {
	margin: 0;
	background-image: url(theme/Basis.jpg);
	background-repeat: no-repeat;
	background-color: #191970;
	font-family: "Open sans";
	padding-left: 200px;
	padding-right: 200px;
	font-size: 20px;
}	

header {
	display: flex;
 	
 	padding-top: 75px;
}

.email {
	font-size: 20px;
	color: rgba(137, 163, 255, 1);
	background-image: url(img/vector.svg);
	background-repeat: no-repeat;
	background-position: left;
	/*border: 2px solid #fff;*/
	padding-left: 38px;
	text-decoration: none;
}

.phone {
	font-size: 20px;
	color: rgba(137, 163, 255, 1);
	background-image: url(img/phone.svg);
	background-position: left;
	background-repeat: no-repeat;
	/*border: 2px solid #fff;*/
	padding-left: 28px;
	margin-left: 40px;
	text-decoration: none;
}

.container {
	margin: 0; 
}

main {
	/*border: 2px solid #fff;*/
}

h1 {
	color: #fff;
	font-weight: 400;
	margin-top: 243px;
	font-size: 44px;
	border-bottom: 2px solid #fff;
	width: 890px;
	padding-bottom: 13px;
	padding-left: 3px;

}

.laptop {
	margin-left: 890px;
	margin-top: -330px;
}

.ad {
	color: #fff;
	width: 130px;
	font-family: "Montserrat";
	font-size: 14px;
	background-color: rgba(30, 32, 79, 1);
	padding: 10px;
	margin-left: -200px;
	margin-top: -300px;
	text-align: center;
	line-height: 20px;
}

.promo {
	transition: all 0.5s ease;
}

.promo:hover {
	padding-left: 10px;
}

.languages {
	font-size: 36px;
	color: #fff;
	margin-top: 35px;
	border: 2px solid rgba(137, 163, 255, 1);
	border-radius: 7px;
	text-align: center;
	padding-bottom: 2px;
	width: 510px;
	font-family: 'Roboto', sans-serif;
	font-weight: 100;
}

.grid {
	display: grid;
	grid-template-columns: 247px 247px 247px;
	column-gap: 75px;
}

.name-html {
	background-image: url(img/icon-html.svg);
	background-repeat: no-repeat;
	background-position: 5px 0;
	font-family: 'Roboto', sans-serif;
	font-size: 36px;
	/*border: 2px solid #fff;*/
	width: 106px;
	padding-left: 85px;
	margin-top: 17px;
	margin-left: 25px;
	padding-top: 14px;
	padding-bottom: 14px;
}

.html-container {
	text-align: center;
	color: #fff;
	border: 2px solid rgba(246, 91, 4, 1);
	border-radius: 25px;
	width: 247px;
	height: 339px;
	margin-top: -270px;
	transition: all 0.5s ease;
}

.html-container:hover {
	padding: 10px;
}

.text-html {
	font-family: 'Source Sans Pro', sans-serif;
	text-align: center;
	font-size: 22px;
	/*border: 2px solid #fff;*/
	margin-top: -23px;
	margin-left: 15px;
	width: 209px;
}

.name-css {
	background-image: url(img/icon-css.svg);
	background-repeat: no-repeat;
	background-position: 20px 0;
	font-family: 'Roboto', sans-serif;
	font-size: 36px;
	/*border: 2px solid #fff;*/
	width: 106px;
	padding-left: 85px;
	margin-top: 17px;
	margin-left: 25px;
	padding-top: 14px;
	padding-bottom: 14px;
}

.css-container {
	text-align: center;
	color: #fff;
	border: 2px solid rgba(49, 148, 220, 1);
	border-radius: 25px;
	width: 247px;
	height: 339px;
	margin-top: -270px;
	transition: all 0.5s ease;
}

.css-container:hover {
	padding: 10px;
}

.text-css {
	font-family: 'Source Sans Pro', sans-serif;
	text-align: center;
	font-size: 22px;
	/*border: 2px solid #fff;*/
	margin-top: -23px;
	margin-left: 15px;
	width: 209px;
}

.name-js {
	background-image: url(img/Javascript.svg);
	background-repeat: no-repeat;
	font-family: 'Roboto', sans-serif;
	font-size: 36px;
	/*border: 2px solid #fff;*/
	width: 106px;
	padding-left: 85px;
	margin-top: 17px;
	margin-left: 25px;
	padding-top: 14px;
	padding-bottom: 14px;
}

.JS-container {
	text-align: center;
	color: #fff;
	border: 2px solid rgba(222, 186, 56, 1);
	border-radius: 25px;
	width: 247px;
	height: 339px;
	margin-top: -270px;
	transition: all 0.5s ease;
}

.JS-container:hover {
	padding: 10px;
}

.text-js {
	font-family: 'Source Sans Pro', sans-serif;
	text-align: center;
	font-size: 22px;
	/*border: 2px solid #fff;*/
	margin-top: -23px;
	margin-left: 15px;
	width: 209px;
}

.footer-grid {
	display: flex;
}

footer {
	margin-left: -200px;
	margin-right: -200px;
	margin-top: 100px;
	background-color: rgba(35, 36, 73, 1);
	padding-bottom: 10px;
	padding-top: 10px;
	color: #fff;
	font-family: "Montserrat";
	font-size: 18px;
}

.ceo {
	/*border: 1px solid #fff;*/
	margin-left: 40px;
}

.contact {
	/*border: 1px solid #fff;*/
	margin-left: auto;
	margin-right: 40px;
}
