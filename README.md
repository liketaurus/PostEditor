# PostEditor

Попытка создать простой клиент для создания постов для блога на базе GitHub Pages и Jekyll. Пока - для личных целей.

**Что уже работает:**
* подключение к GitHub
* получение списка репозиториев
* получение списка каталогов в репозитории
* формирование имени файла стандартного для Jekyll вида
* создание поста со стандартной шапкой и контентом, введенным пользователем
* сохранение временного файла поста в папке проекта
* создание и коммит файла в выбранном каталоге выбранного репозитория

**Что только планируется:**
* улучшение и "полировка" UI
* WYSIWYG-редактор для Markdown-постов
* удаление файла поста после публикации
* визуальное подтверждение успешной публикации (возможно, открытие поста в браузере)
* ...

Любая помощь приветствуется:-)

---

Использована библиотека [Eclipse EGit Github Connector]
Также некоторые полезные моменты я подсмотрел здесь:
* [OctoDroid]
* [How to create/update file with github api v3 from android]
* [Making a commit with the Github API]
* [Error creating commit: Invalid request]

[Eclipse EGit Github Connector]: https://github.com/eclipse/egit-github
[OctoDroid]: https://github.com/slapperwan/gh4a
[How to create/update file with github api v3 from android]: https://gist.github.com/Detelca/2337731
[Making a commit with the Github API]: http://mdswanson.com/blog/2011/07/23/digging-around-the-github-api-take-2.html
[Error creating commit: Invalid request]: https://github.com/github/maven-plugins/issues/69
