# IQ Mahjong

Mahjong-parspil med uendelige baner, IQ-måler og fælles topliste.

Spillet er én fil, `index.html`. Netlify lægger den op automatisk,
hver gang der bliver ændret noget her i arkivet.

## Sådan spilles det

To ens brikker lægges i bakken, og så forsvinder de. En brik kan kun
tages, hvis der ikke ligger noget ovenpå den, og den er fri i enten
venstre eller højre side. Bakken har fire pladser — fyldes de uden et
par, er banen tabt.

## Hvad der er med

- Uendelige baner, der vokser i størrelse, lag og antal motiver
- IQ-måler med rangene Nysgerrig, Kvik, Skarp, Klog, Skarpsindig,
  Brillant, Genial og Geni
- Point med kædebonus, guldbrikker der giver dobbelt, og bane-bonus
- Fælles topliste via Firebase, med invitationslink
- Dyst-tilstand, hvor to spillere får præcis det samme bræt
- Ti sprog, valgt efter telefonens indstilling
- Gemmer bane, point og stilling midt i en bane
- Virker uden internet, når den først er åbnet
- Sikkerhedskode, der henter spil og rum tilbage på en ny telefon

## Filer

| Fil | Hvad den gør |
|---|---|
| `index.html` | Hele spillet |
| `sw.js` | Henter nyeste udgave når der er net, gemt udgave når der ikke er |
| `netlify.toml` | Siger til Netlify at filerne ligger i roden |
