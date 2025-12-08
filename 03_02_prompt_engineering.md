# 3.2 Prompt Engineering: Arta de a Cere 🗣️

"Prompt Engineering" sună complicat, dar e simplu: înseamnă **să știi să ceri ca să primești ce vrei**.

AI-ul este un "literalist". Dacă ceri prost, primești prost.

## 1. Structura unui Prompt Perfect

Un prompt bun ar trebui să aibă 3 elemente:

1.  **Rolul**: Cine vrei să fie AI-ul?
2.  **Contextul**: Ce știi tu și ce vrei să afli?
3.  **Formatul**: Cum vrei să arate răspunsul?

### Exemplu PROST ❌
> "Fă-mi o pagină web."

### Exemplu BUN ✅
> "**(Rol)** Vreau să acționezi ca un expert în Web Design și HTML5.
> **(Context)** Creează o pagină de pornire pentru o pizzerie numită 'Luigi'. Vrem să aibă un meniu simplu, o poză de fundal și un formular de contact. Folosește culorile steagului Italiei.
> **(Format)** Dă-mi codul într-un singur fișier `index.html` cu CSS inclus în tag-ul `<style>`."

## 2. Tehnici Avansate (dar Simple)

### A. Few-Shot Prompting (Dă-i exemple)
În loc să explici teoria, dă-i un exemplu de cum vrei să arate rezultatul.

> "Vreau să transformi numele de orașe în format JSON.
> Exemplu:
> Input: București
> Output: { 'oras': 'București', 'tara': 'România' }
>
> Input: Paris
> Output: ..."

### B. Chain of Thought (Gândește cu voce tare)
Când ai o problemă de logică, cere-i AI-ului să o rezolve pas cu pas.

> "Calculează câți bani am nevoie pentru vacanță. **Gândește pas cu pas și explică fiecare calcul înainte să dai totalul.**"

Asta reduce drastic greșelile de calcul.

### C. "Refuză să ghicești"
Uneori AI-ul inventează. Poți să adaugi asta în prompt:

> "...Dacă nu știi răspunsul sau nu ești sigur, spune-mi 'Nu știu', nu inventa informații."

## Exercițiu
Încearcă să ceri un script Python care să sorteze fișierele dintr-un folder pe categorii (poze, documente, etc). Folosește structura de mai sus (Rol, Context, Format).

---
[Mergi la Lecția 3.3: Fluxul de Lucru](./03_03_ai_workflow.md)
