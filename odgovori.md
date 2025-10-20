# Odgovori na test

1. Osnovni tipovi podataka u Pythonu su:
   - int (npr. 3)
   - float (npr. 4.3)
   - complex (npr. 3+4j)
   - string (npr. "tekst")
   - bool (npr. True/False)

2. Lista je promjenjiva kolekcija elemenata, tuple je nepromjenjiva, a set je neuređena kolekcija jedinstvenih elemenata.
   - lista = [1, 2, 3]
   - tuple = (1, 2, 3)
   - set = {1, 2, 3}

3. String se može podijeliti metodama:
   - split(): dijeli string po zadanom separatoru (npr. razmak)
   - partition(): dijeli string na tri dijela prema prvom pojavljivanju zadanog separatora
   - slicing: izdvaja dio stringa po indeksima

4. Objektno orijentirano programiranje (OOP) je način programiranja gdje se program sastoji od objekata koji imaju atribute i metode. Osnovne karakteristike su: enkapsulacija, nasljeđivanje, polimorfizam i apstrakcija.

5. Kod za ispis svih riječi odvojenih razmakom:

tekst = 'Ana ima jabuku, Marko ima krušku.'
rijeci = tekst.split()
print(rijeci)
