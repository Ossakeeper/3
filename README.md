<p align = "center">МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ<br>
РОССИЙСКОЙ ФЕДЕРАЦИИ<br>
ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ<br>
ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ<br>
«САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»</p>
<br><br><br><br><br><br>
<p align = "center">Институт естественных наук и техносферной безопасности<br>Кафедра информатики<br>Шинкаренко Никита Александович</p>
<br><br><br>
<p align = "center"><br><strong>Лабораторная работа №3.«HTML»</strong><br>01.03.02 Прикладная математика и информатика</p>
<br><br><br><br><br><br><br><br><br><br><br><br>
<p align = "right">Научный руководитель<br>
Соболев Евгений Игоревич</p>
<br><br><br>
<p align = "center">г. Южно-Сахалинск<br>2024 г.</p>
<br><br><br><br><br><br><br><br><br><br><br><br>

<h1 align = "center">Введение</h1>

<p><b>HTML</b> —  стандартизированный язык гипертекстовой разметки документов для просмотра веб-страниц в браузере. Веб-браузеры получают HTML документ от сервера по протоколам HTTP/HTTPS или открывают с локального диска, далее интерпретируют код в интерфейс, который будет отображаться на экране монитора.</p>
<p><b>CSS</b> — формальный язык описания внешнего вида документа, написанного с использованием языка разметки. Также может применяться к любым XML-документам, например, к SVG или XUL.</p>


<h1 style="text-align: center">Задачи</h1>
<ol>
  <li>Создать все виды заголовков с текстом "Hello world" c классом "heading".
  <li>Каждому заголовку также дать id (к прим. heading-1, heading-2...) </li>
  <li>Задать всем заголовкам цвет текста на красный </li>
  <li>Второму заголовку синий </li>
  <li>Третьему заголовку поменять задний фон на чёрный </li>
  <li>Четвертому заголовку сделать border и округлить углы </li>
  <li>Пятому заголовку создать :hover эффект (любой)</li>
  <li>Создайте 6 input с разными типами. </li>
  <li>Создать нумерованный список из 4 элементов с текстом “Нумерованный”</li>
  <li>Создать маркированный список из 4 элементов с текстом “Маркированный” и квадратным маркером.</li>
  <li>Создайте веб-страницу с зеленым фоном и белым текстом из 30 слов. </li>
  <li>Создать 6 блоков с нумерацией и такими параметрами (ширина 100px и высота 100px, зеленого цвета , внешним отступом 10px). Их родительским элементом должен быть container. </li>
  <li>Поставить все блоки по центру страницы.</li>
  <li>Добавьте тэг iframe на вашу страницу.</li>
  <li>Сделайте простую форму регистрации на сайте (Только верстка).</li>
  <li>Сделайте таблицу на странице.</li>
  <li>Создайте стиль для заголовка h1 с красным цветом текста.</li>
  <li>Установите шрифт Arial для всех параграфов на странице.</li>
  <li>Добавьте тень на блок div с помощью свойства box-shadow.</li>
  <li>Установите фоновый цвет #f0f0f0 для всего документа.</li>
  <li>Создайте анимацию, которая будет мигать красным цветом.</li>
  <li>Установите отступы внутри блока div с помощью свойства padding.</li>
  <li>Создайте стиль для ссылок, которые будут менять цвет при наведении на них курсора.</li>
  <li>Добавьте границу вокруг изображения с помощью свойства border.</li>
  <li>Создайте стиль для списка ul с маркерами в виде квадратов.</li>
  <li>Установите ширину и высоту блока div с помощью свойств width и height.</li>
  <li>Создайте стиль для таблицы, который будет делать каждую вторую строку серой.</li>
  <li>Добавьте эффект перехода при наведении на кнопку с помощью свойства transition.</li>
  <li>Установите фоновое изображение для элемента с помощью свойства background-image.</li>
  <li>Создайте стиль для формы с полями для ввода текста и кнопкой отправки.</li>
  <li>Добавьте рамку вокруг текстового поля с помощью свойства outline.</li>
  <li>Установите выравнивание текста по центру в блоке div с помощью свойства text-align.</li>
  <li>Создайте стиль для выпадающего меню с помощью псевдоэлемента :hover.</li>
  <li>Добавьте тень на текст с помощью свойства text-shadow.</li>
  <li>Создайте стиль для анимации появления элемента на странице с помощью свойства opacity.</li>
  <li>Установите шрифт размером 18 пикселей для всех заголовков на странице.</li>
</ol>




<h1 style="text-align: center">Решения</h1>

<h2 style="text-align: center">Файл 1.html(Задание 1-7)</h2>
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
</head>
<style>
    .heading {
        color: red;
    }
    #heading-2{color:blue;}
    #heading-3 {
            background-color: black;
            color: white;
    }
    #heading-4 {
            border: 2px solid black;
            border-radius: 10px;
    }
    #heading-5:hover {
            color: yellowgreen;
    }
</style>
<body>
    <h1 class="heading">Hello world</h1>
    <h2 class="heading">Hello world</h2>
    <h3 class="heading">Hello world</h3>
    <h4 class="heading">Hello world</h4>
    <h5 class="heading">Hello world</h5>
    <h6 class="heading">Hello world</h6>

    <h1 id="heading-1" class="heading">Hello world</h1>
    <h2 id="heading-2" class="heading">Hello world</h2>
    <h3 id="heading-3" class="heading">Hello world</h3>
    <h4 id="heading-4" class="heading">Hello world</h4>
    <h5 id="heading-5" class="heading">Hello world</h5>
    <h6 id="heading-6" class="heading">Hello world</h6>
</body>
</html>
```
<h2 style="text-align: center">Файл 2.html</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
</head>
<body>
<label>
    <input type="text" placeholder="Текст">
</label>
<label>
    <input type="password" placeholder="Пароль">
</label>
<label>
    <input type="number" placeholder="Числовое ">
</label>
<label>
    <input type="email" placeholder="email">
</label>
<label>
    Флажок
    <input type="checkbox">
</label>
<label>
    Поле даты
    <input type="date">
</label>
</body>
</html>
```
<h2 style="text-align: center">Файл 3.html</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
</head>
<body>
<ol>
    <li>Нумерованный</li>
    <li>Нумерованный</li>
    <li>Нумерованный</li>
    <li>Нумерованный</li>
</ol>
</body>
</html>
```
<h2 style="text-align: center">Файл 4.html</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <style>
        .sq {
            list-style-type: square;
        }
    </style>
</head>
<body>
<ul class="sq">
    <li>Маркированный</li>
    <li>Маркированный</li>
    <li>Маркированный</li>
    <li>Маркированный</li>
</ul>
</body>
</html>
```

<h2 style="text-align: center">Файл 5.html</h2>

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        body {
            background-color: green;
            color: white;
        }
    </style>
</head>
<body>
<pre>
Послушайте!
Ведь, если звезды зажигают —
значит — это кому-нибудь нужно?
Значит — кто-то хочет, чтобы они были?
Значит — кто-то называет эти плево́чки жемчужиной?
И, надрываясь
в метелях полу́денной пыли,
врывается к богу,
боится, что опоздал,
плачет,
целует ему жилистую руку,
просит —
чтоб обязательно была звезда! —
клянется —
не перенесет эту беззвездную муку!
А после
ходит тревожный,
но спокойный наружно.
Говорит кому-то:
«Ведь теперь тебе ничего?
Не страшно?
Да?!»
Послушайте!
Ведь, если звезды
зажигают —
значит — это кому-нибудь нужно?
Значит — это необходимо,
чтобы каждый вечер
над крышами
загоралась хоть одна звезда?!
</pre>
</body>
</html>
```

<h2 style="text-align: center">Файл 6.html(Задания 12-13)</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .container {
            display: flex;
        }

        .block {
            width: 100px;
            height: 100px;
            background-color: green;
            margin: 10px;
        }
    </style>
</head>
<body>
<div class="container">
    <div class="block">АБ</div>
    <div class="block">ВГ</div>
    <div class="block">ДЕ</div>
    <div class="block">ЁЖ</div>
    <div class="block">ЗИ</div>
    <div class="block">ЙК</div>
</div>
</body>
</html>
```

<h2 style="text-align: center">Файл 7.html</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
</head>
<body>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/KffVhdWAgXc?si=_6qAw1t67i8tdOs9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</body>
</html>
```

<h2 style="text-align: center">Файл 8.html</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Форма регистрации</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        .container {
            width: 300px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f2f2f2;
            border-radius: 5px;
        }

        .container h2 {
            text-align: center;
        }

        .container label,
        .container input {
            display: block;
            margin-bottom: 10px;
            box-sizing: border-box;
        }

        .container input[type="text"],
        .container input[type="email"],
        .container input[type="password"] {
            width: 100%;
            padding: 8px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }

        .container button {
            width: 100%;
            padding: 10px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
    </style>
</head>
<body>
<div class="container">
    <h2>Регистрация</h2>
    <form>
        <label for="username">Имя:</label>
        <input type="text" id="username" name="username" required>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>

        <label for="password">Пароль:</label>
        <input type="password" id="password" name="password" required>

        <button type="submit">ВВОД</button>
    </form>
</div>
</body>
</html>
```
<h2 style="text-align: center">Файл 9.html</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
        }

        th, td {
            padding: 8px;
            text-align: left;
            border-bottom: 1px solid #ddd;
        }

        th {
            background-color: #f2f2f2;
        }
    </style>
</head>
<body>
<table>
    <thead>
    <tr>
        <th>Заголовок 1</th>
        <th>Заголовок 2</th>
        <th>Заголовок 3</th>
    </tr>
    </thead>
    <tbody>
    <tr>
        <td>Ячейка 1-1</td>
        <td>Ячейка 1-2</td>
        <td>Ячейка 1-3</td>
    </tr>
    <tr>
        <td>Ячейка 2-1</td>
        <td>Ячейка 2-2</td>
        <td>Ячейка 2-3</td>
    </tr>
    <tr>
        <td>Ячейка 3-1</td>
        <td>Ячейка 3-2</td>
        <td>Ячейка 3-3</td>
    </tr>
    </tbody>
</table>
</body>
</html>
```

<h2 style="text-align: center">Файл 10.html</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <style>
        h1 {
            color: red;
        }
    </style>
</head>
<body>
<h1>ЗАГОЛОВИЩЕ</h1>
</body>
</html>
```

<h2 style="text-align: center">Файл 11.html</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <style>
        p {
            font-family: Arial, sans-serif;
        }
    </style>
</head>
<body>
<p>АРИАЛ</p>
<p>АРИАЛИЩЕ</p>
</body>
</html>
```
<h2 style="text-align: center">Файл 12.html</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Тень на блоке</title>
    <style>
        .box {
            width: 200px;
            height: 200px;
            background-color: #ffffff;
            box-shadow: 2px 2px 4px rgba(0, 0, 0, 0.4);
        }
    </style>
</head>
<body>
<div class="box"></div>
</body>
</html>
```

<h2 style="text-align: center">Файл 13.html</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Фоновый цвет документа</title>
    <style>
        body {
            background-color: #f0f0f0;
        }
    </style>
</head>
<body>
<h1>ABCDEF</h1>
<p>BABABABABA</p>
</body>
</html>
```

<h2 style="text-align: center">Файл 14.html</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Анимация мигания</title>
    <style>
        @keyframes blink {
            0% {
                background-color: white;
            }
            50% {
                background-color: red;
            }
            100% {
                background-color: white;
            }
        }

        .blink-animation {
            animation: blink 0.3s infinite;
        }
    </style>
</head>
<body>
<div class="blink-animation">ALARM!</div>
</body>
</html>
```
<h2 style="text-align: center">Файл 15.html</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Отступы внутри блока</title>
</head>
<body>
<div style="padding: 20px;">LOREM IPSUM</div>
</body>
</html>
```

<h2 style="text-align: center">Файл 16.html</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <style>
        a {
            color: blue;
            text-decoration: none;
        }

        a:hover {
            color: #5eff00;
        }
    </style>
</head>
<body>
<a href="#">LinkAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA</a>
</body>
</html>
```
<h2 style="text-align: center">Файл 17.html</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <style>
        img {
            border: 10px solid black;
        }
    </style>
</head>
<body>
<img src="https://avatars.dzeninfra.ru/get-zen_doc/3986059/pub_61643389916bac55c04bdc9c_616438963051007f8ef76331/scale_1200" alt="">
</body>
</html>
```

<h2 style="text-align: center">Файл 18.html</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <style>
        ul {
            list-style-type: square;
        }
    </style>
</head>
<body>
<ul>
    <li>A</li>
    <li>B</li>
    <li>C</li>
</ul>
</body>
</html>
```
<h2 style="text-align: center">Файл 19.html</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
   
</head>
<body>
<div style="width: 300px;height: 200px;">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Numquam, sint?</div>
</body>
</html>
```

<h2 style="text-align: center">Файл 20.html</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
        }

        table tr:nth-child(odd) {
            background-color: #f2f2f2;
        }
    </style>
</head>
<body>
<table>
    <tr>
        <th>header 1</th>
        <th>header 2</th>
    </tr>
    <tr>
        <td>a 1</td>
        <td>b 2</td>
    </tr>
    <tr>
        <td>c 3</td>
        <td>d 4</td>
    </tr>
    <tr>
        <td>e 5</td>
        <td>f 6</td>
    </tr>
</table>
</body>
</html>
```

<h2 style="text-align: center">Файл 21.html</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <style>
        .button {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            transition: background-color 0.6s ease;
        }

        .button:hover {
            background-color: yellowgreen;
        }
    </style>
</head>
<body>
<button class="button">_____________________________________________</button>
</body>
</html>
</html>
```

<h2 style="text-align: center">Файл 22.html</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <style>
        .element {
            width: 300px;
            height: 200px;
            background-image: url('https://avatars.dzeninfra.ru/get-zen_doc/3986059/pub_61643389916bac55c04bdc9c_616438963051007f8ef76331/scale_1200');
            background-size: cover;
            background-position: center;
        }
    </style>
</head>
<body>
<div class="element"></div>
</body>
</html>
```

<h2 style="text-align: center">Файл 23.html(30-31 задание)</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <style>
      form {
        width: 300px;
        margin: 0 auto;
      }

      input[type="text"],
      input[type="submit"] {
        display: block;
        width: 100%;
        padding: 10px;
        margin-bottom: 10px;
        box-sizing: border-box;
      }
      input[type="text"] {
            outline: 6px solid darkslateblue;
      }

      input[type="submit"] {
        background-color: navy;
        color: white;
        border: none;
        cursor: pointer;
      }

      input[type="submit"]:hover {
        background-color: yellowgreen;
      }
    </style>
</head>
<body>
<form>
  <input type="text" placeholder="Введите текст">
  <input type="submit" value="Отправить">
</form>
</body>
</html>
```

<h2 style="text-align: center">Файл 24.html</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <style>
        .container {
            width: 300px;
            height: 200px;
            background-color: #f2f2f2;
            text-align: center;
        }
    </style>
</head>
<body>
<div class="container">
    <p>ASDASDASDASDAS</p>
</div>
</body>
</html>
```

<h2 style="text-align: center">Файл 25.html</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <style>
        .menu {
            position: relative;
            display: inline-block;
        }

        .menu-content {
            display: none;
            position: absolute;
            background-color: #f9f9f9;
            min-width: 160px;
            box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
            padding: 12px 16px;
            z-index: 1;
        }

        .menu:hover .menu-content {
            display: flex;
            flex-direction: column;
        }
    </style>
</head>
<body>
<div class="menu">
    <button>menu</button>
    <div class="menu-content">
        <a href="#">A</a>
        <a href="#">B</a>
        <a href="#">C</a>
    </div>
</div>
</body>
</html>
```

<h2 style="text-align: center">Файл 26.html</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <style>
        .shadow-text {
            text-shadow: 2px 2px 4px rgba(167, 103, 103, 0.5);
        }
    </style>
</head>
<body>
<h1 class="shadow-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Debitis esse excepturi maxime odio quasi, quo recusandae tenetur. Atque blanditiis consequatur eos ipsam molestiae, obcaecati praesentium quasi qui rem reprehenderit vel.</h1>
</body>
</html>
```

<h2 style="text-align: center">Файл 27.html</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <style>
        .fade-in {
            opacity: 0;
            animation: fade-in-animation 5s forwards;
        }

        @keyframes fade-in-animation {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
            
        }
    </style>
</head>
<body>
<div class="fade-in">
    <h1>Lorem ipsum dolor sit amet.</h1>
</div>
</body>
</html>
```

<h2 style="text-align: center">Файл 28.html</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <style>
        h1, h2, h3, h4, h5, h6 {
            font-size: 18px;
        }
    </style>
</head>
<body>
<h1>AB</h1>
<h2>CD</h2>
<h3>EF</h3>
<h4>12</h4>
<h5>34</h5>
<h6>56</h6>
</body>
</html>
```

<h1 align = "center">Вывод</h1>
<p>По итогу проделанной лабораторной работы, были созданы 28 страниц по заданиям с использованием HTML, CSS</p>
