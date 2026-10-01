# scene-intro: parco intro dei reel «Giorno N»

Dal 01/10/2026 qui ci sono SOLO le 10 scene nuove (riprese in prima persona, camminata a mano, 8 secondi, 720p ricampionato a 1080x1920, 30 fps, senza audio).
Le intro vecchie (N1..N7, 23B, 23C) sono in `../archivio-scene-intro/`: non usarle.

Fase follower attuale: sotto 400. Una persona avanti con l'oggetto, gli altri lontani, girati e distratti.
Soglie: 400 follower = 2 persone avanti, 600 = 3, 800 = 4, 1000 = 5, poi +5 ogni 3000. A ogni soglia si generano intro nuove (tools/scena.py, piano/scene.json nel repo privato media).

| File | Oggetto | Ambiente | Durata |
|---|---|---|---|
| P1-corsia-video | rotolo di carta igienica | corsia di supermercato | 6s |
| P2-viale-video | buste bianche della spesa | viale alberato al tramonto | 6s |
| P3-notte-video | rotolo di carta igienica | strada di notte, vetrina accesa | 8s |
| P4-controller-video | scatola controller da gioco | galleria di un centro commerciale | 8s |
| P5-valigetta-video | cassetta attrezzi rossa | strada residenziale, mattina | 8s |
| P6-sacco-video | sacco a pelo arancione | banchina del treno all'alba | 8s |
| P7-maschere-video | scatola di maschere viso rosa | portici del centro storico | 8s |
| P8-ombretti-video | palette di ombretti nera | lungomare, mattina | 8s |
| P9-candela-video | candela profumata in vaso | vicoli di pietra, sera | 8s |
| P10-mattoncini-video | scatola di mattoncini giocattolo | sentiero nel parco, mattina | 8s |

La rotazione e' per famiglia (prefisso prima del primo trattino): ogni P1..P10 e' una famiglia a se', esce quella usata piu' tempo fa.
