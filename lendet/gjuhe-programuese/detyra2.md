## Përshkrimi

Të shkruhet programi i cili menaxhon të dhënat e librave. Secili libër ka titullin, autorin, zhanrin, dhe vitin e botimit. Zhanri mund të jetë njëra nga vlerat: `Roman`, `Poezi`, dhe `Biografi`.

1. **(1p)** Të deklarohet numërimi `Zhanri` me vlerat `Roman`, `Poezi`, `Biografi`.
2. **(2p)** Të deklarohet struktura `Libri` me fushat `titulli` (string), `autori` (string), `zhanri` (Zhanri), `viti_botimit` (nr. plotë).
3. **(4p)** Të shkruhet funksioni me emrin `shtyp` i cili pranon një parametër të tipit `Libri` dhe nuk kthen rezultat. Ky funksion shtyp në ekran të dhënat e librit sikur në shembullin e mëposhtëm.
4. **(4p)** Të shkruhet funksioni me emrin `numri_librave_roman(Libri librat[], int n)`, i cili në vargun e librave të dhënë si parametër numëron sa nga ta e kanë zhanrin e barabartë me `Roman`. Numri i këtyre librave të kthehet si rezultat i funksionit përmes **return**.
5. Në `main` të realizohen kërkesat në vijim:
   1. **(1p)** Të deklarohet një varg që mban tipet `Libri` me gjatësi **N=3** dhe të inicializohet me vlera sipas dëshirës.
   2. **(2p)** Përmes një unaze, të shtypen të gjithë anëtarët e vargut në ekran duke thirrur funksionin `shtyp` për secilin anëtar të vargut.
   3. **(1p)** Të thirret funksioni `numri_librave_roman` duke ia dërguar si argumente vargun dhe gjatësinë e tij. Rezultati i kthyer nga funksioni të shtypet në ekran sikur në shembullin e mëposhtëm.

**Kujdes: Detyra që nuk kompajllohet ka minus 3 pikë!**

Shembull të ekzekutimit të programit gjeni në vijim:

```
1. "Gjenerali i Ushtrisë së Vdekur", Ismail Kadare, Roman, 1963
2. "Lumi i vdekur", Jakov Xoxa, Roman, 1971
3. "Einstein: Jeta dhe Universi", Walter Isaacson, Biografi, 2007

Numri i librave te zhanrit Roman: 2.
```
