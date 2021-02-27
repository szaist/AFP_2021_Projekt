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

