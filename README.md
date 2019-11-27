Použil som CSS Grid system aj Flexbox, aj keď by som to asi nemal kombinovať. Jednak som to chcel prvý krát naplno vyskúšať na nejakom zadaní, ale podla toho čo som pozeral, podpora je už dosť solídna. Velký projekt by som ale robil s Flex gridom.

Zvolil som custom CSS Grid / Flexbox, pretože som považoval za nevhodné pridávať celý CSS Grid alebo Flexbox pre túto template. Odhadol som, že známe/slávne CSS Frameworks tu nemám linkovať a scriptovať iba na JS TABY...Dúfam že súhlasíte. Samozrejme Bootstrapu, Foundation atd. sa nebránim.

- pre CSS architekturu používam 7-1. Hodil som to aj sem, býva to o dohode čo sa použije...
- snažil som sa čo najviac aplikovať BEM konvenciu.

Progressive enhancement - čo sa týka layoutu cez float  - to sa snažím nepoužívať už vôbec

Som si vedomý, že do _variables môžu ísť aj font-size, font-weight, z-indexy atd. ale verím že to nezaváži.

Font-size boli niektoré s desatinnými meistami - zaokrúhlil som. 
Line-height si väčšinou nastavím na body a ostatné prispôsobím.


LAYOUT:
- V responsive som ratal do 320 px. Ak to ma zmysel aj pre menej, nie je problem.

- šípka pod deadpoolom by asi mala byť cez svg ale tie ešte neovládam.

- text-decoration v kartach som použil po precitani tohto článku https://css-tricks.com/styling-underlines-web/

- dlhšie som rozmýšlal a skúšal spraviť v responsive tie slide switche. Originál som to chcel dať nalavo cez position ale nehodí sa to na stranu...Tak som to spravil ako buttony (Sú tam iba základné štýly ale vedel by som to vypimpovať). Už je to ale dlhšia doba čo ste mi zadanie poslali, takže nejde o to mať dokonalé buttony. Vy ste chceli vidieť nejaké nevšedné riešenie , ale okrem toho že by som to dal na stranu, ma nič nenapadá.

Obrázky:

- na logo som použil Art direction + Density switch - Viem že tam mám 2 krát rovnaký obrázok = ide len o princíp, že väčšinou som zamieňal logo ak neboli iné obrazky na webe
- resolution switching v tejto template podla mňa nemá význam
- produktové obrázky (v JS TABS) majú málo kB a malé rozlíšenie, takže tu som tiež vynechal tieto techniky spracovania obrázkov. Nechal som ich fixne, s ohladom na to že sa to tak robí v mnohych eshopoch - a toto mi príde ako produkty v eshope + logo vo footri je ná uváženie ale myslím že aj to by malo ostať velké. 
