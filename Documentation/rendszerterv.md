## 1. Rendszer célja

A rendszer egy matematikai tanulmányokat megsegítő weblap. A legfőbb funkció a kurzusok megvalósítása, amelyekre az emberek jelentkezhetnek, létrehozhatnak hogy elkezdjék tanulmányaikat egy adott témakörból. Regisztráció és bejelentkezés nélkül a weboldal funkciói nem elérhetőek. Ebben az esetben egy betekintő oldalra érkezik a látogató és megtekintheti milyen funkciókat érhet el ha készít egy fiókot. Sikeres regisztráció és bejelentkezés után már létrehozhat kurzust a felhasználó és jelentkezhet is azokra. Minden kurzust amelyet létrehoz egy felhasználó adatbázisban kell eltárolni és hozzákell rendelni azt a felhasználóhoz aki létrehozta. Ezek alapján azt is tárolni kell, hogy ki milyen kurzusokra jelentkezett. Ezek alapján megvalósítható az előrehaladás nyomon követése adott felhasználóknál. Az egyes kurzusokhoz biztosítanunk kell a lehetőséget a véleménykifejtésre valamint a kérdések feltevésére. Ezt egy fórum szerű felületen tehetik meg a felhasználók, ezzel növelhetjük az interakciót a kurzus vezető és a kurzus résztvevő között. A felhasználók mérföldköveket teljesíthetnek előrehaladásuk során. Lehetőséget kell biztosítanunk egyaránt egyszerű és komplexebb kurzusok megvalósítására. Ezt elérhetjük előre létrehozott sémák segítségével. A kurzusokba videó anyagokat, hang anyagokat is fel lehet tölteni így ezt is engedélyeznünk kell. Az adott kurzusokat módosíthatják, törölhetik a felhasználók de csak az aki az adott kurzusnak a tulajdonosa, más felhasználó nem. Ezen kívül szerkeszthetik profiljuk adatait is. Ezen felületen tekinthetik meg kurzusokkal kapcsolatos információjukat is a felhasználók. Létre kell hoznunk egy olyan jogkört, egy felsőbb rendű felhasználót aki a weboldalon történő karbantartást végzi. Ezen felhasználó nevezzük adminisztrátornak korlátlanul módosíthatja, törölheti a kurzusokat valamint szerkesztheti a felhasználók adatait. Ő kapja meg a felhasználók által jelzet hibákat is amelyeket orvosolhat vagy tovább küldheti a fejlesztő csapatnak. Ezen funkciós összességével megvalósíthatunk egy e-learning felület ahol a felhasználók kiaknázhatják tudásukat tanulmányaik teljesítésének érdekében.

## 4. Követelmények

**Funkcionális követelmények**
  - Bejelentkezés
  - Regisztráció
  - Kijelentkezés
  - Felhasználók adatainak tárolása
  - Felhasználók tudják változtatni adataikat
  - Lehetőség van kurzusok felvételére
  - Saját kurzusok létrehozására is van lehetőség
  - A kurzusokban való haladással mérföldkövek elérése
  - Elért mérföldkövek megtekintése
  - Hiba esetén lehetőség van értesíteni az adminisztrátort
  - A kurzusokban létrehozott gyakorló feladatok kitöltése is lehetséges, és kitöltés után visszajelzést kap a felhasználó a teljesítményéről

  **Nem funkcionális követelmények**
  - A felhasználók nem férnek hozzá egymás adataihoz
  - A felhasználók nem tudják módosítani a más által közzétett kurzust
  - Az adminisztrátori felületet csak az adott joggal rendelkezők érik el
  - A felhasználók nem tudnak más nevében felvenni kurzusokat
  - A vendégek nem tudnak felvenni kurzusokat
  - Vendégek nem tudnak létrehozni kurzust
  - Bejelentkezett felhasználóknak a bejelentkezés és a regisztráció fül nem elérhető.

  **Törvényi előírások, szabványok:**
  - GDPR-nak való megfelelés
  - Tervezési mintáknak való megfelelés.

  ## 5. Funkcionális terv

  **Rendszerszereplők:**
  - Adminisztrátor
  - Felhasználó
  - Vendég

  **Rendszerhasználati esetek és lefutásaik:**
  - **Adminisztrátor**
    - Felhasználók adatainak módosítása, felhasználók törlése
    - Kurzusok hozzáadása, kurzusok módosítása
    - Hibák javítása, adott esetben hiba jelzése a programozóknak.
  - **Felhasználó**
    - Kurzus felvétel
    - Kurzus leadás
    - Kurzus felvétele a kívánságlistára
    - Saját kurzus létrehozása
    - Saját kurzusok szerkesztése

  - **Vendég**
    - Kurzusok megtekintése
    - Regisztráció
    - Bejelentkezés

  - **Menü-hierarchiák:**

## 6. Fizikai környezet
  - Az alkalmazás csak web platformra készül.
  - Nincsenek megvásárolt komponensek.
  - **Fejlesztői eszközök:**
    - Visual Studio Code
    - Notepad++
    - Sublime text 3
    - MySQL Workbench
    - HediSQL 

