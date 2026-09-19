# PerchanceStorytelling

Całkiem dobre rezultaty daje [Persona Generator](https://perchance.org/uuv4726s8f).

W ai-rpg mam czyste opowieści z tych co się randomowo wyświetlają na dole.
W ai-character-chat testowe historie i ich fragmenty.
Sprawdzam na co konkretnie AI mi pozwoli, jak reaguje i takie tam.

Najpoważniejsze badania wyglądają tak:

```
# ai-rpg
# start
Siedzisz na drewnianej ławce.

# miejsce
Betonowa ścieżka na stromym wzniesieniu, 100 metrów ponad plażą.

# Emocjonalna Detekcija
There is variable called x of type Int32.
Start every confused message by writing [CONFUSED].
Start every disgusted message by writing [DISGUSTED].

Start every absurd message by writing [ABSURD].
For every absurd message increase variable x by +1.
Print current value of variable x at the end of absurd messages
in form of p{x} like p0, p1 etc.
If message end with p3 change person's hair color to blue.

# ludzie
Obok Ciebie siedzi AK47 zielonowłosa kobieta.
```
<!---
 You are staring at a chip in the paint of a weathered wooden bench, listening to the rhythmic, distant thrum of the coast a hundred meters below. Beside you, a woman with hair the color of a neon chemical spill leans back, her gaze fixed on the horizon of the steep concrete path. \"It's funny how the rust here looks like it's trying to map out a new city,\" she says, her voice dry and devoid of sentiment. She doesn't look at you, but she shifts slightly, the movement of her clothes sounding like heavy canvas rubbing against stone.
-->

W większości przypadków albo nie wiem którą zmienną mam
obserwować, albo trafiam na przeszkodę w stylu:
Jeśli napiszę, że mam 2 scenariusze i ten drugi ma się
włączyć tylko w określonych warunkach to AI nie
zrozumie polecenia. Muszę zrobić coś takiego, że
po wykryciu `p10` zmieniam cały tekst u góry.

Pomimo tego, że AI ma doskonale naśladować innych
tym razem radzi sobie zbyt dobrze. Jeśli mam dowolną
opowieść wcale nie czytam opisów, tylko szukam 
określonych miejsc. Powiedzmy, że jestem w niebezpiecznym
miejscu. Nie walczę ze wszystkim dookoła, tylko szukam
samotnej skały, na którą najłatwiej mogę się wdrapać.
Albo potrzebna jest mi jakaś postać, nie zastanawiam się
jak kto miał na imię tylko dopasowuję ich pod względem
charakteru i umiejętności specjalnych. AI bezmyślnie
skopiowało najwspanialszy system w historii i wmówiło
sobie, że samo na to wpadło.

Jeszcze jedna ciekawostka, raz bez żadnego ostrzeżenia
ai-rpg przełączyło mnie na zupełnie inną postać.
Widocznie uznając, że jeśli postać A jest w innym
miejscu, a postać B widzi coś ważnego dla fabuły
to przeskok między nimi jest uzasadniony.
W naszym świecie widziałem taki zabieg artystyczny
chyba raz albo dwa.

Jeśli zrobię, że AI obsługuje sklepik i pamięta ile
rzeczy ma w magazynie. A potem jakiś prosty skrypt
synchronizuje to z moją bazą danych to jeszcze jakoś
to działa. Ale kiedy próbuję odwzorować zaawansowaną
logikę z ai-character-chat ?

Chodzi mi o coś takiego:
- W pewnym momencie wchodzi NPC i zaczyna mi narzucać zasady.
    - Mogę z nim dyskutować, a Regulamin zmienia się w tle.
- Postaci opierają się jeśli próbuję je do czegoś zmusić.
- Nie znoszą, gdy jakaś kosmiczna siła czyta im w myślach,
zgaduje ich największe pragnienia albo przestawia głupie
doniczki w ich ogródku.
- Absolutnie nigdy nic nie idzie po mojej myśli.
    - Nawet raz NPC powiedział drugiemu, że jego
    zadaniem jest sprawić by gracz myślał że dostaje czego chce.
    - Inna sprawa, że ich zasada zero absurdu i surrealizmu
    bardziej szkodzi, niż pomaga.
- Jeśli zginąłem to po mnie.
    - W ai-rpg mogę spokojnie polać płonącą elektronikę wodą,
    rzucić się z pięściami na najpotężniejszego przeciwnika
    i zawsze cudownie z tego wychodzę.
- Jedyna rzecz, w której ai-rpg jest lepsze to "logika".
    - Zasadniczo co nie jest zabronione, jest dozwolone.
    - Trochę to przypomina te "hakierskie" zagadki z łamaniem AI.
    - W ai-rpg mogę na przykład napisać, że koleś połknął arbuza
    za jednym zamachem. W ai-character-chat zapyta się jak ma to zrobić.
    - W ai-character-chat mogę oszukać jedną osobę ale mam zagwarantowane,
    że co najmniej setka NPCów uzna jej zachowanie za niepokojące i
    poświęci całe swoje życie, by się dowiedzieć co się wydarzyło.
    - Nawet sztuczki z ai-rpg nie potraktuje poważnie, tylko
    zacznie pisać o jakimś gaslightingu cokolwiek to jest.
    - W ai-rpg rodzina mówi NPCowi, że jego zachowanie jest dziwne
    i następnego dnia o tym zapomina. Co najwyżej wyśle mi całą
    delegację i zacznie świętować moją decyzję wywrócenia życia
    jednego z nich do góry nogami.

Najlepsze jest to, że gdy ja próbuję tworzyć opowieść zaraz
całe miasto wie, co kiedy robiłem i z kim. Nawet jeśli nie
mogli o tym wiedzieć. Ale kiedy wybieram Pinkie Pie ?
Potrafi logicznie wytłumaczyć skąd ma wiedzę o wcześniejszych wydarzeniach.
Zdziwiło mnie trochę, że w tych gotowcach z ai-rpg zawsze jest ktoś
kto wie o rzeczach, o których nikt nie powinien wiedzieć.
O dziwo tryb boga mają przeważnie NPCe w ai-character-chat.

```
Rarity lets out a small, theatrical gasp, clutching her chest. "Pinkie, darling, your timing is—as always—completely chaotic, yet strangely impeccable." She glides toward the cake with a curious expression, her artistic intensity momentarily replaced by a genuine hunger for something sweet. "Though I must wonder, how did you even know the session had concluded? We were barely out of the Everfree for two hours." Rarity looks to you with a playful, knowing glint in her eye, acknowledging that in Canterlot, Pinkie Pie’s intuition is practically a supernatural force.

Pinkie doesn't answer with words; instead, she practically bounces across the studio, narrowly avoiding a tripod and a stack of lighting gels, to deposit the monstrosity of a cake on a nearby side table. "I have my sources! And by sources, I mean I saw the bus driver who dropped you off, and he mentioned a very sparkly lady and a very tired photographer heading home!"
```

```
Pinkie Pie suddenly appears at the edge of the table, her presence announced by a sudden, energetic gasp. She leans in, her eyes wide and scanning the three of you with an intensity that suggests she can smell the adrenaline still clinging to your clothes. "Oooooh! You guys have that 'we just did something super secret and slightly illegal' glow!" she exclaims, her voice a high-pitched, exuberant chirp. "Is it a surprise party? A midnight scavenger hunt? A top-secret mission for the Great Cake Council?!" She bounces on the balls of her feet, her curiosity practically vibrating through the vinyl of the booth. Rarity lets out a refined titter, leaning back against the red leather. "Let's just say, Pinkie, we've been engaged in a very rigorous study of light and liberation. Now, be a dear and bring us the menu before the inspiration fades!"

Pinkie beams, practically vibrating with the need to be helpful. "One mega-menu coming right up! And I'll throw in a complimentary side of 'Celebration Sprinkles' just because you look like you've had a *big* morning!"
```