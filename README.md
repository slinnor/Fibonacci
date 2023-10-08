# Fibonacci
Fibonacciho posloupnost je doufa vsem znama, pokud ne, Google je vas nejlepsi kamarad. V tomto ukolu naprogramujete metody pro spravu Fibonacciho posloupnosti - bude velice jednoducha, uzivatel si napise prvek, kolikaty chce z rady vypsat, program nasledne vypocita a vypise tento prvek. POrogram by nemel neustale pocitat znovu a znovu veskere prvky v rade, pokud uzivatel zada opakovane nekolik vstupu, program by mel dopocitat jen takove prvky, ktere do toho zvoleneho indexu uzivatelem chybi.

## Postup reseni
Fibonacci ma 2 zname hodnoty na prvnich 2 prvcich - 1 a 1. Z techto hodnot se pak vypocitavaji zbyle hodnoty posloupnosti. Tyto hodnoty jsou defaultni a s nimi budeme pracovat. Dale, program by nemel znovu pocitat jiz vypocitane prvky. Pokud bude uzivatel chtit treti prvek v posloupnosti, program v tuto chvili z 1 a 1a vypocita 3. prvek a sice 2. Pokud nasledne uzivatel prvek na 5patem miste posloupnosti, program uz prvni 3 cleny posloupnosti zna a musi tedy vypocitat pouze 2 dalsi cleny.

Veskera prace s Fibonnaciho posloupnosti by se mela dit ve tride `Fibonacci` a prace s uzivatelem, tedy jeho vstup apod. se bude dit v `Program.cs`. 

## Termin odevzdani
Patek 13. 10. 2023 - 20:00
