# QuickDraw_cGAN
cGAN generatív modell a Quick, Draw! adathalmazon tanítva
# Generatív modellek a művészetben: Az emberi és gépi kreativitás határai

Ez a repository a Feltételes Generatív Ellenséges Hálózat (cGAN) megvalósítását és eredményének elemzését tartalmazza. A képek generálása a "Quick, Draw!" adathalmaz alapján történik. A projekt célja az emberi és gépi kreativitás határainak feltérképezése.

## Főbb funkciók

1. **Modell implementáció**:
   - Feltételes generatív ellenséges hálózat (cGAN) használata képek generálására a "Quick, Draw!" adathalmaz alapján.

2. **Modell tanítása**:
   - Az adatok előkészítése, a modell architektúrájának kialakítása és a tanítási folyamat részletes leírása.
   - Teljesítményfigyelés a tanulási folyamat során.

3. **Teljesítmény monitorozása**:
   - Valós idejű mutatók a tanulási folyamat követésére.
   - Értékelési metrikák, például:
     - **Inception Score (IS)**
     - **Fréchet Inception Distance (FID)**

4. **Tesztelés és kiértékelés**:
   - A tanítás utáni elemzések tartalmazzák:
     - Kvantitatív metrikák számítása (IS, FID).
     - Generált képek vizuális elemzése.
     - Anomália detekció egyedi vagy váratlan minták azonosítására.

5. **Eredmények és következtetések**:
   - A generált képek minőségének és realizmusának értékelése, valamint összehasonlítása emberi alkotásokkal.

## Használat

1. Klónozd a repository-t:
   ```bash
   git clone <repozitórium_url>
