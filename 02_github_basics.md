# Modulul 2: GitHub - Portofoliul tău online 🌐

Dacă Git este "Save"-ul de pe calculatorul tău, **GitHub** este "Cloud"-ul. Este locul unde programatorii își țin codul pentru a nu-l pierde și pentru a colabora cu alții.

Este ca un Facebook pentru programatori, dar în loc de poze cu pisici (bine, sunt și alea uneori), avem cod.

## Pasul 1: Crearea unui "Repository" (Repo)

1.  Intră pe [github.com](https://github.com) și fă-ți un cont (e gratis).
2.  Apasă pe butonul `+` din dreapta sus -> **New repository**.
3.  Dă-i un nume (de ex: `primul-meu-proiect`).
4.  Apasă **Create repository**.

## Pasul 2: Conectarea

După ce ai creat repo-ul, GitHub îți va da o listă de comenzi. Dacă ai dat deja `git init` (cum am discutat în Modulul 1), ne interesează partea cu "push an existing repository".

Va arăta cam așa:

```bash
git remote add origin https://github.com/USERNAME/NUME-PROIECT.git
git branch -M main
git push -u origin main
```

### Ce înseamnă asta?

*   `git remote add origin ...`: Îi spune calculatorului tău: "Hei, serverul principal (origin) pentru acest cod este la această adresă".
*   `git branch -M main`: Redenumește ramura principală în "main" (standardul modern).
*   `git push -u origin main`: "Împinge" (upload) tot codul tău pe server.

## Pasul 3: Fluxul zilnic

De acum înainte, de fiecare dată când lucrezi:

1.  Scrii cod.
2.  `git add .` (Pregătești modificările)
3.  `git commit -m "Mesaj"` (Salvezi local)
4.  `git push` (Trimiți pe net)

Gata! Codul tău e în siguranță.

---
[Următorul pas: Modulul 3 - Colaborarea cu AI](./03_ai_development.md)
