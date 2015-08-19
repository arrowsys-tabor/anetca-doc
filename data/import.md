
## Struktura sloupců souboru .XLS (Microsoft Excel 97-2003) pro nahrání produktů do ANetCa.



**.XLSX formát není podporovaný**

| Název | Zkratka | ID skupiny | DPH % | Cena | Množství | Jednotka | ČK | JKPOV | Prodej. množství |
| -- |
| text | text | int | decimal(2) | decimal(2) | decimal(2) | text | text | text | decimal(4) |
| Párek v rohlíku | Pár. v r. | 1 | 15,00 | 35 | 1 | Ks| 0123| 100021 | 1 |
| Párek | parek |  | 15,00 | 35 | 1 | Ks| | | | |

* **Název** - název produktu
* **Zkratka** - text na účtenku
* ID skupiny - vytvoří novou skupinu importovaných produktů. Pokud v ANetCa již zadané ID existuje, přiřadí se produkt k vybrané skupině.
* **DPH %** - sazba DPH
* **Cena** - prodejní cena produktu, bude přiřazena k výchozí cenové kategorii v ANetCa
* Množství - Jednicové množství, výchozí 1
* **Jednotka**
* ČK - Čárový kód
* JKPOV - Číslo ceníku
* Prodej. množství - počet na účtenku, výchozí 1

**Zvýrazněné sloupce musejí být naplněny, ostatní mohou být prázdné.**

Datové typy

decimal - číslo v závorce za *decimal* definuje desetinná čísla, podporované formáty: 2; 2.00; 2,00