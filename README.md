# Objects
Данный проект представляет приложение на Delphi отображающее данные, из ранее созданной и заполненной данными таблице SCOTT.OBJECTS. 
Реализован поиск по столбцу object_id или object_name. Так же есть есть возможность отображать только записи определённого типа по столбцу object_type. 

Для задания параметров соединения с базой данных Oracle используется файл /Bin/setup.ini. 
Предварительно, следует создать структуру таблицы и заполнить ее, прогнав скрипт /Database/alter_table.sql
Также скомпилировать oracle-package из файла /Database/scott.objects_processing.pck

В проекте описаны комметарии, проект реализован с помощью компонентов Odac и DevExpress.
