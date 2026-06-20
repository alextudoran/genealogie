# Reguli de documentare

## 1. Separăm faptele de ipoteze

Nu transformăm presupunerile în afirmații genealogice.

Folosește rubricile:

- Confirmat
- Probabil
- Posibil
- Speculativ
- Respins

## 2. Fiecare afirmație importantă trebuie să aibă sursă

Orice naștere, căsătorie, deces, relație părinte-copil, localizare sau identificare trebuie legată de un document, o transcriere, o notă de arhivă sau o sursă orală marcată ca atare.

## 3. O persoană = un fișier

Persoanele se documentează în `people/`, preferabil grupate după familie.

Exemplu:

```text
people/lacanu/tudor-t-lacanu.md
```

## 4. Un document = un fișier

Documentele se documentează separat de concluziile despre persoane.

Exemplu:

```text
documents/archive-files/vn-f-00021-3-1908-153.md
```

## 5. Indexurile nu conțin analiză

Indexurile sunt liste de navigare. Concluziile stau în fișierele de persoane, familii, documente sau ipoteze.

## 6. Ipotezele au nivel de încredere

Folosește una dintre valorile:

- Ridicat
- Mediu
- Scăzut
- Foarte scăzut

Nu folosi procente false dacă nu există o bază clară.

## 7. Necunoscut este o valoare validă

Nu inventăm nume, părinți sau legături. Dacă o persoană nu poate fi identificată, primește fișier temporar în `people/unknown/`.

## 8. Jurnalul de cercetare este cronologic

Orice sesiune semnificativă se notează în `research-log/` cu data, sursele analizate, concluziile și următoarele acțiuni.

## 9. Citarea internă

Când o pagină folosește altă pagină din repo, folosește link relativ Markdown.

Exemplu:

```markdown
Vezi [VN-F-00021-3-1908-153](../../archive-references/vn-f-00021-3-1908-153.md).
```

## 10. Date despre persoane vii

Nu se publică date personale despre persoane vii într-un repository public. Dacă repository-ul rămâne public, documentele sensibile trebuie omise, anonimizate sau mutate într-un spațiu privat.
