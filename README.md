#   (Eesti) ilutoodete andmebaas 
Annabel Hiiu  
Heili Aavola

Oleme kaks keemia taustaga andmeteaduse tudengit ning otsustasime oma projektis tegeleda ilutoodete ja neis sisalduvate koostisosadega. 

## Valdkond ja selle mõisted

Tegemist on ilutoodete valdkonnaga. Tooted sisaldavad koostisosi, millel kõigil on oma mõju, mis aitavad leevendada erinevaid kaebuseid.
Toode:  
nimetus - toote nimi  
bränd - toote bränd  
koostisosa - tootes sisalduv keemiline ühend  
mõju - koostisosal esinev omadus  
kaebus - kliendilt tulnud kaebus  
tootegrupp kategooria - mis tootega on tegemist (šampoon, palsam, deodorant …)

Tootja- ja brändiriigi eristuse (vt I etapi algne versioon) otsustasime eemaldada, kuna andmebaasi tehes keskendume vaid Eesti brändidele, mille tootmine toimub ka Eestis ehk tootjariik ei ole enam oluline. Andmebaasi kasutajal on eelteadmine, et antud andmebaas annab välja vaid kodumaised ilutooted (st Eestis valmistatud). 

Valdkonna probleem ja kitsaskohad 

Müügil olevad ilutooted (šampoonid, palsamid, deodorandid …) sisaldavad palju erinevaid koostisosi (kemikaale), mis on erineva mõjuga. Kõikide koostisosade mõju ja sobilikkuse analüüsiks ei ole aga tavainimestel aega ja teadmisi. Selleks otsustasime teha andmebaasi, kus on kirjas tooted koos koostisosadega ja nende koostisosade mõjudega. Tegelikult eksisteerib veebilehekülgi (skincarisma.com) ja äppe (Think Dirty), mis aitavad inimesel analüüsida koostisosade mõju, kuid nende suureks puuduseks on see, et nendes leidub vähe Eesti brändide tooteid. Sellepärast otsustasime keskenduda meie andmebaasis just Eesti ilutoodetele, mis aitab tarbijatel teha teadlikumaid otsuseid. 

Andmebaasi kasutajad, kasutajagrupid, millistele küsimustele need kasutajad andmebaasi abil vastuseid soovivad saada

Andmebaasi kasutavad inimesed, kes saavad analüüsida endale meelepärase toote koostisosade omadusi ja teha saadud teadmiste pealt otsus, kas see toode on nende jaoks õige.

Mõned näited küsimustest, millele saab vastuse andmebaasi kasutades:
Milline deodorant sobib mulle, kui olen imetav ema?
Milline kreem sobib näonaha niisutamiseks?
Soovin, et minu seerumis sisalduksid koostisosadena: Centella Asiatica, Panthenol, Hyaluronic Acid, millised tooted vastavad sellele soovile?
Millised tooted saan võtta lennukile minnes käsipagasisse?


Ärireeglid ning nendest tulenevad seoste aarsused

Ühel tootel on mitu koostisosa. Üks koostisosa võib esineda mitmes tootes. (n:m)
Ühel koostisosal on mitu mõju.  Ühte mõju võib esineda mitmes koostisosas. (n:m)
Ühes kaebuses võib olla kirjas mitu soovitud mõju. Ühte soovitud mõju võib esineda mitmes kaebuses. (n:m)
Ühel tootel on üks bränd. Ühel brändil võib olla mitu toodet. (1:n)
Üks toode võib kuuluda erinevatesse tootegruppidesse (nt geel-toonik kuulub kahte gruppi: geel ja toonik). Ühte tootegruppi võib esineda mitmes tootes. (n:m)
Ühel tootel võib olla pakendeid eri suurustes. Ühte pakendi suurust võib esineda mitmel tootel. (n:m)
