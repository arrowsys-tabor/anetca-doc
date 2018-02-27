# Váha

Slouží pro měření hmotnosti daného zboží. Navážená hodnota je přenesena z váhy do pokladny, kde je následně zpracována a vypočtena správná cena vůči jednotkové ceně váženého zboží. V současné době máme k dispozici váhy značky METTLER TOLEDO, které lze objednat na našem eshopu. Jedná se o modely METTLER TOLEDO ARIVA S a BRITE ADVANCE.

### **TLAČÍTKO VÁHY**

Slouží k navážení zboží. Hmotnost váženého zboží se po stisknutí tlačítka přepíše z váhy do pokladny. Lze kombinovat s tlačítkem TÁRY.

![](/assets/KALKULAČKA-VÁHA.JPG)

### **TLAČÍTKO TÁRY**

TÁRA je hmotnost obalu zboží v obchodním styku, někdy se tímto pojmem označuje i obal jako takový. Takto navážený obal se odečte z celkové hmotnosti, takže vlastní navažování je již v čisté váze netto. Tárování lze využít například pokud máte vlastní misku, ale prodáváte pouze její obsah.

![](/assets/KALKULAČKA-TÁRY.JPG)

### Instalace:

Instalaci a certifikaci váhy provádí technik METTLER TOLEDO.

### Zjištění portu váhy:

1. Po připojení váhy je nutno zjistit COM port, na kterém je váha připojena. Přejděte do ovládacích panelů systému Windows, zvolte položku **SYSTÉM -&gt; SPRÁVCE ZAŘÍZENÍ -&gt; porty COM a LPT**, kde naleznete **COM port přiřazený k váze**.

![](/assets/VAHA-COM PORT2.jpg)

### **Nastavení v ANetCa:**

1/ Spusťte ANetCa a přejděte do záložky **NASTAVENÍ -&gt; ZAŘÍZENÍ -&gt; PORT VÁHY** - zde vyplňte **zjištěný** **COM PORT **a stiskněte **ULOŽIT**.

![](/assets/NASTAVENI-ZARIZENI-PORT VAHY2.jpg)

2/ Přejděte do záložky **PRODEJ**, stiskněte **NOVÁ ÚČTENKA, **položte zboží, které potřebujete navážit a klikněte do kalkulačky na symbol **VÁHY. **Navážená hodnota z LCD se Vám přenese do kalkulačky. Stiskněte tlačítko daného DPH a účtenku odešlete do EET.

![](/assets/PRODEJ-VAHY2.jpg)

## Vážení - položkový systém

#### Postup 1:

1. Vytvořte novou účtenku.
2. Pokud Vážíte zboží v misce, kterou nechcete do váženého zboží počítat, dejte misku na váhu, stiskněte tlačítko TÁRY a vyberte z tabulky uloženou misku.
3. Zboží, které potřebujete navážit dejte na váhu.
4. Označte vážené zboží a stiskněte tlačítko váhy na kalkulačce. \(vážená hodnota se přepíše do pole kalkulačky\)
5. Stiskněte tlačítko PŘIDAT POLOŽKU.
6. Účtenku uhraďte nebo přidejte další zboží, případně postup opakujte.

\*Postup 1 je nutné použít při **vypnuté** volbě v **NASTAVENÍ-&gt;PROSTŘEDÍ-&gt;PŘIDAT ZBOŽÍ NA ÚČTENKU STISKNUTÍM TLAČÍTKA**.

#### Postup 2:

1. Vytvořte novou účtenku.
2. Pokud Vážíte zboží v misce, kterou nechcete do váženého zboží počítat, dejte misku na váhu, stiskněte tlačítko TÁRY a vyberte z tabulky uloženou misku.
3. Zboží, které potřebujete navážit dejte na váhu.
4. Stiskněte tlačítko váhy na kalkulačce a klikněte na dlaždici zboží. \(vážená hodnota se přepíše do pole kalkulačky\)
5. Účtenku uhraďte nebo přidejte další zboží, případně postup opakujte.

\*Postup 2 je nutné použít při **zapnuté** volbě v **NASTAVENÍ-&gt;PROSTŘEDÍ-&gt;PŘIDAT ZBOŽÍ NA ÚČTENKU STISKNUTÍM TLAČÍTKA**.

## **Vážení - kalkulačka**

#### Postup:

1. Vytvořte novou účtenku.
2. Pokud Vážíte zboží v misce, kterou nechcete do váženého zboží počítat, dejte misku na váhu, stiskněte tlačítko TÁRY a vyberte z tabulky uloženou misku.
3. Zboží, které potřebujete navážit dejte na váhu a stiskněte symbol váhy.
4. Následně stiskněte na kalkulačce tlačítko správné sazby daně. \(21%,  15%,  10%, 0%\)
5. Účtenku uhraďte nebo přidejte další zboží, případně postup opakujte.

**\*upozornění: pro správný chod váhy je nutné zadat u zboží cenu za jednotku, aby mohl program s naváženým množstvím správně pracovat.**

