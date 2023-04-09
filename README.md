# proiectPOO

Firma de curierat

Acest cod definește mai multe clase și implementează un program care manipulează obiecte create din aceste clase. Voi explica pe scurt fiecare clasă și funcționalitatea asociată.

Clasa Angajat:
Această clasă definește un angajat, având atribute precum nume, vechime, funcție și salariu. Clasa are constructori, getteri, metoda marire pentru a verifica dacă salariul angajatului trebuie mărit, și metode pentru afișarea datelor unui angajat.

Clasa Client:
Această clasă definește un client, având atribute precum nume, adresă și cod poștal. Clasa are constructori și getteri pentru a accesa atributele.

Clasa Colet:
Această clasă definește un colet, având atribute precum id, client, greutate, dimensiuni și adresă de destinație. Clasa are constructori și o metodă get_dimensiune pentru a calcula volumul coletului.

Clasa Masina:
Această clasă definește o mașină, având atribute precum angajat (șofer), număr de înmatriculare, marcă și model. Clasa are constructori.

Clasa Livrare:
Această clasă definește o livrare, având atribute precum colet, mașină, angajat, dată de livrare și preț. Clasa are constructori și o metodă verificare_dimensiune care verifică dacă un colet încap în mașină sau nu.

Clasa TabelAngajati:
Această clasă definește un tabel de angajați, având un vector de angajați și numărul de angajați. Clasa are constructori, un destructor pentru a elibera memoria alocată dinamic, o metodă adaugaAngajat pentru a adăuga un angajat în tabel și o metodă calculeazaSalariuMediu pentru a calcula salariul mediu al angajaților din tabel.

În funcția main, sunt create câteva obiecte ale acestor clase și sunt apelate diverse metode pentru a demonstra funcționalitatea programului. De exemplu, se verifică dacă coletele încap în mașini, se calculează salariul mediu al angajaților din tabelul de angajați și se afișează informații despre angajați.
