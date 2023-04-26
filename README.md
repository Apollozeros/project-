<!DOCTYPE html>
<html>
<head>
	<title>Туристическое агентство</title>
</head>
<body>
	<header>
		<img src=" logo.jpg" height="150" width="150" alt="Логотип">
		<h1>Туристическое агентство</h1>
		<nav>
			<ul>
				<li><a href="#info">Информация</a></li>
				<li><a href="#tours">Туры</a></li>
				<li><a href="#booking">Заказ</a></li>
			</ul>
		</nav>
	</header>
	<main>
		<section id="info">
			<h2>О нас</h2>
			<p>Наша цель - помочь Вам открыть для себя красоту мира, предоставляя лучшие туристические услуги в комфортном и недорогом формате.</p>
			<h3>Как заказать тур</h3>
			<ol>
				<li>Выберите даты предполагаемого похода</li>
				<li>Укажите количество участников</li>
				<li>Укажите нужные дополнительные услуги</li>
				<li>И просто оформите заказ</li>
			</ol>
		</section>
		<section id="tours">
			<h2>Наши туры</h2>
			<p>Выберите один из наших лучших туров и отправляйтесь в незабываемое путешествие:</p>
			<img src="tour1.jpg" alt="Тур 1">
			<img src="tour2.jpg" alt="Тур 2">
			<img src="tour3.jpg" alt="Тур 3">
		</section>
		<section id="booking">
			<h2>Бронирование</h2>
			<form>
				<label for="name">ФИО:</label>
				<input type="text" id="name" required>
				<label for="phone">Номер телефона:</label>
				<input type="tel" id="phone" required>
				<label for="date">Дата тура:</label>
				<input type="date" id="date" required>
				<label for="people">Количество людей:</label>
				<input type="number" id="people" min="1" required>
				<label for="addons">Дополнительные услуги:</label>
				<textarea id="addons"></textarea>
				<input type="submit" value="Оформить заказ">
			</form>
		</section>
	</main>
	<footer>
		<img src="logo.png" alt="Логотип">
		<nav>
			<ul>
				<li><a href="#about">О нас</a></li>
				<li><a href="#contacts">Контакты</a></li>
				<li><a href="#reviews">Отзывы</a></li>
			</ul>
		</nav>
	</footer>
</body>
</html>
