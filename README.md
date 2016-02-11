# StepCTF-2015
Репозиторий тасков для SpisokCTF 2015 -- CTF-соревнования по информационной безопасности.

## Оформление тасков

Каждый таск -- отдельная директория (название директории -- название таска), в ней:

1. Файл `summary.yml` в формате YAML, с описанием, автором, стоимостью, категорией.
В пункте 'description' могут быть ссылки на сторонние файлы, их размещаем в аттачменты на Степике.

2. Папка `solution/` с решением (с файликом `solution.html`, в котором указан возможный подход к решению, используемые скрипты, сторонние проги). Там же - hints.html с возможными хинтами.

3. Папка `create/`, в ней - всякие файлы, необходимые для создания этого задания.

#### Флаги

Формат: `STCTF#\w{6,}#`?

Примеры: `STCTF#this_is_a_flag#`, `STCTF#h311o_pr3TtY#`, `STCTF#31337_31415#`


## Вопросы, проблемы?

Открывайте гитхабовские Issue.