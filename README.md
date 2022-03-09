# Титульная страница для компании ЛПМ-Комплекс

![](https://shields.io/badge/-HTML-orange) 
![](https://shields.io/badge/-CSS-blue)
![](https://shields.io/badge/-JavaScript-yellow)

## Описание
* Данным сайтом предполагалось заменить текущую страницу компании ЛПМ-Комплекс по адресу - http://complex-light.ru/ 
* Верстка макета Figma. В процессе верстки отходил от значений указанных в макете. 
* Дизайн сайта разработан мой. Макет в формате CDR и PNG в отдельных ветках.
* Каждый блок сверстан адаптивно. 
* Также присутствует файл `Новый веб-дизайн.docx`, где я объяснил смысл принятых мной дизайнерских решений. 

## Функциональность
* Меню реализовано через "бургер меню". Кнопка меню закреплена в верхнем правом углу страницы. Бургер меню раскрывается на всю страницу.
* Слайдер с лучшими изделиями компании на всю страницу. При наведении курсора перелистывание останавливается. Скрипт `./scripts/roof.js` (на 99% написан не мной). Адаптивность реализована через *Grid Layout*.
* Картинки со ссылками на виды работ и специализацию компании черно-белые. При наведение курсора, изображения становятся цветные.
* Адаптивный слайдер блока "наши партнеры". При ширине экрана 320px одна компания на экране. При 768px две. При 816px три. Скрипт `./scripts/script_downSlider.js`. 
* Адаптивный блок с оборудованием компании. Размер картинок и блоков, которые поверх изображений, пропорциональны ширины экрана. Скрипт `./scripts/tech.js`.

[Ссылка на макет в Figma](https://www.figma.com/file/6Cusjy39hADuiTcmojrFud/Main-2?node-id=0%3A1).

[Ссылка на готовый проект](https://tyt34.github.io/lpm-komplex/).

## Запуск приложения
1. открыть `./index.html`
