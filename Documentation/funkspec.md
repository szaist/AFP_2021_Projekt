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