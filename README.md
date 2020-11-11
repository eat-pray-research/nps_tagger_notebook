Привет, Лёх. Этот скрипт протеггирует твои NPS-опросы _:)_

### Инструкция:
- Тыкай сюда -> [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/vapapaiva/nps_tagger_notebook/HEAD?filepath=https%3A%2F%2Fgithub.com%2Fvapapaiva%2Fnps_tagger_notebook%2Fblob%2Fmaster%2Fnps_script.ipynb) - откроется спейс с файлами
- Нажми upload (в правом верхнем углу) и загрузи в спейс файлы с NPS опросами
- Зайди в файл **nps_script.ipynb**
- В ячейке с кодом функции, которая запускает теггирование, пропиши через запятую названия файлов. Чтобы получилось как-то так: 
```
process_nps([
    'nps_karti.xlsx',
    'nps_app.xlsx',
    'nps_chto-to-esche.xlsx'
]) 
```
- Теперь поднимись наверх файла **nps_script.ipynb**, ткни мышкой в первый блок с кодом и нажимай на кнопку "▶ Run" пока весь код файла не исполнится (пока рядом с ячейкой кода стоит знак [*] - он не исполняется)
- Вернись на страницу со списком файлов [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/vapapaiva/nps_tagger_notebook/HEAD?filepath=https%3A%2F%2Fgithub.com%2Fvapapaiva%2Fnps_tagger_notebook%2Fblob%2Fmaster%2Fnps_script.ipynb) и скачай обработанные файлы (они будут называться название_изначального_файла_output.xlsx
- После того как скачаешь файлы — удали их из списка файлов (и обработанные и необработанные)

Грацы, ты великолепен!
