<p align = "center">МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ<br>
РОССИЙСКОЙ ФЕДЕРАЦИИ<br>
ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ<br>
ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ<br>
«САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»</p>
<br><br><br><br><br><br>
<p align = "center">Институт естественных наук и техносферной безопасности<br>Кафедра информатики<br>Чернявский Роман Евгеньевич</p>
<br><br><br>
<p align = "center"><br><strong>Лабораторная работа №3.«HTML»</strong><br>01.03.02 Прикладная математика и информатика</p>
<br><br><br><br><br><br><br><br><br><br><br><br>
<p align = "right">Научный руководитель<br>
Соболев Евгений Игоревич</p>
<br><br><br>
<p align = "center">г. Южно-Сахалинск<br>2024 г.</p>
<br><br><br><br><br><br><br><br><br><br><br><br>

<h1 align = "center">Введение</h1>

<p><b>Среда разработки html (HyperText Markup Language)</b> — это язык разметки, который используется для создания веб-страниц. HTML определяет структуру содержимого веб-страницы, такие как заголовки, параграфы, списки, ссылки и изображения. HTML состоит из набора тегов, которые определяют различные элементы страницы и их отображение в браузере.</p>

<br>
<h1 align = "center">Цели и задачи</h1>


<p>Требуется выполнить задания, применяя полученные знания на лекциях и взятые из интернета.</p>

<p></p>



<h1 align = "center">Решение</h1>

<p>Для выполнения этой лабораторной работы, я пользовался материалом из интернета и того, что мы проходили на лекциях</p>

<h2 align = "center">Файл "1.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width, initial-scale=1.0">
        <title>"Лабораторная работа №3"</title>
    </head>

    <body style="background-color:blueviolet;">
        <h1 class="heading">Hello world</h1>
        <h2 class="heading">Hello world</h2>
        <h3 class="heading">Hello world</h3>
        <h4 class="heading">Hello world</h4>
        <h5 class="heading">Hello world</h5>
        <h6 class="heading">Hello world</h6>
    </body>
</html>
```

<h2 align = "center">Файл "2.html"</h2>


```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width, initial-scale=1.0">
        <title>"Лабораторная работа №3"</title>
    </head>

    <body style="background-color:blueviolet;">
        <h1 id="heading-1" class="heading">Hello world</h1>
        <h2 id="heading-2" class="heading">Hello world</h2>
        <h3 id="heading-3" class="heading">Hello world</h3>
        <h4 id="heading-4" class="heading">Hello world</h4>
        <h5 id="heading-5" class="heading">Hello world</h5>
        <h6 id="heading-6" class="heading">Hello world</h6>
    </body>
</html>
```

<h2 align = "center">Файл "3.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width, initial-scale=1.0">
        <title>"Лабораторная работа №3"</title>
        <style>
            .heading {
                color: red;
            }
        </style>
    </head>

    <body style="background-color:blueviolet;">
        <h1 id="heading-1" class="heading">Hello world</h1>
        <h2 id="heading-2" class="heading">Hello world</h2>
        <h3 id="heading-3" class="heading">Hello world</h3>
        <h4 id="heading-4" class="heading">Hello world</h4>
        <h5 id="heading-5" class="heading">Hello world</h5>
        <h6 id="heading-6" class="heading">Hello world</h6>
    </body>
</html>
```

<h2 align = "center">Файл "4.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width, initial-scale=1.0">
        <title>"Лабораторная работа №3"</title>
        <style>
            .heading {
                color: red;
            }
            #heading-2 {
                color: blue;
            }
        </style>
    </head>

    <body style="background-color:blueviolet;">
        <h1 id="heading-1" class="heading">Hello world</h1>
        <h2 id="heading-2" class="heading">Hello world</h2>
        <h3 id="heading-3" class="heading">Hello world</h3>
        <h4 id="heading-4" class="heading">Hello world</h4>
        <h5 id="heading-5" class="heading">Hello world</h5>
        <h6 id="heading-6" class="heading">Hello world</h6>
    </body>
</html>
```

<h2 align = "center">Файл "5.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width, initial-scale=1.0">
        <title>"Лабораторная работа №3"</title>
        <style>
            .heading {
                color: red;
            }
            #heading-2 {
                color: blue;
            }
            #heading-3 {
                background-color: black;
                color: white;
            }
        </style>
    </head>

    <body style="background-color:blueviolet;">
        <h1 id="heading-1" class="heading">Hello world</h1>
        <h2 id="heading-2" class="heading">Hello world</h2>
        <h3 id="heading-3" class="heading">Hello world</h3>
        <h4 id="heading-4" class="heading">Hello world</h4>
        <h5 id="heading-5" class="heading">Hello world</h5>
        <h6 id="heading-6" class="heading">Hello world</h6>
    </body>
</html>
```

<h2 align = "center">Файл "6.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width, initial-scale=1.0">
        <title>"Лабораторная работа №3"</title>
        <style>
            .heading {
                color: red;
            }
            #heading-2 {
                color: blue;
            }
            #heading-3 {
                background-color: black;
                color: white;
            }
            #heading-4 {
                border: 2px solid black;
                border-radius: 10px;
            }
        </style>
    </head>

    <body style="background-color:blueviolet;">
        <h1 id="heading-1" class="heading">Hello world</h1>
        <h2 id="heading-2" class="heading">Hello world</h2>
        <h3 id="heading-3" class="heading">Hello world</h3>
        <h4 id="heading-4" class="heading">Hello world</h4>
        <h5 id="heading-5" class="heading">Hello world</h5>
        <h6 id="heading-6" class="heading">Hello world</h6>
    </body>
</html>
```

<h2 align = "center">Файл "7.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width, initial-scale=1.0">
        <title>"Лабораторная работа №3"</title>
        <style>
            .heading {
                color: red;
            }
            #heading-2 {
                color: blue;
            }
            #heading-3 {
                background-color: black;
                color: white;
            }
            #heading-4 {
                border: 2px solid black;
                border-radius: 10px;
            }
            #heading-5:hover {
                color: green;
            }
        </style>
    </head>

    <body style="background-color:blueviolet;">
        <h1 id="heading-1" class="heading">Hello world</h1>
        <h2 id="heading-2" class="heading">Hello world</h2>
        <h3 id="heading-3" class="heading">Hello world</h3>
        <h4 id="heading-4" class="heading">Hello world</h4>
        <h5 id="heading-5" class="heading">Hello world</h5>
        <h6 id="heading-6" class="heading">Hello world</h6>
    </body>
</html>

```

<h2 align = "center">Файл "8.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width, initial-scale=1.0">
        <title>"Лабораторная работа №3"</title>
        <style>
            .heading {
                color: red;
            }
            #heading-2 {
                color: blue;
            }
            #heading-3 {
                background-color: black;
                color: white;
            }
            #heading-4 {
                border: 2px solid black;
                border-radius: 10px;
            }
            #heading-5:hover {
                color: green;
            }
        </style>
    </head>

    <body style="background-color:blueviolet;">
        <h1 id="heading-1" class="heading">Hello world</h1>
        <h2 id="heading-2" class="heading">Hello world</h2>
        <h3 id="heading-3" class="heading">Hello world</h3>
        <h4 id="heading-4" class="heading">Hello world</h4>
        <h5 id="heading-5" class="heading">Hello world</h5>
        <h6 id="heading-6" class="heading">Hello world</h6>
        <input type="text" placeholder="Text input">
        <input type="password" placeholder="Password input">
        <input type="number" placeholder="Number input">
        <input type="email" placeholder="Email input">
        <input type="date" placeholder="Date input">
        <input type="checkbox" id="checkbox"> <label for="checkbox">Checkbox</label>
    </body>
</html>
```

<h2 align = "center">Файл "9.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width, initial-scale=1.0">
        <title>"Лабораторная работа №3"</title>
        <style>
            
        </style>
    </head>

    <body style="background-color:blueviolet;">
        <ol>
            <li>Нумерованный</li>
            <li>Нумерованный</li>
            <li>Нумерованный</li>
            <li>Нумерованный</li>
          </ol>
    </body>
</html>
```

<h2 align = "center">Файл "10.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width, initial-scale=1.0">
        <title>"Лабораторная работа №3"</title>
        <style>
            
        </style>
    </head>

    <body style="background-color:blueviolet;">
        <ul style="list-style-type: square;">
            <li>Маркированный</li>
            <li>Маркированный</li>
            <li>Маркированный</li>
            <li>Маркированный</li>
        </ul>
    </body>
</html>
```

<h2 align = "center">Файл "11.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>"Лабораторная работа №3"</title>
        <style>
            body {
                background-color: green;
                color: white;
            }
        </style>
    </head>
    <body>
        <p>Это веб-страница с зеленым фоном и белым текстом. Веб-страница содержит тридцать слов, используя стандартное HTML.</p>
        <p>Зеленый фон создается с помощью CSS, который задает свойство background-color, а белый текст — с помощью CSS, который задает свойство color.</p>
        <p>Это третье предложение для демонстрации того, что веб-страница действительно содержит тридцать слов. Теперь осталось только еще несколько, чтобы достичь цели. Вот они, последние слова.</p>
    </body>
</html>
```

<h2 align = "center">Файл "12.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width, initial-scale=1.0">
        <title>"Лабораторная работа №3"</title>
        <style>
            p {
                font-family: Arial, sans-serif;
            }
        </style>
    </head>

    <body style="background-color:blueviolet;">
        <p>Международное сообщество выражает глубокую озабоченность из-за последних событий в регионе. Несмотря на множество усилий и дипломатических переговоров, ситуация остается напряженной.</p>

        <p>Недавние обострения только подчеркивают необходимость мирного урегулирования конфликта. Диалог и сотрудничество между сторонами должны стать приоритетом для предотвращения дальнейшей эскалации.</p>

        <p>Важно, чтобы все заинтересованные стороны воздерживались от действий, которые могут ухудшить ситуацию. Только через совместные усилия и конструктивный диалог можно найти устойчивое решение, способствующее миру и стабильности в регионе.</p>
    </body>
</html>
```

<h2 align = "center">Файл "13.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>"Лабораторная работа №3"</title>
    <style>
      body {
        background-color: green;
        color: white;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
      }
      .container {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
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
      <div class="block">1</div>
      <div class="block">2</div>
      <div class="block">3</div>
      <div class="block">4</div>
      <div class="block">5</div>
      <div class="block">6</div>
    </div>
  </body>
</html>
```

<h2 align = "center">Файл "14.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width, initial-scale=1.0">
        <title>"Лабораторная работа №3"</title>
        <style>
            p {
                font-family: Arial, sans-serif;
            }
        </style>
    </head>

    <body style="background-color:blueviolet;">
        <p>Международное сообщество выражает глубокую озабоченность из-за последних событий в регионе. Несмотря на множество усилий и дипломатических переговоров, ситуация остается напряженной.</p>

        <p>Недавние обострения только подчеркивают необходимость мирного урегулирования конфликта. Диалог и сотрудничество между сторонами должны стать приоритетом для предотвращения дальнейшей эскалации.</p>

        <p>Важно, чтобы все заинтересованные стороны воздерживались от действий, которые могут ухудшить ситуацию. Только через совместные усилия и конструктивный диалог можно найти устойчивое решение, способствующее миру и стабильности в регионе.</p>
    </body>
</html>
```

<h2 align = "center">Файл "15.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>"Лабораторная работа №3"</title>
    <style>
      body {
        font-family: Arial, sans-serif;
        background-color: #f4f4f4;
        color: #333;
        margin: 0;
        padding: 0;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
      }
      form {
        background-color: #fff;
        padding: 20px;
        border-radius: 5px;
        box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      }
      input[type="text"],
      input[type="email"],
      input[type="password"],
      button {
        width: 100%;
        padding: 10px;
        margin-bottom: 10px;
        border: 1px solid #ccc;
        border-radius: 3px;
        box-sizing: border-box;
        font-size: 16px;
      }
      button {
        background-color: #007bff;
        color: #fff;
        cursor: pointer;
      }
      button:hover {
        background-color: #0056b3;
      }
    </style>
  </head>
  <body>
    <form>
      <input type="text" name="username" placeholder="Имя пользователя" required>
      <input type="email" name="email" placeholder="Электронная почта" required>
      <input type="password" name="password" placeholder="Пароль" required>
      <button type="submit">Зарегистрироваться</button>
    </form>
  </body>
</html>
```

<h2 align = "center">Файл "16.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>"Лабораторная работа №3"</title>
        <style>
            body {
                font-family: Arial, sans-serif;
            }
            table {
                width: 100%;
                border-collapse: collapse;
                margin-bottom: 20px;
            }
            th, td {
                border: 1px solid #ccc;
                padding: 8px;
                text-align: left;
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
                    <th>Имя</th>
                    <th>Возраст</th>
                    <th>Город</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Иван</td>
                    <td>25</td>
                    <td>Москва</td>
                </tr>
                <tr>
                    <td>Елена</td>
                    <td>30</td>
                    <td>Санкт-Петербург</td>
                </tr>
                <tr>
                    <td>Алексей</td>
                    <td>28</td>
                    <td>Новосибирск</td>
                </tr>
            </tbody>
        </table>
    </body>
</html>
```

<h2 align = "center">Файл "17.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width, initial-scale=1.0">
        <title>"Лаборатоная работа №3"</title>
        <style>
            h1 {
                color: red;
            }
        </style>
    </head>

    <body style="background-color:blueviolet;">
        <h1 class="heading">Hello world!</h1>
    </body>
</html>
```

<h2 align = "center">Файл "18.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width, initial-scale=1.0">
        <title>"Лабораторная работа №3"</title>
        <style>
            p {
                font-family: Arial, sans-serif;
            }
        </style>
    </head>

    <body style="background-color:blueviolet;">
        <p>Международное сообщество выражает глубокую озабоченность из-за последних событий в регионе. Несмотря на множество усилий и дипломатических переговоров, ситуация остается напряженной.</p>

        <p>Недавние обострения только подчеркивают необходимость мирного урегулирования конфликта. Диалог и сотрудничество между сторонами должны стать приоритетом для предотвращения дальнейшей эскалации.</p>

        <p>Важно, чтобы все заинтересованные стороны воздерживались от действий, которые могут ухудшить ситуацию. Только через совместные усилия и конструктивный диалог можно найти устойчивое решение, способствующее миру и стабильности в регионе.</p>
    </body>
</html>
```

<h2 align = "center">Файл "19.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>"Лабораторная работа №3"</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f0f0f0;
        }
        .container {
            width: 300px;
            height: 200px;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            padding: 20px;
            text-align: center;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Пример веб-страницы с тенью</h1>
        <p>Этот блок div имеет тень, добавленную с помощью свойства box-shadow.</p>
    </div>
</body>
</html>
```

<h2 align = "center">Файл "20.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>"Лабораторная работа №3"</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .container {
            width: 300px;
            height: 200px;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            padding: 20px;
            text-align: center;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Пример веб-страницы с тенью</h1>
        <p>Этот блок div имеет тень, добавленную с помощью свойства box-shadow.</p>
    </div>
</body>
</html>
```

<h2 align = "center">Файл "21.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>"Лабораторная работа №3"</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .container {
            width: 300px;
            height: 200px;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            padding: 20px;
            text-align: center;
            animation: blink 1s infinite;
        }
        @keyframes blink {
            0% {color: black;}
            50% {color: red;}
            100% {color: black;}
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Пример анимации мигания</h1>
        <p>Этот блок div имеет анимацию, которая мигает красным цветом.</p>
    </div>
</body>
</html>
```

<h2 align = "center">Файл "22.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>"Лабораторная работа №3"</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .container {
            width: 300px;
            height: 200px;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            padding: 120px;
            text-align: center;
            animation: blink 1s infinite;
        }
        @keyframes blink {
            0% {color: black;}
            50% {color: red;}
            100% {color: black;}
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Пример анимации мигания</h1>
        <p>Этот блок div имеет анимацию, которая мигает красным цветом.</p>
    </div>
</body>
</html>
```

<h2 align = "center">Файл "23.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>"Лабораторная работа №3"</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .container {
            width: 300px;
            height: 200px;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            padding: 20px;
            text-align: center;
            animation: blink 1s infinite;
        }
        @keyframes blink {
            0% {color: black;}
            50% {color: red;}
            100% {color: black;}
        }
        a {
            color: #007bff;
            text-decoration: none;
            transition: color 0.3s;
        }
        a:hover {
            color: #0056b3;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Пример анимации мигания</h1>
        <a href="#">Этот блок div имеет анимацию, которая мигает красным цветом.</a>
    </div>
</body>
</html>
```

<h2 align = "center">Файл "24.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>"Лабораторная работа №3"</title>
    <style>
        
    </style>
</head>
<body>
    <img src="24.jpg" alt="sunflowers" style="border: 1px solid black;">
</body>
</html>
```

<h2 align = "center">Файл "25.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>"Лабораторная работа №3"</title>
    <style>
        ul {
            list-style-type: square;
        }
    </style>
</head>
<body>
    <p>Пример списка с квадратными маркерами:</p>
    <ul>
        <li>Item 1</li>
        <li>Item 2</li>
        <li>Item 3</li>
        <li>Item 4</li>
    </ul>
</body>
</html>
```

<h2 align = "center">Файл "26.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>"Лабораторная работа №3"</title>
    <style>
        div {
            width: 300px;
            height: 200px;
            background-color: lightblue;
        }
    </style>
</head>
<body>
    <div>"Размеры этого блока составляют 200 пикселей в высоту и 300 пикселей в ширину"</div>
</body>
</html>
```

<h2 align = "center">Файл "27.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>"Лабораторная работа №3"</title>
    <style>
        table {
            border-collapse: collapse;
            width: 100%;
        }

        table tr:nth-child(even) {
            background-color: lightgrey;
        }

        table th, table td {
            border: 1px solid black;
            padding: 8px;
            text-align: left;
        }
    </style>
</head>
<body>
    <table>
        <thead>
            <tr>
                <th>Заголовок</th>
                <th>Заголовок</th>
                <th>Заголовок</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1</td>
                <td>1</td>
                <td>1</td>
            </tr>
            <tr>
                <td>2</td>
                <td>2</td>
                <td>2</td>
            </tr>
            <tr>
                <td>3</td>
                <td>3</td>
                <td>3</td>
            </tr>
            <tr>
                <td>4</td>
                <td>4</td>
                <td>4</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
```

<h2 align = "center">Файл "28.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>"Лабораторная работа №3"</title>
    <style>
        .button {
            background-color: #4CAF50;
            border: none;
            color: white;
            padding: 15px 32px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            margin: 4px 2px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        .button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <button class="button">Наведи на меня!</button>
</body>
</html>
```

<h2 align = "center">Файл "29.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>"Лабораторная работа №3"</title>
    <style>
        .element {
            width: 500px;
            height: 300px;
            background-image: url('29.jpg');
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
        }
    </style>
</head>
<body>
    <div class="element"></div>
</body>
</html>
```

<h2 align = "center">Файл "30.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>"Лабораторная работа №3"</title>
    <style>
        form {
            width: 300px;
            margin: 0 auto;
        }

        input[type="text"], input[type="password"], input[type="email"], textarea {
            width: 100%;
            padding: 10px;
            margin: 5px 0;
            border: 1px solid #ccc;
            border-radius: 4px;
            box-sizing: border-box;
        }

        input[type="submit"] {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }

        input[type="submit"]:hover {
            background-color: #45a049;
        }

    </style>
</head>
<body>
    <form>
        <label for="name">Ваше Имя:</label><br>
        <input type="text" id="name" name="name" placeholder="Введите ваше имя"><br>
        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email" placeholder="Введите ваш email"><br>
        <label for="message">Сообщение:</label><br>
        <textarea id="message" name="message" placeholder="Отправить"></textarea><br>
        <input type="submit" value="Отправить">
    </form>
</body>
</html>
```

<h2 align = "center">Файл "31.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>"Лабораторная работа №3"</title>
    <style>
        input[type="text"], input[type="password"], input[type="email"], textarea {
            width: 100%;
            padding: 10px;
            margin: 5px 0;
            border: 1px solid #ccc;
            border-radius: 4px;
            box-sizing: border-box;
            outline: 2px solid blue;
        }
    </style>
</head>
<body>
    <form>
        <label for="name">Ваше Имя:</label><br>
        <input type="text" id="name" name="name" placeholder="Введите ваше имя"><br>
        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email" placeholder="Введите ваш email"><br>
        <label for="message">Сообщение:</label><br>
        <textarea id="message" name="message" placeholder="Отправить"></textarea><br>
        <input type="submit" value="Отправить">
    </form>
</body>
</html>
```

<h2 align = "center">Файл "32.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>"Лабораторная работа №3"</title>
</head>
<body>
    <div style="text-align: center;">
        <h1>Пример выравнивания текста по центру</h1>
        <p>Этот текст выровнен по центру.</p>
        <p>Дополнительный текст для демонстрации выравнивания по центру.</p>
    </div>
</body>
</html>
```

<h2 align = "center">Файл "33.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>"Лабораторная работа №3"</title>
    <style>
        .dropdown {
            position: relative;
            display: inline-block;
        }

        .dropdown-content {
            display: none;
            position: absolute;
            background-color: #f9f9f9;
            min-width: 160px;
            box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
            z-index: 1;
        }

        .dropdown-content a {
            color: black;
            padding: 12px 16px;
            text-decoration: none;
            display: block;
        }

        .dropdown:hover .dropdown-content {
            display: block;
        }
    </style>
</head>
<body>
    <div class="dropdown">
        <button class="dropbtn">Меню</button>
        <div class="dropdown-content">
            <a href="#">Ссылка 1</a>
            <a href="#">Ссылка 2</a>
            <a href="#">Ссылка 3</a>
        </div>
    </div>
</body>
</html>
```

<h2 align = "center">Файл "34.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>"Лабораторная работа №3"</title>
    <style>
        .shadow-text {
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }
    </style>
</head>
<body>
    <h1 class="shadow-text">Текст с тенью</h1>
    <p class="shadow-text">Этот текст также имеет тень.</p>
</body>
</html>
```

<h2 align = "center">Файл "35.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>"Лабораторная работа №3"</title>
  <style>
    @keyframes fadeIn {
      from {
        opacity: 0;
      }
      to {
        opacity: 1;
      }
    }

    .fade-in-element {
      opacity: 0;
      animation: fadeIn 2s ease-in-out forwards;
    }
  </style>
</head>
<body>
  <div class="fade-in-element">
    <h1>Плавное появление!</h1>
    <p>Этот элемент плавно появляется на странице с использованием анимации opacity.</p>
  </div>
  <div style="height: 1000px;"></div>

  <script>
    document.addEventListener('DOMContentLoaded', function() {
      const element = document.querySelector('.fade-in-element');
      element.classList.add('fade-in-element');
    });
  </script>
</body>
</html>
```

<h2 align = "center">Файл "36.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>"Лабораторная работа №3"</title>
  <style>
    h1, h2, h3, h4, h5, h6 {
      font-size: 18px;
    }
  </style>
</head>
<body>
  <h1>Заголовок 1</h1>
  <h2>Заголовок 2</h2>
  <h3>Заголовок 3</h3>
  <h4>Заголовок 4</h4>
  <h5>Заголовок 5</h5>
  <h6>Заголовок 6</h6>
</body>
</html>
```

<h1 align = "center">Результат</h1>

<p align = "center"><img src="result.png" alt="result"></p>

<h1 align = "center">Вывод</h1>
<p>По итогу проделанной лабораторной работы, я узнал о том, что такое HTML и CSS и научился использовать их для создания своего сайта.</p>
