# ZBOŽÍ

pokud chcete používat dlaždice/položky na hlavní obrazovce **"PRODEJ"** je nutné v první řadě založit i nové ZBOŽÍ.![](/assets/Zbozí.PNG)

### Založení nového zboží

1. Přejděte do záložky **"ZBOŽÍ"**
2. Stiskněte tlačítko **"NOVÝ"**
3. Vyplňte povinná pole "**NÁZEV, CENU, POČET/JEDNOTKA, ČASTÉ MNOŽSTVÍ, DPH, SKUPINU"**
4. stiskněte **"PŘIDAT"**![](/assets/Nova polozka.PNG)

### Smazání karty zboží

1. označte v levé polovině obrazovky kartu zboží, kterou potřebujete smazat
2. stiskněte symbol křížku v levém dolním rohu 

\*pokud je již zboží zahrnuto v tržbách, což znamená, že je již použito na účtence, nelze jej smazat.

### Hledání zboží

-do kolonky **"HLEDAT"** vypište daný řetězec pro hledání. Následně Vám bude vyfiltrováno vše, co obsahuje zadaný řetězec nebo jeho část

### Nastavení priority

-vedle kolonky pro název je také možnost nastavit prioritu zobrazovaní zboží. Pokud je nastavena vyšší priorita, bude se **"ZBOŽÍ" **zobrazovat v záložce **"PRODEJ"** na prvních místech.

\*tímto nastavením lze volit, které zboží se bude zobrazovat jako první. Většinou se nastavuje na nejvíce prodávanou položku.

### Slevová položka

-pro vytvoření zboží, pomocí kterého budete vytvářet v pokladně slevy je nutné dodržet pár pravidel.

1. Vytvořte zboží, které se bude jmenovat například **"Sleva 20%"**
2. Vyplňte cenu **"1"**
3. Do kolonky časté množství vyplňte hodnotu **"-0,2"**, což označuje **slevu 20%**. Potvrďte pomocí zeleného tlačítka **"+"**
4. Kód zboží musí mít vyplněnou hodnotu **"999999"**
5. Uložte

Takto vytvořené zboží následně použijete jako slevovou položku tak, že jej vložíte na účtenku s vyplněnou částkou, kterou má zboží jež potřebujete slevit. Program již autoamaticky spočítá slevu a vloží ji na účtenku jako samostatnou slevovou položku.

**Příklad:**

Položka na účtence má cenu 100Kč

Přidám slevovou položku **20%** a v sekci PRODEJ vložím do pole pro počet v horní částí obrazovky částku "100"

Stisknu tlačítko **"PŘIDAT POLOŽKU"**  a následně se mi vloží na účtenku položka s hodnotou **"-20"**, kde celková hodnota účtenky se poníží o **"20"**.

### Korunová položka

-používá se především jako náhrada variabilní ceny, která díky cenovým hladinám nemůže být v pokladně ANetCa realizována. Touto položkou a správným postupem lze docílit ceny, kterou požadujete, bez nutnosti mít založeno několik položek s pevně danou cenou.

1. Vytvořte zboží, které má všechny důležité náležitosti jako je **"Název, Cena, Množství, Časté množství, DPH, a Skupina"**.
2. Do kolonky kód zboží vyplňte **"999999".**
3. Uložte.

Nyní se chová takto založená položka jako položka s variabilní cenou. Přejděte do záložky **"PRODEJ"**, vytvořte novou účtenku, označte tuto položku a do kolonky **"POČET"** vyplňte požadovanou cenu. Stiskněte tlačítko **"PŘIDAT POLOŽKU"**. Následně se vloží místo počtu kusů na účtenku pouze požadovaná cena s počtem kusů "1"

### Vysvětlení jednotlivých pojmů:

**Název - **pole pro název zboží. Tento název se zobrazuje následně v záložce **"PRODEJ"** jako název zboží a tiskne se na účtence.

**Cena - **cena zboží. V základu je nutné zvolit jakou cenovou hladinu nastavujete pomocí roletky v záložce **"PRODEJ". **Tato cena se zobrazuje na účtence.

**Počet/Jednotka - **Počet označuje počet prodávaných kusů, jednotka pak slouží jako textové pole, do kterého lze zapsat jakýkoli text. **Nejčastěji ks, kč, noc** nebo jiná zkratka pro jednotku. Tato zkratka se zobrazuje na účtence u zboží.

**Časté množství - **používá se především pro určení často prodávaného množství.

 \*\*Příklad: Zákazník objedná litr 0,2l kofoly a pokud bude vyplněno časté množství 0,2, přidá se na účtenku pouze poměrná část výchozí jednotky. Pomocí tlačítka\*\* "+" \*\*přidáte časté množství. Pomocí křížku pak následně lze po označení odstranit.

**\***pro použití častého množství je nutné mít nastaveno cenu za jednotku\(litr, kus\), ze které se následně počítá poměrná část ceny.

**Tisk na objednávku - **toto pole slouží pro zjednodušení práce obsluhy. Při zatržení **"TISK NA OBJEDNÁVKU"** a vložení takového produktu na účtenku, lze vytisknout toto zboží na druhou tiskárnu. Používá se hodně v restauraci, kdy se v kuchyni vytiskne číslo objednávky a rozpis jídel, která se mají uvařit. Obsluha tak nemusí psát tyto položky ručně a nést zvlášť do kuchyně.

**DPH - **daň z přidané hodnoty daného zboží

**Skupina - **skupina, ve které se zboží nachází.Je nutné, aby každé zboží bylo ve skupině.

**\***skupiny lze vytvářet v záložce **"NASTAVENÍ-&gt;DPH, SKUPINY, CENY"**

**Text na účtence - **název zboží zobrazovaný na účtence.

**\***tuto kolonku není nutné vyplňovat

**Kód zboží -** používá se především pokud vedete sklady, kde se podle kódu zboží dá hledat dané produkty i záložce **"PRODEJ -&gt; HLEDAT"**.

**Čárový kód - **pokud je čárový kód vyplněn, lze následně vkládat zboží na účtenku pomocí čtečky čárového kódu.

**PLU - **je uživatelsky měnitelný kód. Slouží pro zjednodušené vkládání pomocí kalkulačky. Pomocí PLU lze hledat zboží v obsahu na záložce **"PRODEJ"**

**Pověřující DIČ - **neboli prodej v zastoupení. Pokud prodáváte zboží na jiný subjekt, tak do tohoto pole vyplňte DIČ subjektu. Na účtence bude zaznamenáno toto DIČ a platba odejde do EET také pod tímto DIČ.

