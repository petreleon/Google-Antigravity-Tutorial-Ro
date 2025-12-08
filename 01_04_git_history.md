# 1.4 Istoricul: Jurnalul Căpitanului 📜

Ai făcut câteva modificări. Ai "sigilat cutii" (commits). Dar unde sunt ele?

## `git log`: Citirea trecutului

Ca să vezi istoria proiectului tău, scrie:

```bash
git log
```

Vei vedea ceva de genul:

```text
commit a1b2c3d4e5... (un cod lung si ciudat)
Author: Numele Tau <email@tau.com>
Date:   Mon Dec 8 23:00:00 2025

    Prima pagina din jurnal
```

Acel cod lung (`a1b2c3...`) este ID-ul unic al salvării tale. E ca un cod de bare.

## `git status`: Verificarea prezentului

Aceasta este comanda pe care o vei folosi cel mai des. Îți spune starea curentă.

```bash
git status
```

Îți va spune:
*   Ce fișiere ai modificat dar nu le-ai pus în cutie (Unstaged).
*   Ce fișiere sunt în cutie dar nu sunt sigilate (Staged).
*   Dacă totul e "curat" (Clean).

## O scurtă notă despre "Călătoria în Timp" (`git checkout`)

Dacă vrei să vezi cum arăta proiectul în trecut, poți folosi acel cod lung de la `git log`:

```bash
git checkout a1b2c3
```

⚠️ **Atenție**: Asta te duce într-un mod "Detached HEAD" (Sună înfricoșător, nu?). Înseamnă că doar privești, nu poți schimba istoria ușor de aici.

Ca să te întorci în prezent:

```bash
git checkout main
```

(Sau `master`, dacă ai o versiune mai veche de Git).

---
## Ai absolvit Modulul 1! 🎓

Ai învățat să manipulezi timpul. Ești gata să îți pui creațiile pe internet.

👉 **[Mergi la Modulul 2: GitHub Basics](./02_github_basics.md)**
