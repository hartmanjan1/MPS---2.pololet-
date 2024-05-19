# MPS---2.pololetí-

Dobrý den, posílám rozpracovaný projekt z MPS na 2.pololetí. 
Bohužel jsem nemohl pokračovat v rozpracovaném projektu z 1.pololetí jelikož jsem v projektu viděl spoustu nejasností v aplikaci Unity a rpzhodl jsem se že začnu znovu a lépe. Tudíž jsem již měl o mnoho více zkušeností a mohl jsem pracovat více samostatně, jistěji a rychleji.
Hru jsem znovu tvořil v Unity a programoval ve Visual Studio Code. S programováním ve visual studiu mám už mnoho zkušeností ze školy z 2. ročníku takže zákládní kódy pro mě nebyly problém.
Inspiraci a všechny soubory jsem si stáhl z této série videí: https://youtube.com/playlist?list=PLGmYIROty-5YPWeXeVnQvR9KbMIrL5cM-&si=r225FQSHC2LrRHTR po zhlédnutí této série se mi videa zdály velmi pěkně zpracované a srozumitelné.

Po založení projektu v Unity jsem začal tím že jsem si do Unity přetáhnul všechny soubory které jsem stáhnul pod výše uvedeným videem. Soubory jsem si přesunul do složky Sprites abych s nimi následně mohl pracovat. Jako první jsem si přetáhl na pracovní plochu pozadí a dal jsem mu funkci aby bylo vždy nastaveno jako poslední vrstva. Jako další soubor jsem si přetáhl soubor hráče, který má strukturu kosmonauta a plošiny na které může skákat tak aby se dostal z bodu A do bodu B na všechny plošiny i na hráče jsem přidal komponent s názvem Collider 2D na plošiny jsem dal tvar polygonu a na hráče tvar kapsule, aby měla jak plošina tak hráč nejlepší Collider "aby to na ně co nejlépe pasovalo". Tento komponent dělá to že když na něj hráč stoupne tak se nepropadne ale zůstane na plošině. Na hráče jsem pak musel přidat component s názvem Rigidbody 2D což udělá to že na hráče bude působit gravitace a bude mít tzv. fyzické tělo.![1,](https://github.com/hartmanjan1/MPS---2.pololet-/assets/156115281/3dc3617b-b160-4f45-ac87-a4e7089bfb3a)
 ![Snímek obrazovky 2024-05-19 201556](https://github.com/hartmanjan1/MPS---2.pololet-/assets/156115281/0cdc792b-c73e-488d-817b-d13e77416973)


Ještě předtím než jsem začal psát příkazi a přidávat další komponenty, tak jsem si Level na designoval tak aby hra vypadala lépe a dalo se s ní lépe pracovat. Na všechny objekty na které hráč bude v průběhu hry skákat jsem přidal znovu komponent collider 2D. Následně jsem si spojil objekty které jsou na jedné plošině do takové mini složky v Unity, tak aby se mi s tím lépe pracovalo. Těď jsem měl hru připravenou a mohl jsem se pustit do pohybu hráče.

![Snímek obrazovky 2024-05-19 204023](https://github.com/hartmanjan1/MPS---2.pololet-/assets/156115281/22728ded-0d93-429c-b850-f53e7e32350a)


Založil jsem si další složku jménem Scény kde jsem si vypsal všechny levely tak aby se mi s nimi lépe pracovalo.
Následně jsem se přesunul na pohyb hráče který jsem programoval celý ve Visual studiu, výstřižek z Visual Studia vám pošlu celý na konci projektu. Následně jsem jen uppravil v Unity rychlost hráče. Dále jsem přidal kód pro skok hráče. Vše jsem si nastavil tak abych pohyb mohl ovládat šipkami a skok ovládat mezerníkem.
Následně jsem si vytvořil složku Fyzické materiály kam jsem si přímo z Unity přetáhl materiál Bouncy a Slippery což v překladu do češtiny znamená skákání a klouzání, udělal jsem to proto jelikož chci aby hráč ve hře mohl posouvat určité předměty.
Pak jsem se přesunul na kameru. Potřeboval jsem aby kamera následovala hráče, takže jsem se přesunul do Visual Studia a pokusil jsem se to naprogramovat tam. Zde se přiznám že byl asi ten největší zádrhel jelikož jsem si delší dobu nevěděl rady ale následně i s pomocí videa jsem problém vyřešil. 
Níže přiložím výstřižek z Visual studia a krátké video jak hra funguje.

![3](https://github.com/hartmanjan1/MPS---2.pololet-/assets/156115281/7bf6ee01-6ba6-49d5-893b-29a965c03198)


![4](https://github.com/hartmanjan1/MPS---2.pololet-/assets/156115281/f3cbbacd-e5e3-4b41-aa4b-e3138e2d5b76)

Video ze hry Vám pošlu na Teams.
Omlouvám se jestli je tento popis moc stručný pokusím se ho upravit a až bude projekt hotový tak poslat v lepší podobě. Hotový projekt Vám pošlu během příštích dnů již teď pracuji na animacích hráče na dalšim levelu a na respawnu hráče.
