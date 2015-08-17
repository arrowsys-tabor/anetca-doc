Struktura souboru .XLS (Microsoft Excel) pro načtení produktů do ANetCa.

| Název | Zkratka | ID skupiny | DPH % | Cena | Množství | Jednotka | ČK | JKPOV | Prodej. množství |
| -- |
| text | text | int | decimal(2) | decimal(2) | decimal(2) | text | text | text | decimal(4) |
| Párek v rohlíku | Párek v r. | 1 | 15,00 | 35 | 1 | Ks| 0123| 100021 | 1 |


* Zkratka - text na účtenku
* ID skupiny - vytvoří novou skupinu produktů, pokud v ANetCa již zadané ID existuje, přiřadí se produkt ke skupině v ANetCa
* DPH % - sazba DPH, formáty 21; 21.00; 21,00
* Cena - formáty 100; 100.00; 100,00
* Množství - Jednicové množství, formáty 2; 2.00; 2,00
* Jednotka
* ČK - Čárový kód
* JKPOV - Číslo ceníku
* Prodej. množství - počet na účtenku


Datové typy

decimal - číslo v závorce za *decimal* definuje desetinná čísla, podporované formáty: 2; 2.00; 2,00