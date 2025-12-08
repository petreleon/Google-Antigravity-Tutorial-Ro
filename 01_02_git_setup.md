# 1.2 Configurare: Pașaportul de Programator 🛂

Înainte să intrăm în aeroportul programării, trebuie să ne arătăm pașaportul. Git trebuie să știe **cine** face modificările.

De ce? Pentru că atunci când vei lucra în echipă (chiar și cu viitorul tu), vrei să știi cine a scris codul ăla genial (sau cine a stricat totul).

## Pasul 1: Verificarea

Deschide terminalul. Nu-ți fie frică de ecranul negru, e prietenul tău. Scrie:

```bash
git --version
```

Dacă primești ceva de genul `git version 2.x.x`, ești bine. Dacă nu, instalează Git de pe [git-scm.com](https://git-scm.com/).

## Pasul 2: Identitatea

Acum trebuie să îi spunem lui Git cine ești. Aceste setări se fac **o singură dată** pe un calculator nou.

Scrie (înlocuind cu numele și emailul tău):

```bash
git config --global user.name "Numele Tau"
git config --global user.email "emailul_tau@exemplu.com"
```

*   **Nota**: Emailul nu trebuie să fie neapărat unul real, dar e bine să fie cel pe care îl vei folosi pe GitHub mai târziu.

## Pasul 3: Vizualizarea

Ca să verifici că totul e în regulă:

```bash
git config --list
```

Ar trebui să îți vezi numele și emailul acolo.

Gata! Ai pașaportul vizat. E timpul să plecăm în călătorie.

---
👉 **[Lecția 1.3: Fluxul de Lucru](./01_03_git_workflow.md)**
