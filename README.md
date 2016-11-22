Необходимо написать скрипт на Питоне, который разбирает результат работы команды «svn -uv status», вывод которой был перенаправлен в файл. 

Скрипт должен разобрать данные в файле с результатами работы svn status и вывести их в более дружелюбной табличной форме, пригодной для восприятия человеком, который не знает/не помнит формат вывода команды svn status, но имеет базовые представления о таких понятиях как «свойство/статус файла/каталога». 

0. Каждый столбец результирующей таблицы должен соответствовать столбцу в исходном файле. 
1. Порядок следования столбцов в результирующей таблице произвольный. 
2. Способ оформления таблицы (ширины столбцов, способ отделения столбцов друг от друга и т.д.) произвольный. 
3. Каждый столбец таблицы должен иметь заголовок, обозначающий назначение данных в столбце. 
4. Буквы, определяющие состояние файла/каталога в исходной таблице должны быть преобразованы в более понятную/читабельную форму. Например, A –> Added, M -> Modified и т.д. 

Неоднозначные пункты задания следует проинтерпретировать по своему усмотрению.