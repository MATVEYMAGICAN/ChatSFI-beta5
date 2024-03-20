<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="reset.css">
    <link rel="stylesheet" href="style.css">
    <link rel="icon" href="image/kandinsky-download-1707232453976-fotor-20240313103358.ico">
    <title>ChatSFI</title>
</head>

<body>
    <ul id="nav">
        <a href="https://t.me/ChatSFI_bot">
            <li id="search"><b>Let's go</b></li>
        </a>
    </ul>
    <div class="title">
        <div class="title-filter"></div>
        <h2 class="chat-sfi">Chat<span class="sfi">SFI</span></h2>
        <h3 class="SFI"><a href="https://t.me/ChatSFI_bot"><span>S</span>earch <span>F</span>or<span>
                    I</span>nformation</a></h3>
    </div>
    <div class="idea">
        <h3>Идея</h3>
        <div class="title-filter"></div>
        <div class="blocks-idea">
            <div class="one-idea">
                <div class="content">
                    <p>
                        У каждого есть приложение 'Электронная школа', и не у всех оно работает корректно, иногда
                        приходится заново заходить в аккаунт, да и сама проблема в том, что его нужно скачивать, а если
                        заходить туда через сайт, то чаще всего нужно каждый раз писать данные аккаунта. Мы также
                        столкнулись с этими проблемами и долго думали как их решить.
                    </p>
                    <div class="number">
                        1
                    </div>
                </div>
            </div>
            <div class="two-idea">
                <div class="content">
                    <p>
                        Нужен был способ решить все имеющиеся проблемы, чтобы эти данные были в том приложении, которое
                        у
                        всех есть, чтобы оно не требовало постаянной аутентификации и работало на 100/100. Так мы и
                        придумали сделать информацию об уроках в 'Telegram'. Но оставался вопрос, каким
                        образом нам всё это поместить туда?
                    </p>
                    <div class="number">
                        2
                    </div>
                </div>
            </div>
            <div class="three-idea">
                <div class="content">
                    <p>
                        На самом деле, нам не пришлось долго думать, мы практически сразу поняли что всё это может
                        делать
                        'Telegram-bot'. Название мы так же быстро придумали, ведь бот нам нужен для поиска информации:
                        'Search For Information' - 'SFI'. Над
                        реализацией мы еще работаем, так что остался 1 самый основной и сложный пункт.
                    </p>
                    <div class="number">
                        3
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="functional">
        <div class="title-filter"></div>
        <h3>Функционал</h3>
        <div class="func-blocks">
            <div class="homework">
                <h3>Домашнее задание</h3>
                <p>Что задали на завтра?</p>
            </div>
            <div class="timetable-lessons">
                <h3>Расписание уроков</h3>
                <p>Какие учебники мне класть в рюкзак?</p>
            </div>
            <div class="timetable-call">
                <h3>Расписание звонков</h3>
                <p>Когда уже закончится урок?</p>
            </div>
        </div>
    </div>
    <div class="footer">
        <div class="soc">
            <div class="kapustyn">
                <h3 class="pers">Капустин Федор</h3>
                <div class="inf">
                <h3>Telegram</h3>
                <p>https://t.me/rpoi3</p>
                <h3>What's Up</h3>
                <p>+7 923 106-84-32</p>
                <h3>Почта</h3>
                <p>rpoi.strelok@gmail.com</p>
                </div>
            </div>
            <div class="skovordin">
                <h3 class="pers">Сковордин Матвей</h3>
                <div class="inf">
                    <h3>Telegram</h3>
                    <p>https://t.me/Matvey2907</p>
                    <h3>What's Up</h3>
                    <p>+7 913 982-05-92</p>
                    <h3>Почта</h3>
                    <p>skovordinmatvey@bk.ru</p>
                </div>
            </div>
        </div>
    </div>
</body>

</html>
<style>
/* Reset and base styles  */
* {
	padding: 0px;
	margin: 0px;
	border: none;
}

*,
*::before,
*::after {
	box-sizing: border-box;
}

:focus,
:active {
	outline: none;
}

a:focus,
a:active {
	 outline: none;
}

/* Links */

a, a:link, a:visited  {
    color: inherit; 
    text-decoration: none;
    /* display: inline-block; */
}

a:hover  {
    /* color: inherit; */
    text-decoration: none;
}

/* Common */

aside, nav, footer, header, section, main {
	display: block;
}

h1, h2, h3, h4, h5, h6, p {
    font-size: inherit;
	font-weight: inherit;
}

ul, ul li {
	list-style: none;
}

img {
	vertical-align: top;
}

img, svg {
	max-width: 100%;
	height: auto;
}

address {
  font-style: normal;
}

/* Form */

input, textarea, button, select {
	font-family: inherit;
    font-size: inherit;
    color: inherit;
    background-color: transparent;
}

input::-ms-clear {
	display: none;
}

button, input[type="submit"] {
    display: inline-block;
    box-shadow: none;
    background-color: transparent;
    background: none;
    cursor: pointer;
}

input:focus, input:active,
button:focus, button:active {
    outline: none;
}

button::-moz-focus-inner {
	padding: 0;
	border: 0;
}

label {
	cursor: pointer;
}

legend {
	display: block;
}
@import url('https://fonts.googleapis.com/css2?family=Bruno+Ace+SC&family=Comfortaa:wght@600&display=swap');

body{
    margin:0;
    font-family: 'Comfortaa', cursive;
}

h3{
    color:rgb(0, 255, 255);
}

.title{
    width:98.9vw;
    height:100vh;
    background-image:url(image/kandinsky-download-1707232453976.png) ;
    background-size: cover;
    display: flex;
    justify-content: center;
    align-items: center;
}

.title-filter{
    width: 98.9vw;
    height: 100vh;
    position: absolute;
    background-color: rgba(0, 0, 0, 0.7);
    backdrop-filter: blur(6px);
    box-shadow: 0px 10px 10px rgba(9, 2, 93, 0.7)
}

.chat-sfi{
    color:rgb(0, 255, 238);
    position: absolute;
    font-family: 'Comfortaa', cursive;
    font-size:100px;
    transition: 1s;

}

.SFI{
    color:rgba(0, 255, 238, 0.538);
    position: absolute;
    font-family: 'Comfortaa', cursive;
    font-size:50px;
    transition: 1s;
    margin-top:160px;
}

.SFI:hover{
    color:rgb(0, 255, 255);
    transition-duration: 0.3s;
    cursor: pointer;
}

.chat-sfi span{
    color: rgb(132, 41, 223);
}

.SFI span{
    color: rgb(132, 41, 223);
}

#nav {
    list-style: none;
    margin: 0;
    padding-right: 40px;
    display: flex;
    justify-content: space-around;
    align-items: center;
    width: 101vw;
    height: 50px;
    position: fixed;
    z-index:10;
    background-color: rgba(82, 78, 78, 0.577);
    left:1px;
    text-transform: uppercase;
    color:rgba(0, 255, 255, 0.57);
    font-family: 'Comfortaa', cursive;
    box-shadow: 0 0 20px rgb(82, 78, 78);
    font-size:30px;
}

.idea{
    width:98.9vw;
    height:100vh;
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    align-items: center;
    background-image:url(https://unblast.com/wp-content/uploads/2021/01/Space-Background-Images.jpg);
}

.idea h3{
    font-size:50px;
    z-index: 100;
}

.idea .number{
    color: rgb(132, 41, 223);
    width:40px;
    height:40px;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: rgb(56, 56, 56);
    box-shadow: 0 0 10px rgb(39, 38, 38);
    font-size: 30px;
    border-radius: 5px;
    position: absolute;
    right:10px;
    bottom:10px;
}

.content{
    position: relative;
    color:rgba(0, 255, 238, 0.726);
    background-color: rgb(56, 56, 56);
    box-shadow: 0 0 20px rgb(64, 63, 63);
    width:300px;
    height:300px;
    padding:10px;
    border-radius: 10px;
    font-size: 15.9px;
}

.blocks-idea{
    display:flex;
    flex-direction: row;
    width: 95vw;
    justify-content: space-around;
    left:0;
}

.one-idea:hover{
    cursor: pointer;
    transform: scale(1.10);
    transition-duration: 0.4s;
}

.two-idea:hover{
    cursor: pointer;
    transform: scale(1.10);
    transition-duration: 0.4s;
}

.three-idea:hover{
    cursor: pointer;
    transform: scale(1.10);
    transition-duration: 0.4s;
}

.functional{
    width:98.9vw;
    height:100vh;
    background-image:url(https://unblast.com/wp-content/uploads/2021/01/Space-Background-Images.jpg);
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-around;
}

.functional h3{
    z-index: 100;
    font-size: 50px;
}

.func-blocks div{
    width:300px;
    height:150px;
    border-radius: 10px;
    background-color: rgb(56, 56, 56);
    position: relative;
    text-align: center;
    justify-content: center;
    display: flex;
    align-items: center;
    padding: 0;
    box-shadow: 0 0 20px rgb(64, 63, 63);
    flex-direction: column;
}

.func-blocks h3{
    font-size:30px;
}

.func-blocks{
    width:98.9vw;
    height:150px;
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    margin-bottom: 50px;
}

.func-blocks div:hover h3{
    transition-duration: 0.3s;
    opacity: 0;
}

.func-blocks div p{
    position: absolute;
    color:rgb(132, 41, 223);
    opacity: 0;
    font-size: 28px;
}

.func-blocks div:hover p{
    transition-duration: 0.3s;
    opacity: 1;
}

.footer{
    width:98.9vw;
    height:25vh;
    background-color: rgb(37, 37, 37);
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-around;
    position: relative;
    bottom:0px;
}

.soc{
    display: flex;
    justify-content: space-between;
    width:50vw;
    flex-direction: row;
    padding-top:-10px;
    position: relative;
}

.soc h3{
    margin-top:10px;
}

.soc p{
    color:rgb(132, 41, 223);
}

.soc h3, p:hover{
    cursor: pointer;
}</style>
