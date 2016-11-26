# Verze a změny

###1.2.0.0
* Platba fakturou (s platbou na Účet - není odesílána do EET)
* Před uzavřením kasy, upozornění na neodeslané účtenky
* Rozdělení účtenek podle Pověřujícího DIČ
 * Pokud účtenka obsahuje jednu nebo více položek od různých Pověřujících DIČ, vytvoří se z této účtenky další, které lze uhradit samostatně.
  * 1. Režim PP: Pokud je v nastavení definované DIČ Pověřujícího, všechny účtenky budou vystaveny s tímto DIČ
  * 2. Režim PP: Pokud DIČ Pověřujícího není vyplněné a položky mají nastaveno pověřujícího, při úhradě se rozdělí účtenky samostatně.	
* Produkty s PLU 90900, 90910, 90915, 90921 nemohou být smazány
* Zablokováno numerické vkládání hodnot do kalkulačkového labelu
* Zálohování na USB
* Název firmy v horním panelu 
* Tisk názvu položky na nový řádek (pouze BT)

Opravy chyb
* úpravy pro 58mm tisk
* Oprava přepínání číselných řad
* Zakázání záporných marginů 
* Pokud nebyla vyplněna tiskárna, program se nenačetl
* Nejsem plátce DPH na účtenku
* 80mm Kč odskakovalo na další řádek
* Stůl se nestikne pokud není vyplněn
* Při odstranění produktů se nesmažou produkty s PLU 90900 90910 90915 90921
* Chyba kdy nešel program spustit kvůli bankovnímu terminálu byla odstraněna

###1.1.0.0
* Podpora produkčního režimu EET

###1.0.0.0
* Oprava aktualizátoru
