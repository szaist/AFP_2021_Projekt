## 1.Áttekintés

A rendszer a matematikai tanulmányok megsegítésére szolgáló alkalmazást kíván megvalósítani a jövendőbeli felhasználók számára. A rendszer lényege az, hogy a felhasználók különböző kurzusokat, képzéseket hozhatnak létre megadott témakörökkel, tananyagokkal. Felhasználó rendszer megvalósítása szükséges annak érdekében, hogy csak regisztrált felhasználó tudjon létrehozni kurzust vagy jelentkezni egyre. Ez azért szükséges hogy az egyes kurzoskat asszociálni tudjuk a felhasználókhoz, tárolni tudjuk az előrehaladásukat, sikereiket stb. Ezen adatokat egy adatbázisban kell eltárolni az adatok későbbi feldolgozása érdekében. Sikeres regisztráció és bejelentkezés után tudnak létrehozni kurzoskat és tudnak jelentkezni azokra a felhasználók. A regisztrált felhasználók megtekinthetik fiókjuk adatait és módosíthatják azokat. A felhasználók résztvehetnek, teljesíthetik a kurzusokat valamint lehetőséget kell biztosítani a véleménykifejtésre és egy fajta fórumot kell megvalósítani ahol a kérdéseiket feltehetik a kurzus résztvevői a tananyaggal kapcsolatban. Azok akik nem rendelkeznek fiókkal, látogatóknak minősülnek, akik betekintést nyerhetnek az alkalmazás funkcióiba, megtekinthetik az elérhető kurzusokat de nem jelentkezhetnek azokra, nem hozhatnak létre kurzosokat. A kurzos létrehozás során, a kurzushoz létrehozhatunk teszteket, tölthetünk fel videókat és különböző anyagokat amelyek segítik az aktuális tananyag megértését. Hasznos lenne lehetőséget biztosítani a korrepetálásra azon kurzus résztvevői számára, akik nem értik az anyagot és segítségre szorulnak. Egyes kurzusoknál mérföldköveket érhetnek el a résztvevők és előrehaladásukat nyomon tudják követni. Így megtudják, hogy mit hagytak ki, mit nem teljesítettek még vagy éppen azt, hogy melyik fejezeteket fejezték már be, teljesítették sikeresen. Lehetőséget kell biztosítani komplexebb és egyszerűbb kurzusok létrehozására egyaránt. A kurzusok létrehozását, megvalósítását objektum orientált módon kell megvalósítani az újrafelhasználhatóság érdekében. Így követhető egy alap séma minden kurzus létrehozásánál. A felmerülő hibák kiküszöbölésének érdekében szükséges egy felsőbb rendű felhasználó aki tudja módosítani a kurzusokat, törölni azokat, szerkesztheti a többi felhasználó adatait. Ezen felsőbb rendű felhasználó számára tudják jelezni az alkalmazásban felmerülő hibákat a felhasználók és ő tudja orvosolni vagy tudja jelezni a programmozó csapat felé a hibát. Ezt leszámítva minden felhasználó csak a saját kurzusát módosíthatja, törölheti más felhasználóét nem.

## 4. Jelenlegi üzleti folyamatok modellje

Jelenleg a projektünkhöz hasonló kurzus megosztó oldalakon nem tudsz saját kurzust létrehozni, ezért szeretnénk ezt megvalósítani. A másik hátránya a meglévő oldalaknak az, hogy előfizetés nélkül korlátozott a hozzáférés.

1. Bejelentkezés
    - 1.1 Előfizetés
        - Kurzusok felvétele
        - Kurzusok megtekintése
        - Kurzusok értékelése
    - 1.2 Beállítások
        - Email módosítás
        - Jelszó módosítás
    - 1.3 Kurzus betekintő
    - 1.4 Kijelentkezés
2. Regisztráció

## 5. Igényelt üzleti folyamatok modellje

1. Bejelentkezés
2. Regisztráció
3. Kurzusok (Vendég felhasználók láthatják a már meglévő kurzusokat)
    1. Kurzus kiválasztása
    2. Kurzus szerkesztése
    3. Kurzus törlése
    4. Mérföldkövek
4. Admin jogosultsággal (Ha be van jelentkezve a felhasználó és admin is egyben)
	1. Kurzus létrehozása
	2. Kurzus szerkesztése
	3. Kurzus törlése
	4. Felhasználók kezelése
5. Adatlap (Ha be van jelentkezve a felhasználó)
   1. Teljesített kurzusok
   2. Függőben lévő kurzusok
   3. Kívánságlistán lévő kurzusok
6. Beállítások (Ha be van jelentkezve a felhasználó)

## 6. Használati esetek

- Vendég:
    - Megtekintheti a kurzusokat, de nem hozhatnak létre újat, és nem jelentkezhetnek azokra.
- Felhasználó
    - Megtekintheti a kurzusokat és jelentkezhet azokra. Mérföldköveket érhet el a kurzusban való haladással, és ezeket meg is tekintheti.
    - Létrehozhat saját kurzusokat és ahhoz tartozó mérföldköveket is.
    - Lehetősége van gyakorolni a kurzusokhoz hozzáadott feladatok segítségével.
- Adminisztrátor
    - Képes felhasználókat kezelni, módosítani, törölni.
    - Szerkesztheti, törölheti a kurzusokat.
    - Gondoskodni tud az egyes hibák kijavításáról.
    - Abban az esetben ha nem tudja megoldani akkor tud szólni a programozóknak akik tudják javítani a hibát.



