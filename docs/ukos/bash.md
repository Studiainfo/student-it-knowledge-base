# Ściąga: podstawowe polecenia Bash

| Polecenie | Przykład | Opis |
|---|---|---|
| `pwd` | `pwd` | Wyświetla ścieżkę bieżącego katalogu. |
| `ls` | `ls -la` | Listuje pliki, także ukryte, w formacie szczegółowym. |
| `cd` | `cd docs/ukos` oraz `cd ..` | Przechodzi do katalogu lub do katalogu nadrzędnego. |
| `mkdir` | `mkdir -p docs/ukos` | Tworzy katalog wraz z brakującymi katalogami nadrzędnymi. |
| `touch` | `touch bash.md` | Tworzy pusty plik lub aktualizuje czas jego modyfikacji. |
| `cp` | `cp bash.md bash-backup.md` | Kopiuje plik; dla katalogów użyj opcji `-r`. |
| `mv` | `mv bash-backup.md archive.md` | Przenosi lub zmienia nazwę pliku. |
| `rm` | `rm archive.md` | Usuwa plik. **Uwaga:** operacja omija kosz i jest nieodwracalna. |
| `cat` | `cat bash.md` | Wyświetla zawartość pliku w terminalu. |
| `clear` | `clear` | Czyści widok terminala bez usuwania historii poleceń. |



```bash
pwd
mkdir -p projekt/docs
cd projekt/docs
touch notatki.md
cp notatki.md kopia.md
mv kopia.md archiwum.md
ls -la
cat notatki.md
rm archiwum.md
cd ..
clear
```