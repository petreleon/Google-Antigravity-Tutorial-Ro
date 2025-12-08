# Modulul 1: Bazele Git 💾

Imaginează-ți că scrii un eseu lung. Din când în când, dai "Save As..." și îl numești "Eseu_v1", "Eseu_v2", "Eseu_Final_BUN".

**Git** face fix asta pentru codul tău, dar mult mai inteligent. Este un sistem care ține minte istoria modificărilor tale.

## Pasul 1: Instalarea (dacă nu e deja instalat)

Verifică dacă ai Git instalat deschizând terminalul și scriind:

```bash
git --version
```

Dacă vezi un număr (ex: `git version 2.39.0`), ești gata!

## Pasul 2: Inițializarea unui proiect

Când începi un proiect nou, trebuie să-i spui lui Git "Hei, urmărește dosarul ăsta!".

Comanda magică este:

```bash
git init
```

Asta creează un dosar ascuns `.git` unde se ține toată istoria.

## Pasul 3: "Salvarea" modificărilor

În Git, salvarea se face în doi pași:

1.  **Pregătirea (Stage)**: Alegi ce fișiere vrei să incluzi în salvare.
    ```bash
    git add .
    ```
    (Punctul `.` înseamnă "tot ce s-a schimbat").

2.  **Confirmarea (Commit)**: Faci "poza" efectivă a codului și îi pui o etichetă.
    ```bash
    git commit -m "Mesaj care descrie ce am făcut"
    ```

### Exemplu concret:

Să zicem că ai creat fișierul `README.md`.

```bash
git add README.md
git commit -m "Adaugat introducere"
```

## Pasul 4: Verificarea stării

Ca să vezi ce fișiere s-au modificat și nu au fost salvate încă:

```bash
git status
```

Ca să vezi istoricul salvărilor anterioare:

```bash
git log
```

## 🎯 Misiunea ta

1.  Deschide terminalul.
2.  Dă `git init` în acest folder (dacă nu e deja un repo git).
3.  Dă `git add .` pentru a pregăti aceste fișiere noi.
4.  Dă `git commit -m "Adaugat primele module de tutorial"` pentru a salva.

---
[Următorul pas: Modulul 2 - GitHub Basics](./02_github_basics.md)
