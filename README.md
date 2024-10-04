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

---

Sprawdza stan plików.

```
git status
```

Polecenie [git status](./git/git-status.sh) śledzi tylko pliki dodane do przechowalni (czyli edytowane pliki, które 
nie mają być uwzględniane w migawce).

> Git przechowuje dane w nietypowy sposób, traktując je jak 
serię migawek (_ang. snapshots_) wszystkich plików, które są 
dodane do poczekalni (_ang. staging area_). Za każdym razem, gdy 
tworzysz **commit**, Git tworzy obraz przedstawiający aktualny stan 
wszystkich plików i zapisuje referencję do tej migawki.
