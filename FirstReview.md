Добрый день. Хорошая работа, но требует доработки.
Понравился адаптив: страницы не разваливаются, нет прокрутки. Хорошее наименование классов и хорошая файловая структура. Жаль, что не успели сверстать попапы.
Общее:

    Проверьте все страницы валидатором, есть ошибки
    + Eсть ошибки в консоли из-за ненайденных файлов http://joxi.ru/1A5E7E6Cz6BM8A
    + (исправил МММ)У всех страниц в Head должен быть прописан title
    + Помните, что при указании семейства шрифта нужно указывать дополнительный безопасный шрифт и тип засечек
    + (исправил МММ) Для меню в хэдере нужен тег nav
    + Пунктам меню в футере хорошо бы добавить стили по наведению
    + (сделаю  МММ) Логотип в хэдере должен вести на главную страницу
    + (сделаю МММ) Файл card_elipsis.css находится не в своей папке (по БЭМ-flat это ок, там уже есть папка для другого модификатора) и в этом файле находтся стили для совсем другого элемента card__top-elips
    + Также смешаны стили для разных блоков и элементов в файле about.css
    + (исправил) Папка vendor не должна быть в директории blocks

About:

    + Обозначен html lang="en", а должен быть ru
    + Неправильно отображается шрифт у  .about-us__title, circle__text, blockquote__text, card-au__title, card-au__link : http://joxi.ru/brRqPqbsLR599A http://joxi.ru/Dr8zJzLcJLxBZ2
    + Вместо тега <hr /> лучше использовать бордер к блоку
    + <blockquote class="blockquote">
              <h3 class="blockquote__text"> Это излишняя констуркция, сделайте либо цитату, либо заголовок.

Календарь

    + Кнопки content__tags и calendar__button неправильного цвета
    + content__tags не навигация, здесь не нужен тег nav Это кнопки фильтра, по ним будут отбираться определенные события.
    + calendar__date не стоит позиционировать абсолютно и не стоит делать цифру заголовком, это плохо для Seo

Главная (исправлю МММ)

    + (исправил) В index-1.html указан <html lang="en"> исправил.
    + (исправил) В index-1.html в заголовке желтой карточки есть горизонтальная прокрутка http://joxi.ru/DmBKbKkIgk97x2 и на некоторой ширине часть заголовка скрывается http://joxi.ru/D2PNPNpCBZ7jNr
    + (исправил) В index-1.html иконка человечка в хэдере header__icon-user должна быть синего цвета
    + (исправил) Хорошо бы картнике в video-section__card-image выбрать другой background-position http://joxi.ru/Y2L1P1GcMWRw6A
    +(исправил) Здесь некорректно отображается шрифт http://joxi.ru/Dr8zJzLcJLNkD2
    + (исправил) newsbrake__story должно быть блоком, а не элементом.
    +(исправил0 Тег article для card_elipses и newsbrake__story не очень подходит, так как article -это скорее статья в обычном понимании, как в газете, с текстовым содержанием.
    + (ипсправил) notice__text больше подходит тег blockquote
    +(исправил) У iframe нужно убрать из разметки атрибуты frameborder, scrolling, width, height, data-width. Значения перенесите в стили.
