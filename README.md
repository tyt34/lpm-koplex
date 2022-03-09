# Титульная страница для компании ЛПМ-Комплекс

![](https://shields.io/badge/-HTML-orange) 
![](https://shields.io/badge/-CSS-blue)
![](https://shields.io/badge/-JavaScript-yellow)

## Описание
* Данным сайтом предполагалось заменить текущую страницу компании ЛПМ-Комплекс по адресу - http://complex-light.ru/ 
* Верстка макета Figma. В процессе верстки отходил от значений указанных в макете. 
* Дизайн сайта тоже мой. Макет в формате CDR и PNG в оттельных ветках.
* Каждый блок сверстан адаптивно. 

## Функциональность
* Меню реализовано через "бургер меню". Кнопка меню закреплена в верхнем правом углу страницы. Бургер меню расскрывается на всю страницу.
* Наличие слайдера с лучшими изделиями компании на всю страницу. При наведение курсора перелистование останавлиавется. Скрипт `./scripts/roof.js` (на 99% написан не мной). Адаптивность реазиована через *Grid Layout*.
* Картинки с ссылками на виды работ и специализацию компании черно-белые. Если навести курсор то будут цветные.
* Адаптивный слайдер блока "наши партнеры". При ширине экрана 320px одна компания на экране. При 768px две. При 816px три. Скрипт `./scripts/script_downSlider.js`. 
* Адаптивный блок с оборудованием компании. Размер картинок и блока, который поверх картинки, пропорционален ширине экрана. Скрипт `./scripts/tech.js`.

[Ссылка на макет в Figma](https://www.figma.com/file/6Cusjy39hADuiTcmojrFud/Main-2?node-id=0%3A1).