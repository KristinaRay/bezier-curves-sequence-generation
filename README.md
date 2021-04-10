# bezier-curves-sequence-generation

Научиться генерировать случайные кривые для того, чтобы потом по ним строить визуальные стимулы для пользователей.
**План:**
1. Ознакомиться с классом кривых Безье, например тут: https://habr.com/ru/post/344814/ .Посмотреть, есть ли подобные способы описания путей с помощью кривых других классов - сравнить.
2. Научиться генерировать файлы стандартного формата, например SVG с описанием маршрутов на основе последовательностей кривых, которые выбираются из некоторого случайного множества. Описать параметры для распределений. Отображать последовательности точек вдоль этих маршрутов.
3. Сгенерировать точки вокруг такой кривой со случайным отклонением от истины и подумать, что нужно знать (из скольких участков состоит, какого каждый участок порядка, что-то еще?), чтобы решить обратную задачу - восстановить параметры кривой, зная данные точки.
