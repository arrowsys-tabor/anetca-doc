# !!! Ve výstavbě !!! - právě se upravuje

# 

# Zákaznický display LD-240

-zákaznický display slouží k zobrazení důležitých informací pro zákazníka jako je například částka, kterou má zaplatit, informace o firmě či pouze uvítací oznámení. Tyto informace lze uživatelsky měnit.

### Instalace:

1/ Z přiloženého CD nainstalujte ovladač pro rozhraní USB-to-SERIAL **Win\_Driver\_Prolific\_3\_2\_0\_0.exe** případně stáhněte ovladač přímo z [webu](http://www.w9lrt.com/default/assets/File/baofengprolificvista.zip "WEBU") výrobce.

2/ Jakmile dokončíte instalaci restartujte počítač.

3/ Po úspěšném naběhnutí operačního systému spusťte z instalačního CD utilitu **VFDSetupAP\_V3.0 **která slouží k nastavení uvítací obrazovky zákaznického displaye

4/ nyní přejděte do **ovládacích panelů** **systému Windows** **-&gt; SYSTÉM -&gt; SPRÁVCE ZAŘÍZENÍ **a vyhledejte položku s názvem Porty COM a LPT a vyberte položku **Prolific USB-to-serial Comm Port \(COMx\)**, kdy **"x"** zastupuje číslo portu COM, na který je zákaznický display připojen.

![](/assets/ZD-spravce-zarizeni.JPG)

5/ Pokud by se Vám u **Prolific USB-to-serial Comm Port \(COMx\) **zobrazoval trojúhelník s vykřičníkem je nutné postupovat dle návodu v tomto bodu.

![](/assets/ZD-aktualizace-ovladace.jpg)



6/ Spusťte **VFDSetupAP\_V3.0 **a** **nastavte COM port, který jste zjistili ve správci zařízení a zadejte jej do kolonky **COM PORT SELECT**

7/ V záložce **Welcome msg **vyplňte úvodní text, který se má zobrazovat na uvítací obrazovce displaye a stiskněte **DOWNLOAD SETTINGS TO VFD**

8/ Po chvíli Vám vyskočí okno s hlášením abyste restartovali Display. To potvrďte a následně odpojte a připojte USB k počítači.

