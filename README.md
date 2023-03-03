# XOR-Encritption


Acest proiect contine o implementare simpla a metodei xor de encriptare

> Link către repository-ul inițial : 

> Echipa noastră: XorT11am

> Numele echipei adverse: The Robotors

> Link GitHub către proiectul lor: https://github.com/alex2209alex/proiectAsc 

## Cerința 1: 

Scrieți scripturi python encrypt.py/decrypt.py care iau ca parametru în linia de comandă o cheie și un fișier și realizează criptarea/decriptarea XOR folosind cheia dată. Programul va folosi cheia pentru a cripta conținutul fișierului.

Cum se utilizează script-urile:


  Mediul de lucru


     Python 3.10.0


  Instrucțiuni pentru a rula in Windows


     se deschide CMD-ul / terminalul


     se accesează locația proiectului

     se introduc următoarele comenzi:

      python encrypt.py <parola> input.txt output                  -> (pentru criptare)
      python decrypt.py <parola> output input_recuperat.txt        -> (pentru decriptare)


> ATENȚIE!!! La introducerea comenzilor, în loc de <parola> va fi scrisă direct cheia folosită pentru criptare / decriptare, fără '<' , respectiv '>'.

  Aceiași pași se urmează și pe Ubuntu, dar comenzile conțin "python3" in loc de "python", deci:

     python3 encrypt.py <parola> input.txt output
  
     python3 decrypt.py <parola> output input_recuperat.txt
  
  
  

Documentație: https://docs.python.org/3/library/stdtypes.html

Sursa textului din input.txt: https://ro.m.wikisource.org/wiki/Ion/Glasul_p%C4%83m%C3%A2ntului

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


## Cerința 2: 
  
Aflați cheia cu care a fost criptat fișierul output al echipei adverse.

> Partea 1: Folosiți fișierul input.txt, output și fișierele sursă de pe pagina github a echipei adverse pentru a afla cheia (dacă cheia este disponibilă undeva pe pagina github a echipei adverse, folosiți-o; folosiți-vă de orice mijloace tehnice pentru a descoperi cheia).

Pentru a rezolva această cerință, ne-am folosit de scriptul cerinta2partea1.py. Pe măsură ce parcurgem câte un caracter din output-ul, respectiv input-ul adversarilor, reținem într-un string parola obținută prin XOR-area acestora și îl trecem prin funcția de hash. Dacă hash-ul parolei noastre coincide cu cel din encrypt-ul echipei adverse, afișăm parola.
  
Cheia pe care au folosit-o: parola121alorap

> Partea 2: Folosiți fișierul output și fișierele sursă de pe pagina github a echipei
adverse pentru a afla cheia (NU aveți voie să folosiți input.txt, chiar dacă echipa adversă a greșit cu ceva aflați cheia folosită (aveți acces la codul lor sursă) )

Pentru a rezolva această cerință, ne-am folosit de scriptul cerinta2partea1.py.
