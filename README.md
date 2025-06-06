# Git Навигация

pwd (от англ. <strong><em>p</em></strong><em>rint <strong>w</strong>orking <strong>d</strong>irectory</em>, «показать рабочую папку») — покажи, в какой я папке;

ls (от англ. <strong><em>l</em></strong><em>i<strong>s</strong>t directory contents</em>, «отобразить содержимое директории») — покажи файлы и папки в текущей папке;

ls -a — покажи также скрытые файлы и папки, названия которых начинаются с символа .;

cd first-project (от англ. <strong><em>c</em></strong><em>hange <strong>d</strong>irectory</em>, «сменить директорию») — перейди в папку first-project;

cd first-project/html — перейди в папку html, которая находится в папке first-project;

cd .. — перейди на уровень выше, в родительскую папку;

cd ~ — перейди в домашнюю директорию (/Users/Username);

cd / — перейди в корневую директорию.

#### Работа с файлами и папками

#### Создание

touch index.html (англ. touch, «коснуться») — создай файл index.html в текущей папке;

touch index.html style.css script.js — если нужно создать сразу несколько файлов, можно напечатать их имена в одну строку через пробел;

mkdir second-project (от англ. <strong><em>m</em></strong><em>a<strong>k</strong>e <strong>dir</strong>ectory</em>, «создать директорию») — создай папку с именем second-project в текущей папке.

#### Копирование и перемещение

cp file.txt ~/my-dir (от англ. <strong><em>c</em></strong><em>o<strong>p</strong>y</em>, «копировать») — скопируй файл в другое место;

mv file.txt ~/my-dir (от англ. <strong><em>m</em></strong><em>o<strong>v</strong>e</em>, «переместить») — перемести файл или папку в другое место.

#### Чтение

cat file.txt (от англ. <em>con<strong>cat</strong>enate and print</em>, «объединить и распечатать») — распечатай содержимое текстового файла file.txt.

#### Удаление

rm about.html (от англ. <strong><em>r</em></strong><em>e<strong>m</strong>ove</em>, «удалить») — удали файл about.html;

rmdir images (от англ. <strong><em>r</em></strong><em>e<strong>m</strong>ove <strong>dir</strong>ectory</em>, «удалить директорию») — удали папку images;

rm -r second-project (от англ. <strong><em>r</em></strong><em>e<strong>m</strong>ove,</em> «удалить» + <strong><em>r</em></strong><em>ecursive</em>, «рекурсивный») — удали папку second-project и всё, что она содержит.

## Git Инициализация репозитория

git init (от англ. <strong><em>init</em></strong><em>ialize</em>, «инициализировать») — инициализируй репозиторий.

#### Подготовка файла к коммиту

git add todo.txt (от англ. <em>add</em>, «добавить») — подготовь файл todo.txt к коммиту;

git add --all (от англ. <em>add</em>, «добавить» + <em>all</em>, «всё») — подготовь к коммиту сразу все файлы, в которых были изменения, и все новые файлы;

git add . — подготовь к коммиту текущую папку и все файлы в ней.

#### Создание коммита

git commit -m "Комментарий к коммиту." (от англ. commit, «совершать», «фиксировать» + <strong><em>m</em></strong><em>essage,</em> «сообщение») — сделай коммит и оставь комментарий, чтобы было проще понять, какие изменения внесены.

#### Просмотр информации о коммитах

git log (от англ. <em>log</em>, «журнал [записей]») — выведи подробную историю коммитов.

#### Просмотр состояния файлов

git status (от англ. <em>status</em>, «статус», «состояние») — покажи текущее состояние репозитория.