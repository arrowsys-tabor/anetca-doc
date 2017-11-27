# Váha

-slouží pro měření hmotnosti daného zboží. Hodnotu, která se zobrazuje na LCD následně automaticky vloží do programu, kde vytvoří poměrnou část k jednotkové ceně zboží.

**TLAČÍTKO VÁHY -** slouží k navážení zboží. Hmotnost váženého zboží se po stisknutí tlačítka přepíše z váhy do pokladny.

![](/assets/KALKULAČKA-VÁHA.JPG)

**TLAČÍTKO TÁRY - ** Tára je hmotnost obalu \( misky \) a pod. Na váhu se položí miska a váha zváží táro \( obal\) a uloží do paměti nebo vynuluje.

![](/assets/KALKULAČKA-TÁRY.JPG)

Takže vlastní navažování je již v čisté váze netto.

### Instalace:

1/ Vybalte váhu z originálního balení a pomocí přibaleného kabelu připojte na sériový port. Pokud Vám počítač nedisponuje sériovým portem lze použít **redukci RS232-&gt;USB**. Tu lze sehnat například [**ZDE**](http://i-tec.cz/?t=3&v=31 "RS232 to USB convertor") \(s uvedeným modelem pracovala váha v naprostém pořádku\). Na tuto redukci je nutno nainstalovat ovladač z originálního balení.

2/ Po úspěšném připojení váhy je nutno zjistit COM port, na kterém je váha připojena. Přejděte do ovládacích panelů systému Windows, zvolte položku **SYSTÉM -&gt; SPRÁVCE ZAŘÍZENÍ -&gt; porty COM a LPT**, kde naleznete **COM port přiřazený k váze**.

![](/assets/Vaha-spravce-zarizeni.JPG)

### **Nastavení v ANetCa:**

1/ Spusťte ANetCa a přejděte do záložky **NASTAVENÍ -&gt; ZAŘÍZENÍ -&gt; PORT VÁHY** - zde vyplňte **zjištěný** **COM PORT** a stiskněte **ULOŽIT**.

![](/assets/NASTAVENI-ZARIZENI-VAHA MODUL.JPG)

2/ Přejděte do záložky **PRODEJ**, stiskněte **NOVÁ ÚČTENKA** a klikněte do kalkulačky na symbol **VÁHY. **Navážená hodnota z LCD se Vám přenese do kalkulačky.

![](/assets/PRODEJ-VAHA4.jpg)

## Vážení - položkový systém

#### Postup 1:

1. Vytvořte novou účtenku.
2. Pokud Vážíte zboží v misce, kterou nechcete do váženého zboží počítat, dejte misku na váhu a stiskněte tlačítko TÁRY.
3. Zboží, které potřebujete navážit dejte na váhu.
4. Označte vážené zboží a stiskněte tlačítko váhy na kalkulačce. \(vážená hodnota se přepíše do pole kalkulačky\)
5. Stiskněte tlačítko PŘIDAT POLOŽKU.
6. Účtenku uhraďte nebo přidejte další zboží.

\*Postup 1 je nutné použít při **vypnuté** volbě v **NASTAVENÍ-&gt;PROSTŘEDÍ-&gt;PŘIDAT ZBOŽÍ NA ÚČTENKU STISKNUTÍM TLAČÍTKA**.

#### Postup 2:

1. Vytvořte novou účtenku.
2. Pokud Vážíte zboží v misce, kterou nechcete do váženého zboží počítat, dejte misku na váhu a stiskněte tlačítko TÁRY.
3. Zboží, které potřebujete navážit dejte na váhu.
4. Stiskněte tlačítko váhy na kalkulačce a klikněte na dlaždici zboží. \(vážená hodnota se přepíše do pole kalkulačky\)
5. Účtenku uhraďte nebo přidejte další zboží.

\*Postup 2 je nutné použít při **zapnuté** volbě v **NASTAVENÍ-&gt;PROSTŘEDÍ-&gt;PŘIDAT ZBOŽÍ NA ÚČTENKU STISKNUTÍM TLAČÍTKA**.

## **Vážení - kalkulačka**

#### Postup:

1. Vytvořte novou účtenku.
2. Pokud Vážíte zboží v misce, kterou nechcete do váženého zboží počítat, dejte misku na váhu a stiskněte tlačítko TÁRY.
3. Zboží, které potřebujete navážit dejte na váhu a stiskněte symbol váhy.
4. Následně stiskněte na kalkulačce tlačítko správné sazby daně. \(21%,  15%,  10%, 0%\)
5. Účtenku uhraďte nebo přidejte další zboží.

**\*upozornění: pro správný chod váhy je nutné zadat u zboží cenu za jednotku, aby mohl program s naváženým množstvím správně pracovat.**



