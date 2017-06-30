# Zákaznický displej LD-240

Zákaznický displej slouží k zobrazení důležitých informací pro zákazníka. Jako je například částka, kterou má zaplatit, informace o firmě či pouze uvítací oznámení. Tyto informace lze uživatelsky měnit.

### Instalace:

1/ Z přiloženého CD nainstalujte ovladač pro rozhraní USB-to-SERIAL **Win\_Driver\_Prolific\_3\_2\_0\_0.exe** případně stáhněte ovladač přímo z [webu ](http://www.axis-distribution.cz/obchod/action/productdetail/oc/3472304/product/displej-elio-ld-240-usb-cerny.xhtml)výrobce.

2/ Jakmile dokončíte instalaci restartujte počítač.

3/ Po úspěšném naběhnutí operačního systému spusťte z instalačního CD utilitu **VFDSetupAP\_V3.0 **která slouží k nastavení uvítací obrazovky zákaznického displaye

4/ nyní přejděte do **ovládacích panelů** **systému Windows** **-&gt; SYSTÉM -&gt; SPRÁVCE ZAŘÍZENÍ **a vyhledejte položku s názvem **Porty COM a LPT** a vyberte položku **Prolific USB-to-serial Comm Port \(COMx\)**, kdy **"x"** zastupuje číslo portu COM, na který je zákaznický display připojen.

![](/assets/ZD-spravce-zarizeni.JPG)

5/ Pokud by se Vám u **Prolific USB-to-serial Comm Port \(COMx\) **zobrazoval trojúhelník s vykřičníkem je nutné postupovat dle návodu v tomto bodu.

\*postupujte dle přiložených obrázků pro správné nastavení

![](/assets/ZD-aktualizace-ovladace.jpg)

![](/assets/ZD-aktualizace-ovladace-2.jpg)

![](/assets/ZD-aktualizace-ovladace-3.JPG)

![](/assets/ZD-aktualizace-ovladace-4.jpg)

6/ Spusťte **VFDSetupAP\_V3.0 **a** **nastavte COM port, který jste zjistili ve správci zařízení a zadejte jej do kolonky **COM PORT SELECT**

![](/assets/ZD-program-1.jpg)

7/ V záložce **Welcome msg **vyplňte úvodní text, který se má zobrazovat na uvítací obrazovce displaye a stiskněte **DOWNLOAD SETTINGS TO VFD**

![](/assets/ZD-program-2.jpg)

-pro nastavení textu zobrazeného v kolonkách je nutné do každého pole vyplnit patřičný znak. Pokud se jedná o mezeru je nutno vyplnit zvlášť i ji.

8/ Po chvíli Vám vyskočí okno s hlášením, abyste restartovali Display. To potvrďte a následně odpojte a připojte zákaznický display k počítači.

# Nastavení v ANetCa

1/ přejděte do záložky **NASTAVENÍ -&gt; KONFIGURACE.**

2/ Zde je možno konfigurovat** port ZD**\(zákaznického displaye\). **Vyplňte COM port**, který byl zjištěn ve správci zařízení a vyplňte jej.

3/ Po stisku na tlačítko **NASTAVENÍ **lze display dodatečně konfigurovat.

![](/assets/ZD-anetca-nastaveni.jpg)

