Тестовое задание Funbox

##Запуск
npm install   
grunt

##Настройка вывода
Содержимое блоков определеяется данными, переданными в миксин.
1. contents
Строка, определяющая содержимое пакета в формате "с ...", передается и выводится как есть, без проверок.    
Поскольку нижняя строка на выделенном элементе разная для разных наполнителей, для всех неизвестных выводится как для "фуа-гра".
2. weight 
Вес. Принимает значения 2, 5, все остальные приводятся к "0,5".
3. status
Необязательный параметр. Строка, слова которой присваиваются как класс, без проверок. Если имеет значение "disabled", элемент выводится как закончившийся.

##Комментарии
Места, где находятся комментарии, в исходном jade и итоговом HTML-коде предваряет соответствующий комментарий.

##Поддерживаемые браузеры
Только с поддержкой SVG http://caniuse.com/#search=svg