# 3.5 Capcane și Limite 🚧

Cu mare putere vine și mare responsabilitate (și câteva pericole).

## 1. "Hallucinations" (Halucinații)

AI-ul este antrenat să fie **de ajutor**, nu neapărat să fie **corect**. Uneori, dacă nu știe răspunsul, va inventa unul care *sună* plauzibil pentru a te mulțumi.

### Exemplu clasic:
Tu ceri o bibliotecă pentru o funcție obscură. AI-ul îți dă un nume: `pip install super-library-x`. Tu încerci și... nu există.

**Soluția**: Verifică întotdeauna dacă bibliotecile sau link-urile recomandate chiar există.

## 2. Securitatea Datelor 🔒

Acesta este cel mai important punct din tot capitolul.

**NU TRIMITE NICIODATĂ DATE SECRETE UNUI AI.**

*   ❌ Parole.
*   ❌ Chei API (API Keys).
*   ❌ Date personale (CNP, Carduri).
*   ❌ Secrete comerciale ale companiei (dacă nu ai aprobare).

Aceste conversații pot fi folosite pentru antrenarea viitoarelor modele. Consideră conversația ca fiind **Publică**.

### Cum faci dacă ai nevoie de ajutor cu cod care conține parole?
Anonimizează codul înainte să îl dai. În loc de `password="Secret123"`, pune `password="***"`.

## 3. Cunoștințe "Expirate" (Cutoff Date)

Modelele AI sunt antrenate pe date până la un anumit an (ex: 2023). Ele nu știu ce bibliotecă s-a lansat ieri, decât dacă au acces la internet (cum are Antigravity prin Google Search).

Dacă folosești un framework care se schimbă des (ca Next.js sau librării noi de AI), specifică-i versiunea: "Folosesc Next.js versiunea 14".

## Felicitări! 🎉

Ai terminat Modulul 3! Acum știi nu doar să scrii cod, ci să "manageriezi" un asistent AI pentru a scrie cod pentru tine.

Ești gata să construiești orice.

---
[Înapoi la Cuprinsul Modulului](./03_ai_development.md) | [Înapoi la Începutul Tutorialului](./README.md)
