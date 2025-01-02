A beadandóm témája a Connect 4 nevű stratégiai amőbajáték megvalósítása programozási eszközökkel. A projekt során olyan fejlesztési eszközöket használtam, mint például a Maven, amely lehetővé tette, hogy a futtatáshoz szükséges függőségeket és plugineket hatékonyan kezeljem. Ennek köszönhetően a kódom tisztán és hibamentesen működik, a projekt végén pedig egy futtatható JAR fájlt is létrehoztam, amely tartalmazza a teljes programot.

A játékot az objektumorientált programozás alapelveit figyelembe véve terveztem és valósítottam meg. A program indításakor a játékos nevét kérem be, majd ellenőrzöm, hogy létezik-e mentett játéktábla. Ha van, azt betöltöm, ellenkező esetben egy üres pályáról indítom a játékot. A gép piros (RED), a játékos sárga (YELLOW) korongokkal játszik. A játék célja, hogy a játékos vagy a gép elsőként helyezzen el négy azonos színű korongot egymás mellett vízszintes, függőleges vagy átlós irányban.

A játék végén a program megkérdezi a játékost, hogy szeretné-e az eredményt elmenteni. Ha a válasz igen, az eredményt exportálom egy eredménytáblába, így biztosítva a játékadatok nyomon követését.
