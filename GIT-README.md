# Polecenia w systemie Git

- `git init` - utworzenie repozytorium Git w katalogu, z którego pisane jest polecenie
- `git remote add origin <link do repozytorium na GitHubie>` - przypisuje repozytorium do jego odpowiednika na GitHubie
- `git branch -M <nazwa gałęzi>` - zmienia nazwę głównej gałęzi
- `git checkout -b <nazwa gałęzi>` - tworzy nową gałąź na podstawie tej, na której się teraz znajdujemy
- `git checkout <nazwa gałęzi>` - zmienia obecną gałąź na <nazwa gałęzi>
- `git add <katalog/plik>` - dodaje katalog/plik do zarejestrowanych zmian
- `git commit -m "<Treść commita>"` - tworzy commit (zatwierdzenie) zmian zarejestrowanych przez `git add`
- `git push <nazwa remote> <nazwa gałęzi>` - wysłanie zmian do repozytorium
- `git fetch` - sprawdzenie czy są nowe zmiany w repozytorium
- `git pull` - aktualizacja danych z repozytorium do obecnej gałęzi
- `git merge <nazwa gałęzi>` - pobranie danych z <nazwa gałęzi> do gałęzi na której się teraz znajdujemy