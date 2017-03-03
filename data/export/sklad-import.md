# Formát importu do modulu skladu/EET maloobchod

Funkce hromadného vložení produktů do modulu skladů musí být ve formátu **Sešit Microsoft Excel 5.0/95 \(\*.xls\)**, xlsx formát a 97-2003 není podporovaný.

| Název | Zkratka | Skupina | DPH % | Prod.Cena | Zůstatek skladu | Jednotka | ČK | Kód zboží | Nákupní cena |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| text | text | int/text | decimal\(2\) | decimal\(2\) | decimal\(4\) | text | text | text | decimal \(2\) |
| Párek | Par | JIDLO | 15,00 | 35 | 1 | Ks | 0123 | 100021 | 10 |

* **Název** - název vkládaného produktu
* Zkratka - text zobrazený účtence, doporučeno je 20 znaků
* Skupina - Název skupiny, ve které se zboží bude nacházet. Skupiny je nutné založit před importem
* **DPH %** - sazba DPH \(0, 10, 15, 21\).
* **Prodejní cena** - prodejní cena produktu.
* **Zůstatek skladu** - Zůstatek skladu, může být 0
* **Jednotka **- jednotka, ke které bude množství přiřazeno
* ČK - Čárový kód
* **Kód zboží** - Číslo ceníku, číslo položky
* **Nákupní cena** - nákupní cena

**\*zvýrazněné sloupce musejí být naplněny, ostatní mohou být prázdné.**

Datové typy:

decimal - číslo v závorce za _decimal_ definuje desetinná místa, podporované formáty: 2; 2,00

**Šablona pro hromadný import:**

**Vzorovou tabulku** si můžete stáhnout ve správném formátu zde [assets/import-vzor-sklad.xls](assets/import-vzor-sklad.xls).

