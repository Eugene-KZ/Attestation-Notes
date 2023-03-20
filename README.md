# Добро пожаловать в приложение Notes

Данное приложение создано для работы из терминала.

В зависимости от того, что вам нужно вводите следующие команды:

--help - покажет список команд

--add [OPTION]- добавит заметку, для добавления нужно через пробел ввести следующие команды:  
    --title TITLE - заголок заметки  
    --msg MESSAGE - текст заметки  
Пример: "python main --add --title Заголовок --msg Текст заметки"

--show [OPTION]- покажет список заметок  
    --all - список всех заметок  
    --id ID - заметка по id  

--find [OPTION]- поиск заметок по базе данных по ключевым словам  
    SUBSTRING - поиск слова в заголовке и тексте  
    --title SUBSTRING - поиск по слову в заголовке  
    --msg SUBSTRING - поиск по слову в тексте  

--edit ID - изменение заметки  
    --title TITLE - изменение заголовка  
    --msg MESSAGE - изменение текста  

--delete ID - удалить заметку по id  

--export - экспорт из csv файла

--import PATH_TO_FILE - импорт в csv файл