# 18/04/2024
Nu så har jag fixat så att hoppet funkar ordentligt och så att alla animeringarna funkar när dom ska, har även lagt till så att spriten vänder sig när den borde och när den hoppar så har jag valt att andvända samma animation för när den åker både uppåt och nedåt för att inte behöva ha två olika animationer för båda, vilket optimserar antalet bildfiler men lägger till ungefär 4 raeder kod. Jag funderar på att göra så man har ett hopp som desto längre man håller inne mellanslag desto längre hoppar man, istället för dubbelhoppet, då jag antagligen behöver en global variabel som går upp för varje 'tick' man håller inne mellanslag som sen blir 0 igen när man har hoppat.

# 15/4/2024
Vscode ville inte sammarbeta med godot av någon andledning så därför så funkade inte commiten förra veckan så fixade det och var lite för trött från högskoleprovet för att göra något vettigt i godot. Så gjorde bara en liten plan på vad jag ville göra längre fram i projektet, kollade upp lite hur man gjorde globala variabler vilket jag behöver för att kunna till exempel dubbelhoppa. 

# 11/94/2024
Märkte att animationerna var konstiga och märkte att jag hade glömt att specifiera vart den skulle ta alla bildfilerna ifrån så fick fixa så den tog från rätt bibliotek, vilket gjorde att jag behöde göra om typ alla animationer och felsöka en stund. Men jag löste det iallafall.

# 08/04/2024
Jätteseg idag, har fått en svag hjärnskakning så blev inte mycket gjort men jag fixade lite grejer med animationerna, så dom funkar, dom ser inte bra ut, men dom funkar, nästa gång borde jag se till så att jag kan aktivera animationerna.

# 25/03/2024
Jag fixade fler animationer och gjorde så att slimen(spelaren) kunde gå runt, inte så bra men den kan iallafall röra sig och hoppa, jag har dock vältigt mycket problem med animationerna och är alderles för hungrig för att förstå vad som är fel, jag åt dock nyss lunch så vet inte varför jag är så hungrig.

# 21/03/2024
Jag började fixa min main character sprite med animationer och collision.

# 18/03/2024
Idag så fixade jag så att nodesen faktiskt fungerade och har lärt mig hur man updaterar git ordentligt. Har även lärt mig om bland annat globala variabler i godot. 

# 14/03/2024
Började på en startscen då jag andvänder nodes för att få sprites att comunicera med mitt scrips som i sin tur antingen startar en ny scen eller stänger ned spelet, beroende på vilken knapp man trycker på.




