poker
- index.php: A főoldal, ahol a játékot lehet elindítani.
- game.php: A játék főoldala, ahol a játék zajlik.
- styles.css: A játékhoz tartozó stíluslap.
- logic.php: A játék logikáját tartalmazó fájl.

Mit tartalmazzanak a fájlok?

- index.php: Egy űrlapot, ahol a játékostól bekérjük a nevét, és egy gombot, amivel elindíthatja a játékot.
- game.php: A játékot magát. A játékostól bekérjük a tétet, majd a játék végeztével megjelenítjük a nyertes kezet.
- styles.css: A játékhoz tartozó stíluslap.
- logic.php: A játék logikáját tartalmazó fájl. Ebben a fájlban kell megvalósítani a játék logikáját.

Hogyan működik a játék?

1. A játékos megnyitja a főoldalt (index.php).
2. A játékos megadja a nevét, majd elindítja a játékot.
3. A játék átirányítja a játék főoldalára (game.php).
4. A játékostól bekérjük a tétet.
5. A játék végeztével megjelenítjük a nyertes kezet.
6. A játékos visszatér a főoldalra, és új játékot indíthat.

### Póker szabályai
1. Cél: A játék célja, hogy a lehető legjobb öt lapból álló kombinációt alkossunk, vagy megnyerjük a potot, ha a többi játékos dobja a lapjait.

2. Játékosok: 1 Játékos vs 1 Számítógép

3. Kártyák: A pókerben 52 lapos francia kártyapaklit használunk. A lapok értéke a következő sorrendben csökken: Ász, Király, Dáma, Bubi, 10, 9, 8, 7, 6, 5, 4, 3, 2.

4. Kombinációk: A pókerben a következő kombinációkat ismerjük el, a legjobb kombinációtól a legrosszabbig: Royal Flush, Straight Flush, Four of a Kind, Full House, Flush, Straight, Three of a Kind, Two Pair, One Pair, High Card.

5. Kezdés: A játék kezdetén mindenkinek 5 lapot osztunk. A játékosnak lehetősége van cserélni a lapokat, majd meg kell adnia a tétet.

6. Körök: A játék körönként kirak egy közös lapot, majd a játékosoknak lehetősége van tétet tenni, emelni vagy dobni. A játék addig tart, amíg valamelyik játékos megnyeri a potot, vagy a többi játékos dobja a lapjait.

7. Nyertes: A játékot az nyeri, akinek a legjobb kombinációja van a kezében, vagy aki megnyeri a potot, ha a többi játékos dobja a lapjait.

Kombinációk értékei:
- Royal Flush: Ász, Király, Dáma, Bubi, 10 ugyanolyan színben.
- Straight Flush: Öt lap egymás után ugyanolyan színben.
- Four of a Kind: Négy azonos értékű lap.
- Full House: Három azonos értékű lap és két azonos értékű lap.
- Flush: Öt lap ugyanolyan színben.
- Straight: Öt lap egymás után.
- Three of a Kind: Három azonos értékű lap.
- Two Pair: Két azonos értékű lap és két azonos értékű lap.
- One Pair: Két azonos értékű lap.
- High Card: A legnagyobb lap az öt lap közül.
- Semmi: Ha nincs kombináció a kezünkben.

Körök: 
Pre-flop: A játékos megkapja az első öt lapját.
Flop: A játékos megkapja az első közös lapot.
Turn: A játékos megkapja a második közös lapot.
River: A játékos megkapja a harmadik közös lapot.

