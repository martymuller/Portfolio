# Portfolio
Ako finálny projekt z predmetu Kreatívne programovanie IV som sa rozhodol vytvoriť digitálnu vizitku, ktorú budem používať na eventoch počas networkingu prostredníctvom QR kódov.

S touto formou link-vizitky som už mal skúsenosti vďaka nástroju LinkTree – „Link in Bio“ platforme, kde si používatelia môžu uložiť rôzne odkazy na jednom mieste pre jednoduché zdieľanie. LinkTree má však svoje obmedzenia, predovšetkým vizuálne. Používatelia si síce môžu vybrať z rôznych farebných motívov, no všetky sú postavené na rovnakom šablónovom základe.

Preto som sa rozhodol vytvoriť vlastnú, vylepšenú verziu, ktorá by nielen ukázala viac mojej osobnosti, ale bola aj interaktívna a zábavná. Dôležité pre mňa bolo aj to, aby bola optimalizovaná pre mobilné zariadenia, keďže práve na nich si ľudia najčastejšie prezerajú prácu počas networkingu.

Môj pôvodný LinkTree:

![image](https://github.com/user-attachments/assets/d54f174b-2223-4e54-9938-bd56cd027d58) 


# Inšpirácia
![httpsmartymuller github ioPortfolio](https://github.com/user-attachments/assets/a9b1f6f9-71d7-49d6-b660-c606032204b8)

Vedel som, že po vizuálnej stránke sa chcem zamerať na čisté a jednoduché farby a tvary. Hlavnou funkciou vizitky je presmerovať návštevníkov a možno ich aj trochu potešiť – nie však natoľko, aby ich to rozptýlilo a zabudli, prečo sa na vizitku vôbec pozerajú.

Preto som sa prioritne zameral na funkčnosť a jasný branding, v kombinácii s výraznými farbami a odkazom na moju tvorbu prostredníctvom sprite animácie MACA z mojej videohry.

# Proces
V prvej scéne som chcel komunikovať, kto som – moje meno, krátky opis seba a to, čomu sa venujem.

V druhom svete, Blob svete, som chcel odkazy hravo odprezentovať v „bublinách“, resp. bloboch.
Popritom sa typografia môjho mena rozpadne na vrch týchto telies, s ktorými sa dá ďalej interagovať.

![IMG_1343](https://github.com/user-attachments/assets/b10c6c84-d433-44b9-8792-d41faa49b470)

Pomocou knižnice Matter.js sú na bloby v scéne aplikované sily tak, aby s nimi používateľ mohol voľne hádzať, a písmená aj ostatné bloby na to prirodzene reagovali. Pri ťahaní týchto blobov sa zároveň mení farebná schéma scény.
Ďalšou možnosťou interakcie je pridávanie mini-blobov do prostredia – stačí potiahnuť prstom alebo kurzorom po prázdnom pozadí.

Pridal som tiež tlačidlo „REFRESH“ v podobe MACOvej hlavy v ľavom hornom rohu, ktoré resetuje blob svet do pôvodného stavu a opäť zobrazí intro.

Pri písaní kódu mi asistoval ChatGPT, najmä pri optimalizácii pre mobilné zariadenia, keďže funkcie ako mousePressed a mouseDragged nefungujú identicky na všetkých dotykových obrazovkách. Táto pomoc mi umožnila zabezpečiť plynulé ovládanie aj na telefónoch a tabletoch.

# Digitálna vizitka
Vo finále vznikla digitálna link-vizitka, ktorá funguje spoľahlivo na PC, notebookoch aj mobilných zariadeniach.
Kód som naformátoval tak, aby bolo v budúcnosti jednoduché pridávať nové odkazy alebo funkcie – všetko je prehľadne usporiadané a ľahko dohľadateľné.

Najviac ma na tejto práci teší, že som si vytvoril nástroj, ktorý reálne využijem – a zároveň sa môžem pochváliť, že som si ho vytvoril sám.
![httpsmartymuller github ioPortfolio (1)](https://github.com/user-attachments/assets/4b7ded2b-42f6-4c57-9c29-83b20144aa75)
![image](https://github.com/user-attachments/assets/e4defe07-4397-4b9d-8889-53024aeae875)





