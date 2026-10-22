# Vizsgaremek 2026/27-es tanév 
### R.E.R.S (Rental Electronic Report System)

###### Fejlesztők: Tóth Gergely, Lengyel István, Szász Benedek

Társasházi Hibabejelentő és Adminisztrációs Rendszer
1. Projektkoncepció és Valós Probléma
A társasházak mindennapi működésének egyik legnagyobb problémája a hiányos kommunikáció és az átláthatatlan ügyintézés. Tipikus példa: egy lakó hazatérve vizes foltot talál a fürdőszoba plafonján, lefotózza, majd értesíti a közös képviselőt. Ezt követően azonban megszűnik az információáramlás – a lakó nem tudja, hogy látták-e a bejelentést, kiosztották-e a szerelőnek, vagy mikorra várható a javítás.
Rendszerünk célja egy olyan átlátható, könnyen kezelhető, webes alapú hibabejelentő platform megvalósítása, amely pótolja ezt a hiányosságot. Nemcsak a hibák életútját követi végig a bejelentéstől a lezárásig, hanem integrált mérőóra-diktálási funkciót is biztosít, tehermentesítve a lakókat és a közös képviselőt a papírmunkától.

2. Csapatfelosztás:
Tóth Gergely: Backend (Laravel PHP), adatbázis-terv, adatbázis kezelés, fejlesztői dokumentáció.
Szász Benedek: Frontend stílusok (CSS Angular), favicon tervezés, szoftvertesztelés (Playwright), fejlesztői dokumentáció, angolra fordítás.
Lengyel István: Frontend felületek (HTML Angular), felhasználói dokumentáció, verziókövetés és git-ágkezelés.
Keretrendszerek és egyéb eszközök:
Frontend: Angular (TypeScript)
Backend: Laravel PHP REST API
Tesztelés: Playwright

3. Funkciók:
Hibakezelés: Bejelentés leírással, fotó feltöltéssel, kategóriák megadásával. Státuszkövetés: Beküldve → Folyamatban → Megoldva.
Mérőóra-diktálás: Havonta lévő víz-, gáz- és villanyóra-állások rögzítése fotós igazolással, automatikus táblázatos exportálási lehetőséggel a közös képviselő számára.
Adminisztrátori Irányítópult: A közös képviselő egy helyen látja az új hibabejelentést, módosíthatja azok státuszát, és kezelheti az admin felületet.
További funkciók: Szerepkör-alapú jogosultságkezelés (Lakó / Adminisztrátor).
 


