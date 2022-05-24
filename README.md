# JSON

 1. Создайте текстовый файл как в первом ДЗ по Terminal.
 2. Сценарий перенесите в этот файл.
 3. На против каждого действия - напишите команду в GitBash

 4. Создать внешний репозиторий c названием JSON.
![Screenshot_1](https://user-images.githubusercontent.com/91422609/169891997-ebcc528d-2add-4c40-8e8d-e9ee445d11f0.png)


 5. Клонировать репозиторий JSON на локальный компьютер.
 
```git clone https://github.com/OlesyaMashuk/JSON.git```

 6. Внутри локального JSON создать файл “new.json”.
 
 ```
 cd JSON (зайти в локальный репозиторий)
 touch new.json
```

 7. Добавить файл под гит.
 
```git add new.json```

 8. Закоммитить файл.
 
```git commit git commit -m "Добавление файла на внеш.репозиторий"```

 9. Отправить файл на внешний GitHub репозиторий.
 
```git push```

 10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
```
vim new.json
i 
{
        "name": "Olesya",
        "surname": "Mashukova",
        "age" : 40,
        "pets" : 1,
        "salary" : 1000
}
esc :wq enter
```
 11. Отправить изменения на внешний репозиторий.
 ```
git status
git add .
git commit -m "Редактирование файла"
git push
```
 12. Создать файл preferences.json
 
``` vim preferences.json ```

 13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
```
i
{
        "favorite movie" : "Terminator",
        "favorite TV series" : "12 moments of spring",
        "favorite food" : "Vegetarian",
        "favorite time_year" : "Summer",
        "country" : "Iceland"
}
esc :wq enter
```
 14. Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON.
``` 
vim skills.json
i
{
	"skill_1" : "Terminal",
	"skill_2" : "GitBash",
	"skill_3" : "GitHub",
	"skill_4" : "Postman",
	"skill_5" : "API",
	"skill_6" : "Test case",
	"skill_7" : "Charles",
	"skill_8" : "DevTools",
	"skill_9" : "SQL"
}
esc :wq enter
```
 15. Отправить сразу 2 файла на внешний репозиторий.
```
git status
git add .
git commit -a "Добавление двух файлов одновр"
git push
```
 16. На веб интерфейсе создать файл bug_report.json.


 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
--> Commit changes

 18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
--> выбрать файл > клик на иконку карандаш > написать баг-репорт в формате json/

 19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
--> Commit changes

 20. Синхронизировать внешний и локальный репозиторий JSON
--> git pull
