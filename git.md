# Домашнее задание к первому семинару по контролю версий
### Список терминальных команд для работы с git, которые нам были показаны во время лекции и семинара:
- ***git config --global user.name "Имя"*** - добавляет имя пользователя git
- ***git config --global user.email "почта"*** - добавляет почту пользователя git
- ***git --version*** - отображение информации об установленной версии git;
- ***git init*** - инициализация git в папке
- ***git status*** - отображает текущий статус файла(-ов) в папке
- ***git add*** - добавляет файл в репозиторий, теперь git может его отслеживать.
- ***git commit -m "комментарий"*** - сохранение (фиксация) изменений в файле(-ах).
- ***git log*** - открытие журнала изменений
- ***git checkout*** **версия** - переходит к определённому коммиту, значение версии можно найти в логах
- ***git checkout master*** - возвращает к актуальной версии
- ***git checkout HEAD^*** - возврат на предыдущий коммит
 - ***git checkout HEAD^^*** - возврат на предпредыдущий коммит