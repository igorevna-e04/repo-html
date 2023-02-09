# repo-html
<!DOCTYPE html>
<html lang="ru" >
<head>
<meta charset="UTF-8">
<title>emina</title>
<style type="text/css">
a{
color: #fff;
text-decoration: none;
}
html{
background: #FFF8CC;
min-height: 100%;
font-family: Helvetica;
display: flex;
flex-direction: column;
}
body{
margin: 0;
padding: 0 15px;
display: flex;
flex-direction: column;
flex: auto;
}
h1{
margin-top: 0;
}
h1, p{
color: #006064;
}
img{
border: 0;
}
.header{
width: 100%;
min-width: 460px;
max-width: 960px;
margin: 0 auto 30px;
padding: 30px 0 10px;
display: flex;
flex-wrap: wrap;
justify-content: space-between;
box-sizing: border-box;
}
.logo{
font-size: 1.5rem;
color: #fff;
text-decoration: none;
margin: 5px 0 0 5px;
justify-content: center;
align-items: center;
display: flex;
flex: none;
align-items: center;
background: #839FFF;
width: 130px;
height: 50px;
}
.nav{
margin: -5px 0 0 -5px;
display: flex;
flex-wrap: wrap;
}
.nav-item{
background: #BDC7FF;
width: 130px;
height: 50px;
font-size: 1.5rem;
color: #fff;
text-decoration: none;
display: flex;
margin: 5px 0 0 5px;
justify-content: center;
align-items: center;
}
.sqr{
height: 300px;
width: 300px;
background: #FFDB89;
}

.main{
width: 100%;
min-width: 460px;
max-width: 960px;
margin: auto;
flex: auto;
box-sizing: border-box;
}
.box{
font-size: 1.25rem;
line-height: 1.5;
margin: 0 0 40px -50px;
display: flex;
flex-wrap: wrap;
justify-content: center;
}
.box-base{
margin-left: 50px;
flex: 1 0 430px;
}
.box-side{
margin-left: 50px;
font: none;
}
.box-img{
max-width: 100%;
height: auto;
}
.content{
margin-bottom: 30px;
display: flex;
flex-wrap: wrap;
}
.banners{
flex: 1 1 200px;
}
.banner{
background: #FFDB89;
width: 100%;
min-width: 100px;
min-height: 200px;
font-size: 3rem;
color: #fff;
margin: 0 0 30px 0;
display: flex;
justify-content: center;
align-items: center;
}
.posts{
margin: 0 0 30px 30px;
flex: 1 1 200px;
}
.comments{
margin: 0 0 30px 30px;
flex: 1 1 200px;
}
.comment{
display: flex;
}
.comment-side{
padding-right: 20px;
flex: none;
}
.comment-base{
flex: auto;
}
.comment-avatar{
background: #FFA985;
width: 50px;
height: 50px;
}
.footer{
background: #FF3366;
width: 100%;
max-width: 960px;
min-width: 460px;
color: #fff;
margin: auto;
padding: 15px;
box-sizing: border-box;
}

@media screen and  (max-width: 800px) {
.banners{
margin-left: -30px;
display: flex;
flex-basis: 100%;
}
.banner{
margin-left: 30px;
}
.posts{
margin-left: 0;
}
}
@media screen and  (max-width: 600px) {
.content{
display: block;
}
.banners{
margin: 0;
display: block;
}
.banner{
margin-left: 0;
}
.posts{
margin: 0;
}
}
</style>
</head>
<body>
<header class="header">
<a class="logo">
LOSO
</a>
<nav class="nav">
<a href="#posts" class="nav-item">Посты</a>
<a href="#comments" class="nav-item">Комменты</a>
<a href="#footer" class="nav-item">Подвал</a>
<a href="#posts" class="nav-item">Посты2</a>
</nav>

</header>
<main class="main">
<div class="box">
<div class="box-base">
<h1>Природа</h1>
<p>Природа — материальный мир Вселенной, в сущности — основной объект изучения естественных наук.</p>
</div>
<div class="box-side">
<div class="sqr">

</div>
</div>
</div>
<div class="content">
<div class="banners">
<div class="banner">Баннер 1</div>
<div class="banner">Баннер 2</div>
<div class="banner">Баннер 3</div>
</div>
<div class="posts"  id="posts">
<div class="post">
<h1>Пост #1</h1>
<p>Совокупность естественных условий или какая-л. часть их на Земле (рельеф, растительный и животный мир, климатические условия и т. п.). Северная природа. Тропическая природа.</p>
</div>
<div class="post">
<h1>Пост #2</h1>
<p>Совокупность естественных свойств, склонностей, потребностей человека, человеческого организма. Когда-нибудь придется же ему Брить бороду себе, что несогласно С природой дамской. Пушкин, Домик в Коломне.</p>
</div>
<div class="post">
<h1>Пост #3</h1>
<p> Сущность, основное свойство чего-л. Он первый уловил истинную природу оппозиции молодого офицерства. Л. Соболев, Первый слушатель. Это явление получило очень большое значение для понимания природы света. С. Вавилов, Советская наука на службе Родине.</p>
</div>
</div>
<div class="comments"  id="comments">
<div class="comment">
<div class="comment-side">
<div class="comment-avatar">

</div>
</div>
<div class="comment-base">
<h1 class="comment-title">Комментарий #1</h1>
<p>Безмерная красота природы доступна каждому. Никто не может думать о том, чтобы забрать домой восход или закат.</p>
</div>
</div>
<div class="comment">
<div class="comment-side">
<div class="comment-avatar">

</div>
</div>
<div class="comment-base">
<h1 class="comment-title">Комментарий #2</h1>
<p>Ошибкой было то, что мы отошли от природы! В ее разнообразии, красоте, жестокости и бесконечном, несравненном величии заключен весь смысл жизни.</p>
</div>
</div>
<div class="comment">
<div class="comment-side">
<div class="comment-avatar">

</div>
</div>
<div class="comment-base">
<h1 class="comment-title">Комментарий #3</h1>
<p>Лес притягивает сердца людей не столько из-за своей красоты, сколько из-за качества воздуха, исходящего от старых деревьев, который так чудесно меняется и обновляет усталый дух.</p>
</div>
</div>
</div>
</div>
</main>
<footer class="footer"  id="footer">
Если есть вопросы звоните на горячую линию 8-956-456-89-78
</footer>
</body>
</html>
