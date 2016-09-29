##Полезные алиасы

`git` → `g` — сокращает команду `git` до одной буквы.

`git status -s` → `gs` — вывод `git status` в коротком формате.

`git push` → `gps`

`git pull --ff-only` → `gpl` — пуллим изменения, используя методику --ff-only

`git commit -va` → `gc` — автоматически стейджим все изменения `-a` и делаем коммит, в редакторе показываем какие изменения у нас были сделаны `-v`

`git stash && git pull --ff-only && git stash pop` → `gu` — прячем в стэш, пуллим последние изменения из ветки, в которой находимся, потом возвращаем свои изменения на место.

`git add -A && gu && gc && gps` → `gsm` — собирает все обновления в ветке, прячет их, проверяет, обновилась ли ветка на сервере и после этого отправляет изменения в репозиторий.

Полный список всех используемых алиасов можно посмотреть в нашем репозитории с dotfiles. Там же можно посмотреть на gitconfig.