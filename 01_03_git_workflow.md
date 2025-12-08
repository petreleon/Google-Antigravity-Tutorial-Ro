# 1.3 Fluxul de Lucru: Cutia, Sigiliul și Arhiva 📦

E timpul să facem magie. Pentru asta, vom avea nevoie de un "laborator".

## Pasul 1: Crearea Laboratorului

Nu vom lucra "în acest folder". Vreau să îți creezi propriul tău spațiu.

1.  Deschide un terminal.
2.  Mergi pe Desktop (sau unde vrei tu): `cd ~/Desktop`
3.  Fă un folder nou: `mkdir ProiectulMeuSecret`
4.  Intră în el: `cd ProiectulMeuSecret`

Acum ești stăpânul acestui folder vid.

## Pasul 2: Inițializarea (`git init`)

Spune-i lui Git să înceapă monitorizarea:

```bash
git init
```

Boom! Git a instalat camere de supraveghere invizibile (folderul `.git`).

## Pasul 3: Crearea unui fișier

Creează un fișier simplu. Poți folosi un editor de text sau comanda asta rapidă:

```bash
echo "Salut Lume" > jurnal.txt
```

## Pasul 4: Cutia de Expediere (`git add`)

Aici intervine un concept cheie: **Staging Area** (Zona de Pregătire).

Imaginează-ți că vrei să trimiți un pachet.
1.  Pui obiectele pe masă (Ai creat fișierul).
2.  Pui obiectele în cutie (Asta e `git add`).
3.  Sigilezi cutia (Asta e `git commit`).

Hai să punem fișierul în cutie:

```bash
git add jurnal.txt
```

Sau, dacă vrei să pui TOT ce e pe masă în cutie:

```bash
git add .
```

## Pasul 5: Sigilarea (`git commit`)

Acum că totul e în cutie, trebuie să o sigilăm și să scriem pe ea ce conține.

```bash
git commit -m "Prima pagina din jurnal"
```

Felicitări! Ai creat primul tău "Save Point".

---
👉 **[Lecția 1.4: Istoricul și Jurnalul Căpitanului](./01_04_git_history.md)**
