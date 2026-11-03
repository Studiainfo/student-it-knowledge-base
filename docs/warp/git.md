# Ściąga: podstawowe polecenia Git

| Polecenie | Przykład | Opis |
|---|---|---|
| `git clone` | `git clone URL` | Pobiera repozytorium i tworzy lokalny katalog. |
| `git status` | `git status` | Pokazuje gałąź oraz pliki zmienione i przygotowane. |
| `git add` | `git add docs/warp/git.md` | Dodaje konkretny plik do obszaru staging. |
| `git commit` | `git commit -m "docs: add Git cheatsheet"` | Zapisuje przygotowane zmiany z czytelnym komunikatem. |
| `git push` | `git push -u origin feature/git-cheatsheet` | Publikuje gałąź i ustawia śledzenie. |
| `git pull` | `git pull --ff-only origin main` | Pobiera zmiany bez tworzenia nieoczekiwanego merge commita. |
| `git fetch` | `git fetch origin` | Pobiera informacje o zmianach bez modyfikowania plików roboczych. |
| `git branch` | `git branch` | Wyświetla lokalne gałęzie i oznacza aktywną. |
| `git switch` | `git switch -c feature/nazwa` | Tworzy gałąź roboczą i przełącza na nią. |
| `git log` | `git log --oneline -5` | Pokazuje skrócony podgląd pięciu ostatnich commitów. |


```bash
git switch main
git pull --ff-only origin main
git switch -c feature/nazwa
git add plik.md
git commit -m "docs: opis zmiany"
git push -u origin feature/nazwa
```