## Отчет по проделанной работе.
1. Был создан сам репозиторий kvazistam.github.io
2.  В настройках pages была выбрана ветка master для отображения изменений в репозитории.
3.  Дальше был установлен lektor и с помощью команды ``lektor quickstart`` был создан начальный проект.
4.  Дальше выбрана тема, внесены некоторые простые изменения в состав страниц и с помощью команды ``lektor build`` собран проект
5.  В файл ``My static site.lektorproject`` внесенны данные строки
   ```yaml
[project]
name = My static site

[servers.ghdeploy]
names = Deploy to Github Pages
target = ghpages+https://kvazistam:my_token@kvazistam/kvazistam.github.io/
```
6. Командой ``lektor deploy`` внесены изменения в репозиторий 
