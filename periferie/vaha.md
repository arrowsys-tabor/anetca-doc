# Váha

-slouží pro měření hmotnosti daného zboží. Hodnotu, která se zobrazuje na LCD následně automaticky vloží do programu, kde vytvoří poměrnou část k jednotkové ceně zboží.

### Instalace:

1/ Vybalte váhu z originálního balení a pomocí přibaleného kabelu připojte na sériový port. Pokud Vám počítač nedisponuje sériovým portem lze použít **redukci RS232-&gt;USB**. Tu lze sehnat například [**ZDE**](http://i-tec.cz/?t=3&v=31 "RS232 to USB convertor") \(s uvedeným modelem pracovala váha v naprostém pořádku\). Na tuto redukci je nutno nainstalovat ovladač z originálního balení.

2/ Po úspěšném připojení váhy je nutno zjistit COM port, na kterém je váha připojena. Přejděte do ovládacích panelů systému Windows, zvolte položku **SYSTÉM -&gt; SPRÁVCE ZAŘÍZENÍ -&gt; porty COM a LPT**, kde naleznete **COM port přiřazený k váze**.

![](/assets/Vaha-spravce-zarizeni.JPG)

### **Nastavení v ANetCa:**

1/ Spusťte ANetCa a přejděte do záložky **NASTAVENÍ -&gt; ZAŘÍZENÍ -&gt; PORT VÁHY** - zde vyplňte **zjištěný** **COM PORT** a stiskněte **ULOŽIT**.

![](/assets/Vaha-nastaveni.jpg)

2/ Přejděte do záložky **PRODEJ**, stiskněte **NOVÁ ÚČTENKA** a klikněte do kolonky **POČET.**

![](/assets/Vaha-PRODEJ.jpg)

3/Stiskněte **symbol váhy**, navážená hodnota z LCD se Vám přenese do pole pro počet a položku i s tímto údajem vložte na účtenku.

4/ Následně stačí jen dokončit všechny kroky pro úspěšné vytištění účtenky.

**\*upozornění: pro správný chod váhy je nutné zadat u zboží cenu za jednotku, aby mohl program s naváženým množstvím správně pracovat.**

