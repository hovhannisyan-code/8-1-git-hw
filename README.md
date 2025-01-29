# Домашнее задание к занятию «Git»

### Инструкция по выполнению домашнего задания

1.  Сделайте `fork` [репозитория c шаблоном решения](https://github.com/netology-code/sys-pattern-homework) к себе в GitHub и переименуйте его по названию или номеру занятия, например, https://github.com/имя-вашего-репозитория/gitlab-hw или https://github.com/имя-вашего-репозитория/8-03-hw.
2.  Выполните клонирование этого репозитория к себе на ПК с помощью команды `git clone`.
3.  Выполните домашнее задание и заполните у себя локально этот файл README.md:
    - впишите сверху название занятия, ваши фамилию и имя;
    - в каждом задании добавьте решение в требуемом виде — текст, код, скриншоты, ссылка;
    - для корректного добавления скриншотов используйте [инструкцию «Как вставить скриншот в шаблон с решением»](https://github.com/netology-code/sys-pattern-homework/blob/main/screen-instruction.md);
    - при оформлении используйте возможности языка разметки md. Коротко об этом можно посмотреть в [инструкции по MarkDown](https://github.com/netology-code/sys-pattern-homework/blob/main/md-instruction.md).
4.  После завершения работы над домашним заданием сделайте коммит `git commit -m "comment"` и отправьте его на GitHub `git push origin`.
5.  Для проверки домашнего задания в личном кабинете прикрепите и отправьте ссылку на решение в виде md-файла в вашем GitHub.
6.  Любые вопросы по выполнению заданий задавайте в чате учебной группы или в разделе «Вопросы по заданию» в личном кабинете.

Желаем успехов в выполнении домашнего задания!

---

### Задание 1

**Что нужно сделать:**

1. Зарегистрируйте аккаунт на [GitHub](https://github.com/).
1. Создайте **новый отдельный публичный репозиторий**. Обязательно поставьте галочку в поле «Initialize this repository with a README».
1. Склонируйте репозиторий, используя https протокол `git clone ...`.
1. Перейдите в каталог с клоном репозитория.
1. Произведите первоначальную настройку Git, указав своё настоящее имя и email: `git config --global user.name` и `git config --global user.email johndoe@example.com`.
1. Выполните команду `git status` и запомните результат.
1. Отредактируйте файл README.md любым удобным способом, переведя файл в состояние Modified.
1. Ещё раз выполните `git status` и продолжайте проверять вывод этой команды после каждого следующего шага.
1. Посмотрите изменения в файле README.md, выполнив команды `git diff` и `git diff --staged`.
1. Переведите файл в состояние staged или, как говорят, добавьте файл в коммит, командой `git add README.md`.
1. Ещё раз выполните команды `git diff` и `git diff --staged`.
1. Теперь можно сделать коммит `git commit -m 'First commit'`.
1. Сделайте `git push origin master`.

В качестве ответа добавьте ссылку на этот коммит в ваш md-файл с решением.

[Commit url](https://github.com/hovhannisyan-code/8-1-git-hw/commit/0afe4a272e825e55f1a8f1778e66d8c40d2db80c)

### Задание 2

**Что нужно сделать:**

1. Создайте файл .gitignore (обратите внимание на точку в начале файла) и проверьте его статус сразу после создания.
1. Добавьте файл .gitignore в следующий коммит `git add...`.
1. Напишите правила в этом файле, чтобы игнорировать любые файлы `.pyc`, а также все файлы в директории `cache`.
1. Сделайте коммит и пуш.

В качестве ответа добавьте ссылку на этот коммит в ваш md-файл с решением.

[Commit url](https://github.com/hovhannisyan-code/8-1-git-hw/commit/e84333da3b404d2298eee725c45221e5e471111c)

### Задание 3

**Что нужно сделать:**

1. Создайте новую ветку dev и переключитесь на неё.
2. Создайте в ветке dev файл test.sh с произвольным содержимым.
3. Сделайте несколько коммитов и пушей в ветку dev, имитируя активную работу над файлом в процессе разработки.
4. Переключитесь на основную ветку.
5. Добавьте файл main.sh в основной ветке с произвольным содержимым, сделайте комит и пуш . Так имитируется продолжение общекомандной разработки в основной ветке во время разработки отдельного функционала в dev ветке.
6. Сделайте мердж dev ветки в основную с помощью git merge dev. Напишите осмысленное сообщение в появившееся окно комита.
7. Сделайте пуш в основной ветке.
8. Не удаляйте ветку dev.

В качестве ответа прикрепите ссылку на граф коммитов https://github.com/ваш-логин/ваш-репозиторий/network в ваш md-файл с решением.

[Network url](https://github.com/hovhannisyan-code/8-1-git-hw/network)
