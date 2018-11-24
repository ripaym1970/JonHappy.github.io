# crop_full_preview.github.io
кадрирование (обрезка) картинок для просмотра и превью

https://jonhappy.github.io/modal_menu/<br>
<b>примеры модального меню с вызываемого по правой кнопке</b><br>
и модального окна вызываемого по кнопе на странице,<br>
а в модальноко окна вызов (открытие) новой вкладки браузера со страницей кадрирования картиок

https://jonhappy.github.io/inner/<br>
<b>сравнение скорости "сревеного рендеринга" со скоростью поэлементного построения на клиенте</b><br>
(смотреть лучше в хроме - точность времени больше - количество знаков после запятой,
в мозиле только мс)

https://jonhappy.github.io<br>
<b>кадрирование (обрезка) картинок для просмотра и превью</b><br>
Пожелания приветствуются.

можно загружать по несколько картинок за раз<br>

- слайдер слева - поворачивает картинку отностельно центра, шаг 1 градус<br>

При нахождении указателя мыши в зоне картинки возможны действия<br>
- колесо мыши - увеличение/уменьшение картинки<br>
 (кнопка x/xx задаёт коэффициент ресайза  - x = 0.001, хх = 0.01 / зелёным цветом выбранный коэффициент)
- Shift + колесо мыши - перемещение картинки только по вертикали на 1 пиксел
- Ctrl + колесо мыши - перемещение картинки только по горизонтали на 1 пиксел<br>
(индикация стрелками на блоке управлени<br>
  зеленые: разрешенное напрвление<br>
  красные: запрещённое направление)
  
 - Alt + колесо мыши - поворот на 0.1 градуса

- слайдер внизу - задаёт размер обрезки по вертикали
- слайдер справа -задаёт размер обрезки по горизонтали<br>
  управление: перемещением красного бегунка мышью или колесом, при нахождении указателя мыши в зоне слайдера
  
- самый крайний слайдер (на цветном поле) уменшение/увеличение картинки

основные модификации
- от jQuery оставлено только draggable...
- сделан переход на использование CSS-переменных
- "панель управления" может перемещаться мышью (чтоб не мешала просмотру обрезанного)

задать размер для картинки можно тут<br>
   --pix_max_width:700px;<br>
   --pix_max_height:700px;<br>

Проверена работа в Chrome и Mozilla.
(в FF загрузка картинки почти в 4 раза медленнее, чем в хроме. можно посмотреть цифры в отладчике)<br>
Превоначально код был предназначен для преобраования исходных фотографий товара в картинки для сайтов
для "полного" простмотра и для "превьюшек" , данный функционал остался в коде в закомментированном виде..
если есть необходимость, можно попробовать самим вернуть эти возможности или попросить меня 
<br><br>
хоть это и проект Netbeans , для просмотра достаточно папку public_html скопировать на диск и в ней запустить index.html
