# Szkolenie z Gita

## 1. Przygotowania

### Stworzenie konta na GitHub

### Zainstaluj Visual Studio Code

### Zainstaluj Git / Git Bash (Windows)

#### Podstawowe polecenia w Bashu

## 2. Tworzenie repozytorium z użyciem polecenia `git`

### Klucze publiczne i prywatne (`ssh-keygen`)

### `git init`

### `git clone` + repo na GitHubie

### `git config` - pierwszy commit

### Plik `.gitignore`

## 3. Praca na repozytorium

### `git add` 

- Dodaje pliki, które chcemy wysłać do przestrzni przed commitem.

### `git commit`

- Rejestruje zmiany w repozytorium i przekazuje je do następnego przesłania.
- Pomaga rozdzielić zmiany wprowadzone przez użytkowników.

### `git diff`

- Diff pokazuje domyslnie roznice pomiedzy zmianami wprowadzonymi w repozytorium przez nas, a stanem biezacym repozytorium (ostatnim commitem).


### `git status` 

- Pokazuje które pliki zostały zmodyfikowane i dodane lub nie do commita.
- Pokazuje status obecnie aktywnego repozytorium, przede wszystkim odnośnie zmian wprowadzonych w plikach.
- Status pozwala na sprawdzenie plikow, ktore zostaly zmodyfikowane, dodane lub usuniete na repozytorium.

### `git log` - komenda

- Pokazuje wprowadzone zmiany w naszym repozytorium
- Wyświetla wszystkie wprowadzone "commit" do repozytorium
- Pokazuje wszystkie commity zrobione do miejsca w drzewie, w ktorym sie
znajdujemy.

## 4. Praca zespołowa.

### `git remote`
- Zarządza gałęziami śledzonego repozytorium. Pozwala nam zobaczyc i ustawic zewnetrzne repozytoria dla naszego repozytorium
(np. na innym serwerze)

### `git push`

- Wysyła pliki repozytorium lokalnego oznaczone "commitem" do zdalego repozytorium

### `git fetch`

- Pobiera dane z repozytorium zdalnego, nie zmieniając plików lokalnych
- nie zmienia glowy (HEAD) naszego repozytorium 

### `git pull`

- Pobiera pliki z repozytorium zdalnego, zastępując pliki w lokalnym repozytorium
- robi `git fetch`, a potem stara sie zmienic HEAD na najnowszy. 
- Jesli mamy wlasne commity, odpala `git merge`, zeby zmerdzowac je ze stanem repozytorium lokalnego


### Pull requesty

### Forki na GitHubie

## 5. Branches / rozgałęzianie repozytorium

### `git checkout`

- Zmienia obecny branch na inny

### `git branch`

### `git merge`

### Rozwiązywanie konfliktów

### Gitflow workflow

#### `git tag`

## 6. Cofanie zmian i nadpisywanie

### `git checkout FILE`

### `git clean`

### `git revert`

### `git reset`

### `git rm`

### `git commit --amend`

## 7. Podsumowanie i czyszczenie repozytorium

## 8. Do przeczytania

1. https://www.atlassian.com/git
2. https://gitexercises.fracz.com/exercise/case-sensitive-filename
3. https://guides.github.com/introduction/git-handbook/
4. https://github.github.com/training-kit/downloads/github-git-cheat-sheet/
5. https://stormit.pl/git/
6. https://git-scm.com/book/pl/v2/Pierwsze-kroki-Podstawy-Git
