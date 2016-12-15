# Verze a změny

### 1.3.0.0

* Širší scrollbar
* PIN storna - pokud je nastaven, je vyžadován pro storno, mazání položek, přidávání minus položek na účtenku
* Provozovna z Nastavení je v záhlaví programu
* Po dvojkliku na VŠE se zobrazí všechny skupiny
* Řazení skupin
* Sčítání množství na účtenku
* Přehlednější seznam účtenek
* Podpora váhy
* Podpora zákaznického displeje

Opravy chyb
* Vystavil bude kdo uhradil účtenku, místo kdo ji vytvořil
* Kopie účtenky se tiskla na výchozí tiskárnu
* Zvětšení tlačítka pro tisk objednávky

### 1.2.0.0

* Platba fakturou \(s platbou na Účet - není odesílána do EET\)
* Před uzavřením kasy, upozornění na neodeslané účtenky
* Rozdělení účtenek podle Pověřujícího DIČ
  * Pokud účtenka obsahuje jednu nebo více položek od různých Pověřujících DIČ, vytvoří se z této účtenky další, které jsou tištěny samostatně s vlastními FIK kódy.
  * 1. Režim PP: Pokud je v nastavení definované DIČ Pověřujícího, všechny účtenky budou vystaveny s tímto DIČ

  * 1. Režim PP: Pokud DIČ Pověřujícího není vyplněné a položky mají nastaveno pověřujícího, při úhradě se rozdělí účtenky samostatně.    


* Produkty s PLU 90900, 90910, 90915, 90921 nemohou být smazány
* Zablokováno numerické vkládání hodnot do kalkulačkového labelu
* Zálohování na USB
* Název firmy v horním panelu 
* Tisk názvu položky na nový řádek \(pouze BT\)

Opravy chyb

* Úpravy pro 58mm tisk
* Oprava přepínání číselných řad
* Zakázání záporných odsazení 
* Pokud nebyla vyplněna tiskárna, program se nespustil
* "Nejsem plátce DPH" na účtenku
* Rekapitulace DPH se nestiskne pro netplátce DPH
* 80mm Kč odskakovalo na další řádek
* Pokud účtenka nemá stůl, "Stůl" se nestikne
* Při odstranění produktů se nesmažou produkty s PLU 90900 90910 90915 90921
* Chyba kdy nešel program spustit kvůli bankovnímu terminálu byla odstraněna

### 1.1.0.0

* Podpora produkčního režimu EET

### 1.0.0.0

* Oprava aktualizátoru



