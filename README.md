# Проект для ESP32 TTGO T4 v1.3 from LillyGo 

Ну или как-то так...
На youtube канале "электроника в объективе" есть видео про max30100 ну и мне захотелось повторить проект. Автор использовал связку eclipse+msys2+esp idf, без понятия какой версии. На актуальной на момент написания (3.3) через Esp idf command prompt ничего собираться не хотело, пошаманил и почти всё заработало, кроме одной функции - esp_spiram_get_size(), её мне пришлось закомментировать и вместо неё вписать статичное значение объема памяти, благо оно указано в спецификациях на TTGO. В общем-то вот и всё, пользуйтесть на здоровье, сюда залит весь проект целиком без билдов и линковок, в мануале espressif подробно описано, что нужно делать, делов на полчаса вместе с установкой. Всем удачи) 

ps Для max30102 проект не годится, нужно переписывать фукнции и библиотеку, дело в адресах памяти. Может быть я это сделаю...
pps Оригинальное видео: https://www.youtube.com/watch?v=oyeVw5IpknA&t
