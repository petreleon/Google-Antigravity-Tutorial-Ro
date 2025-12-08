# 3.3 Fluxul de Lucru (The Workflow) 🔄

Cum arată o zi din viața unui programator care folosește AI? Nu e magie, e proces.

Acesta este **Ciclul PROD** (Planifică - Redactează - Observă - Depanează).

## 1. Planifică (Plan)
Nu scrie cod imediat! Vorbește cu AI-ul despre *ce* vrei să faci.

> "Vreau să fac un joc Snake în Python. Ce biblioteci îmi recomanzi? Cum ar trebui să structurăm codul?"

Așteaptă răspunsul. Validarea planului este crucială. Dacă planul e prost, codul va fi prost.

## 2. Redactează (Draft)
Aici folosești tehnicile de Prompt Engineering (Lecția 3.2).

Cere codul pe bucăți!
*   ❌ "Fă tot jocul." (Risc mare de erori)
*   ✅ "Fă fereastra principală și bucla de joc. Nu adăuga încă șarpele."

## 3. Observă (Observe)
Ia codul, pune-l în editor și rulează-l.

*   Merg import-urile?
*   Apare fereastra?
*   Se comportă cum trebuie?

**NU** presupune că merge doar pentru că AI-ul a zis "Iată codul funcțional". Verifică!

## 4. Depanează (Debug)
Dacă merge, treci la următoarea funcționalitate ("Acum adaugă șarpele").
Dacă NU merge, intrăm în faza de Debugging (vezi Lecția 3.4).

## Exemplu de Sesiune

1.  **Tu**: "Vreau un script care descarcă videoclipuri de pe YouTube."
2.  **AI**: "Putem folosi `yt-dlp`. Iată planul..."
3.  **Tu**: "Arată bine. Dă-mi codul pentru instalare și descărcarea unui singur video."
4.  **AI**: (Generează cod)
5.  **Tu**: (Rulezi codul) -> *Eroare: Library not found*
6.  **Tu**: "Am primit eroarea asta..."
7.  **AI**: "Ah, trebuie să instalezi librăria cu `pip install...`"

Și tot așa, pas cu pas, până termini proiectul.

---
[Mergi la Lecția 3.4: Debugging](./03_04_debugging.md)
