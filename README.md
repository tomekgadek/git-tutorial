# Git tutorial

_Kolekcja poleceń systemu kontroli wersji Git. Notatki powstały na podstawie książki..._

> **Git i GitHub. Kontrola wersji, zarządzanie projektami i zasady pracy zespołowej** 
> 
> ~Mariot Tsitoara

![git and github book](./img/git-and-github.jpg)

## Git, polecenia

Inicjowanie repozytorium / bazy danych. Utworzony zostanie plik **.git**. [Inicjalizuje gita](./git/git-init.sh).

```git
git init
```

---

Wewnątrz katalogu **.git** znajduje się plik **HEAD**. Wskazuje gałąź, na której aktualnie pracuje użytkownik.

![git catalog](./img/git-catalog.png)

---

[Klonowanie](./git/git-clone.sh). Kopiuje całą historię wraz z migawkami.

```git
git clone
```