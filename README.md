# Vaja5-buttons-LED-STM32F0-

1. S pomočjo programskega okolja STM32CubeIDE sprogramirajte mikroprocesor tako, da bosta ob pritisku ustrezne tipke zelena in modra LED utripali po spodjem opisu.

        a. Tipka T1: Zelena LED utripa s frekvenco 2 Hz, in sicer 5x.

        b. Tipka T2: Modra LED utripa s frekvenco 2 Hz, in sicer 5x.

        c. Tipka T3: Modra in zelena LED utripata izmenično s frekvenco 1 Hz, vsaka LED 5x.

        d. Tipka T4: Prikaz SOS (Morsejeva abeceda) z zeleno LED (modra za eno sekundo naznani konec in začetek SOS.

        e. Tipka T5: Utripanje zelene LED: začetna frekvenca je 1 Hz, vsak naslednji cikel je frekvenca mnogokratnik števila 2, vse do frekvence 1000 Hz.

        f. Tipka T6: Modra in zelena LED utripata izmenično z začetno frekvenco 1000 Hz, vsak naslednji cikel je frekvenca deljena z 2, vse do frekvence 1 Hz.


2. Postopek inicializacije periferije
   - T1: **PB10**, T2: **PB11** , T3: **PB12**, T4: **PB13**, T5: **PB14**, T6: **PB15**, zelena LED: **PC9**, modra LED: **PC8**.

## Pinout
