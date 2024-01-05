# Приветствую в моем небольшом сборнике команд для работы с Git.

## Для начала основные команды:

---

pwd (_en_ present working directory/ _ru_ вывести рабочий каталог)

ls (показать файлы в текущей директории) ~~флаг -a~~ позволяет увидеть скрытые файлы и другие директории внутри рабочей.

cd (_en_ change directory/ _ru_ сменить директорию)

~ - ссылка на домашюю директорию _(cd ~)_

.. - ссылает на родительскую директорию _(cd ..)_

---

git init **команда нужная для инициализации git**

Чтобы добавить файл в ваш проект следует использовать команду **git add ...**

Затем следует закоммитить ваш проект и желательно сделать это с комментарием
для этого нам нужен ~~флаг -m~~ **git commit -m "Ваш комментарий"**

В итоге мы можем "запушить" проект. Для этого следует прописать команду **git push -u origin master/main**
~~флаг -u~~ нам будет нужен только для 1-го пуша, а master/main названия, которые могут отличаться

---

## Если хотите работать в команде:

Стоит зарегистрироваться на GitHub, интерфейс интуитивно понятен, понадобится потратить немного времени, зато после будет удобно работать в команде

_в целом это очень удобная платформа с кучей open source проектов в котрых можно поучавствовать даже без доступа к основной ветви проекта, для этого можно будет создать отдельную ветку и клонировать репозиторий, чтобы у себя вносить изменения_

**git clone "ссылка на репозиторий"**

Здесь вносите изменения и потом коммитите и пушите проект, в дальнейшем его могут даже рассмотреть в качестве добавления в основную ветвь!!!

---

# Важный пункт по поводу файлов README.md

Это очень удонбо, заходить на чей-то проект и узнавать всю важную информацию в одном красиво оформленном текстововм файле

[Ссылка на шпаргалку по markdown](https://github.com/yiqes/first-project/blob/master/README.md)

---
