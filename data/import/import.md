## Struktura sloupců souboru .XLS \(Microsoft Excel 97-2003\) pro nahrání produktů do ANetCa.

**.XLSX formát není podporovaný**

| Název | Zkratka | ID skupiny | DPH % | Cena | Množství | Jednotka | ČK | Kód zboží | Prodej. množství | Kuchyně | PLU kód |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| text | text\(50\) | int | decimal\(2\) | decimal\(2\) | decimal\(2\) | text | text | text | decimal\(4\) | bit | text |
| Párek v rohlíku | Pár. v rohl. | 1 | 15,00 | 35 | 1 | Ks | 0123 | 1001 | 1 | 1 | 111 |
| Párek | Párek | 1 | 15,00 | 35 | 1 | Ks | 1234 | 1002 | 1 | 1 | 112 |

* **Název** - název produktu
* **Zkratka** - text na účtenku, maximum je 50 znaku
* **ID skupiny** - vytvoří novou skupinu importovaných produktů. Pokud v ANetCa již zadané ID existuje, přiřadí se produkt k vybrané skupině.
* **DPH %** - sazba DPH. Pro přenesenou daň vyplňte příslušný kód např. P-04. Bez DPH vyplňte 0.
* **Cena** - prodejní cena produktu, bude přiřazena k výchozí cenové kategorii v ANetCa
* **Množství** - Jednotkové množství, výchozí 1
* **Jednotka**
* ČK - Čárový kód
* **Kód zboží** - Číslo ceníku
* **Prodej. množství** - počet na účtenku, výchozí 1
* **Kuchyně** - 1 - položka patří do kuchyně
* **PLU** - kód pro vyhledávání

**Zvýrazněné sloupce musejí být naplněny, ostatní mohou být prázdné.**

DPH % - pro přenesenou daň vyplňte P0

Kód zboží - Pokud v pokladně existuje položka s kódem zboží importované položky, aktualizuje se cena dané položky

Datové typy

decimal - číslo v závorce za _decimal_ definuje desetinná místa, podporované formáty: 2; 2.00; 2,00

### 

### Nahrání Importu do pokladny ANetCa

1. Přejděte do záložky **"NASTAVENÍ-&gt;DPH, SKUPINY, CENY"** a stiskněte tlačítko **"NAČÍST PRODUKTY"**
2. Vyberte, kde se soubor pro import nachází a načtěte ho.
3. Vyčkejte moment, dokud program nezahlásí **"POLOŽKY BYLY ÚSPĚŠNĚ IMPORTOVÁNY"**.

![](/assets/NASTAVENI-IMPORT.PNG)

