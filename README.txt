<!DOCTYPE html>
<!--[if IE 7]> <html lang="ru" class="ie7 responsive" > <![endif]-->
<!--[if IE 8]> <html lang="ru" class="ie8 responsive" > <![endif]-->
<!--[if IE 9]> <html lang="ru" class="ie9 responsive" > <![endif]-->
<!--[if !IE]><!-->


►	Верстка проводится для:
	- IE-8;
    - IE-9;
	- IE-10;
	- Opera;
	- Crome;
	- Yandex;
	- Mozilla;
	- Safari.
	
	
►	Контрольные точки размера экрана:
- 1920;
- 1600;
- 1440;
- 1366;
- 1280;
- 1200;
- 1140;
- 1024;
- 991;
- 768;
- 720
- 667
- 640
- 568
- 480
- 460
- 414
- 375
- 360
- 320


appearance: none; + -webkit-, -moz-. Убирать св-фа форм по умолчаю;
►	DPR
 - DPR = 1, 1.5, 2;
 - srcset - определение плотности экрана (DPR);
 -  Верстка <img> и DPR см. Переключения разрешений: Одинаковый размер, разные разрешения https://developer.mozilla.org/ru/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images
 
 
►	Единица измеренияЖ
 - em = размеру шрифта от родительского эл-та. Используется в font, height, width, padding, margin, bexckground;
 - rem =  где  px / font-siceHTML (font, height, width, padding, margin, bexckground);
 - 1vh/vw = 1% от  высоты/ширины окна браузера;
 - 1vmain/vmax = 1% от меньшего значения - ширины или высота. Если orientation: portrait то 1vmin=1vw$


►	Flex: none | < flex-grow > < flex-shrink> < flex-basis > - растягивание/сжатие
	
	margin-Fight
	- flex-shrink: <номер>
		Определяет коэфициент СЖАТИЯ эелемента относительно остальных элементов flex 
		-- номер = 1: элемент может сужаться;
		-- номер = 0: элемент сохраняет первоначальный размер;
		
	- flex-grow: <номер>
		Как РАСТЯГИВАТЬСЯ
		-- номер = 0: не растягивается;
		-- номер = 1: значение по умолчанию;
		-- номер = 2: значение кратно двум;

	- flex-basis: изначчальные размеры элемента в любых единицах;
	
	- order: <номер>
		номер - любое число указывающее каким по порядку должен быть элемент в ленте элементов.
		Чем меньше номер тем раньше видим в ленте;
		
►	calc()
	-  

		
►	HEAD 
<head>
	<meta name="viewport" content = "width = devicew-width, initial-scale = 1.0"> - регулируем масштабирование на устройствах;
	<meta name="format-detection" content="telephone=no" > отменяем звонок при клике!!! - редко востребован;
	<link href="...css" rel="stylesheet" media="screen/prinnt/speeach/all">
</head>


►	@MEDIA
@media not screen {  } - not - срабатывать в случае, противоположном указанному условию;
@media (aspect-ratio: 8/5) {  } - соотношение ширины к высоте отображаемого экрана;
@media (min-aspect-ratio: 8/5) {  }
@media (orientation: ladscape/portrait) {  } - горизонтальный/вертикальный экраны;
@media (max-width: 1199.98px) {  }
@media (max-width: 768px) and (min-width: 1280px) {  }
@media (max-width: 768px), (min-width: 1280px) {  }

https://habr.com/ru/post/475832/
http://htmlbook.ru/css/value/media

Справка HTML5
https://html5book.ru/html-html5/
https://html5book.ru/css-css3/
https://html5book.ru/javascript-jquery/
https://html5book.ru/web-topography/
https://html5book.ru/category/vyorstka/
https://html5book.ru/html-spravochnik.html
https://html5book.ru/css-spravochnik.html


►	Соотношения сторон 
https://translated.turbopages.org/proxy_u/en-ru.ru.2ea8e350-62bd91fb-ea2dcafc-74722d776562/https/en.wikipedia.org/wiki/High_Quality#Common_display_resolutions
Стандартное	Соотношение сторон	Ширина (px)	Высота (в пикселях)
nHD			16:09			640	360
SVGA		4:03			800	600
XGA			4:03			1024	768
WXGA		16:09			1280	720
WXGA		16:10			1280	800
SXGA		5:04			1280	1024
HD			≈16:9			1360	768
HD			≈16:9			1366	768
WXGA+		16:10			1440	900
N/A			16:09			1536	864
HD+			16:09			1600	900
WSXGA+		16:10			1680	1050
FHD			16:09			1920	1080
WUXGA		16:10			1920	1200
QWXGA		16:09			2048	1152
QXGA		4:03			2048	1536
UWFHD		≈21:9			2560	1080
QHD			16:09			2560	1440
WQXGA		16:10			2560	1600
UWQHD		≈21:9			3440	1440
4K UHD		16:09			3840	2160
Другое			


	