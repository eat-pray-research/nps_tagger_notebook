Привет, Лёх. Этот скрипт протеггирует твои NPS-опросы _:)_

### Инструкция:
- Тыкай сюда -> [![Binder](https://mybinder.org/badge_logo.svg)](https://hub.gke2.mybinder.org/user/vapapaiva-nps_tagger_notebook-iodbptz6/tree) - откроется спейс с файлами
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
- Теперь поднимись наверх файла **nps_script.ipynb**, ткни мышкой в первый блок с кодом и нажимай на кнопку "▶ Run" пока весь код файла не исполнится (если рядом с ячейкой кода стоит знак [*] - значит он все ещё исполняется)
- Вернись на страницу со списком файлов [![Binder](https://mybinder.org/badge_logo.svg)](https://hub.gke2.mybinder.org/user/vapapaiva-nps_tagger_notebook-iodbptz6/tree) и скачай обработанные файлы (они будут называться название_изначального_файла_output.xlsx
- После того как скачаешь файлы — удали их из списка файлов (и обработанные и необработанные)

Грацы, ты великолепен!


P.S. Если кнопка сломалась - не беда. Иди на https://mybinder.org/ в поле **GitHub repository name or URL** вставляй ссылку на эту страницу (https://github.com/vapapaiva/nps_tagger_notebook) и жди пока он соберет тебе проект. А дальше — иди по инструкции.
