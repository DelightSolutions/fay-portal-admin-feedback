Portál Admin rendszer
=========================

O.K. Központ portál rendszer admin felületéhez tartozó issue tracker

## Hasznos információk
* Kitelepített verzió: **Build 0610**

#### Build 0610 változtatásai

- Új modulok:
  * Jogosultság sablonok
  * Tréning
  * Felhasználó kezelés
  * Rendszerüzenetek
  * Nyelvek
  * GYIK
  * Alkalmazások 
  * API
- Az API jelenleg nem elérhető, az API dokumentáció viszont megtalálható a portál adminban.
- GYIK többnyelvűsítve
- Felhasználó lértehozása egyelőre nem a végleges működéssel valósul meg
- Létrehozhatóak az adminhoz kapcsolódó alkalmazások, melyeknél az API kulcs generálása automatikus

## API

*Néhány metódus esetében a hiányzó mögöttes tartalom miatt DUMMY adatokat ad vissza az API*

- Adható OK Pont
- Létrehozható User aktivitás
- Bejelentkezés
- API kulcs alapú authentikáció, esemény és pontszám rögzítés

#### Build 0528 változtatásai

- A portál ettől a verziótól már tartalmazza a jogosultság kezelést. A jogosultság szerkesztő hiánya miatt minden felhasználó superuser jogokkal rendelkezik, azaz semelyik tevékenység nem tiltott.
- Kibővített esemény kezelés
  * Események
  * Felszerelések
  * Tevékenységek
  * Reprezentációs eszközök
  * Megválaszolandó kérdések
  * Szóróajándékok
- Néhány megjelenésbeli változtatás, finomítás

#### Build 0521 változtatásai

_Ez a build egy hotfix_

Az alábbi hibák lettek javítva:

* [Bizonyos fieldek nem működnek az intézményi adatok rögzítésénél](https://github.com/DelightSolutions/fay-portal-admin-feedback/issues/12)
* [Intézmény megtekintése](https://github.com/DelightSolutions/fay-portal-admin-feedback/issues/11)

#### Build 0520 változtatásai

**!!! Ez a verzió az adatbázis resetelésével jár, ezért a felhasználóknak újból kell regisztrálniuk**

* Exportálás funkció hozzáadva
* Működő menü aktív állapotok
* Intézmény szerkesztési hiba javítva
* Több elemű mező kitöltő control hozzáadva
* Historyn belül megjelenik a módosítás dátuma
* Rendezés + keresés ajaxosítva, működik

--

#### Build 0516 változtatásai
* Megjelentek az angol változónevek fordításai
* Ajax alapú oszlop rendezés, táblázat lapozást (50 elem felett)
* Működő fuzzy keresés (egyelőre nem ajax, ez később az lesz)
* Különböző objektumok változtatásainak logja megtekinthető
* A dátum, idő, dátum-idő választó mezők okosabbak lettek

