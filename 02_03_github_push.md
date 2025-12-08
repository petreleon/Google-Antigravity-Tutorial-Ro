# 2.3 Teleportarea: Push & Remote 🚀

Ai codul pe calculator (Git).
Ai casa goală pe GitHub (Repo).

Cum le conectăm? Construim un portal numit **Remote**.

## Pasul 1: Link-ul

În pagina repo-ului tău de pe GitHub, vei vedea un link care se termină în `.git`.
Exemplu: `https://github.com/numele-tau/nume-proiect.git`

Copiază-l.

## Pasul 2: Conexiunea

Întoarce-te în terminal, în folderul proiectului tău (`ProiectulMeuSecret` din Modulul 1).

Scrie:

```bash
git remote add origin https://github.com/numele-tau/nume-proiect.git
```

*   `git remote add`: "Git, adaugă o telecomandă..."
*   `origin`: "...numește-o 'origin' (e standardul)..."
*   `https://...`: "...și leag-o la adresa asta."

## Pasul 3: Teleportarea (`push`)

Acum vine momentul adevărului. Să trimitem codul sus.

```bash
git push -u origin main
```

1.  GitHub te va ruga să te loghezi (nume și parolă, sau prin browser).
2.  Vei vedea niște bare de progres.
3.  "Branch 'main' set up to track remote branch 'main'".

🎉 **Victorie!**

Dacă intri acum pe site-ul GitHub și dai Refresh, vei vedea fișierele tale acolo.

## De acum înainte...

Nu mai trebuie să scrii tot cârnatul de comandă. Când mai faci modificări și vrei să le urci:

```bash
git push
```

Atât. Simplu.

---
👉 **[Lecția 2.4: Multiplayer Mode](./02_04_github_social.md)**
