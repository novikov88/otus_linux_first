# otus_linux
Имеется два модуля **ps_aux.py** и **log_parser.py**

**ps_aux** - генерирует отчёт о состоянии системы, выводя информацию на экран и сохраняя данные в файл с именем даты на момент запуска скрипта в формате .txt 

**log_parser.py** - читает файл(ы) логов и выводит информацию:
- Общее количество запросов
- Количество запросов по типам
- Топ 3 IP адресов, с которых были сделаны запросы
- Топ 3 самых долгих запроса

Результат также сохраняется в дирректорию **results** в json файл с именем названия лога

*Для работы скрипта логи должны лежать в дирректории* **/logs** (/home/**user**/logs)
