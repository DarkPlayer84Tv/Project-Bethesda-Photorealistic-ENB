# Project-Bethesda-Photorealistic-ENB
DP84 ENB Multi-Game Presets

Descrizione

DP84 ENB Multi-Game è un progetto di preset ENB fotorealistici e sperimentali per 7 giochi:

Fallout 4 (Next Gen / Old Gen)

Skyrim AE

Skyrim LE

Fallout 3

Fallout: New Vegas

The Elder Scrolls IV: Oblivion

Include preset ottimizzati per laptop/PC con 16 GB di RAM e versioni avanzate per 32 GB di RAM, oltre a preset sperimentali "Fiabesco Medievaleggiante" per Skyrim AE e LE.

Il progetto è pensato per offrire un look fotorealistico con gestione avanzata di Bloom, DOF, SSAO, SSR, Subsurface Scattering e LUT personalizzate.

Contenuto del Pacchetto

Per ciascun gioco troverai:

[Game_Name]/
├─ enbseries.ini
├─ enblocal.ini
├─ README.txt
├─ DP84_Visuals/
│  └─ LUTS/
│     ├─ DP84_LUT_Warm.dds
│     ├─ DP84_LUT_Cinematic.dds
│     └─ DP84_LUT_Neutral.dds
├─ with_enblocal/
│  ├─ enbseries.ini
│  ├─ enblocal.ini
│  ├─ enbcolor.ini
│  ├─ enbdepthoffield.ini
│  ├─ enbpostprocessing.ini
│  ├─ enbssao.ini
│  ├─ enbreflections.ini
│  └─ README_with_enblocal.txt
├─ Preset_32GB_RAM/
│  ├─ enbseries.ini
│  ├─ enblocal.ini
│  ├─ README_32GB.txt
│  └─ with_enblocal/  (stessa struttura di sopra)
└─ esperimenti/  (solo per Skyrim AE & LE)
   ├─ enbseries_experimental.ini
   ├─ enblocal_experimental.ini
   ├─ README_experimental.txt
   └─ DP84_Visuals/LUTS/
      ├─ DP84_LUT_Fiabesco_Warm.dds
      └─ DP84_LUT_Fiabesco_Glow.dds

Installazione

Backup dei file ENB esistenti (enbseries.ini, enblocal.ini) nella cartella principale del gioco.

Copia i file del preset principale nella root del gioco.

Per provare la versione con tutti i supporti, copia la cartella with_enblocal/.

Per sistemi con 32 GB di RAM, usa la cartella Preset_32GB_RAM/.

Per Skyrim AE/LE, prova anche i preset sperimentali in esperimenti/ per un look fiabesco medievaleggiante.

Nota: Nessun file binario/DLL incluso. Scaricare e usare le DLL ufficiali ENB per ogni gioco.

Filosofia del Progetto

Fotorealismo: Bloom, DOF, SSAO, SSR e SSS ottimizzati.

Modularità: cartelle separate per versioni RAM, esperimenti e support files.

Esperimenti estetici: preset fiabeschi per Skyrim AE/LE con toni caldi, luce volumetrica e particelle luminose.

Compatibilità laptop/PC: impostazioni bilanciate per RTX 4070 Mobile e monitor 1920×1080 a 165Hz.

Consigli

Testare un preset alla volta.

Per sistemi con VRAM limitata, mantenere i preset base (16GB).

Per Skyrim LE/DX9 (Oblivion, Fallout 3/NV) usare valori di VRAM più conservativi se necessario.

Contribuire

Il progetto è open source e accetta suggerimenti su:

Miglioramento dei valori ENB per ciascun gioco

Creazione di nuovi preset sperimentali

Ottimizzazione per nuove GPU e versioni future

Licenza

Distribuzione gratuita per uso personale e testing. Non includere file DLL ufficiali ENB.
