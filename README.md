# IO-PrincipiaOrbitPatches
Contains patches to make various planet pack orbits stable with Principia tested to ~5,000+ years (unless stated otherwise).
Compatible with IO-AlteredOrbits.

Currently contains:

  **Stock Joolean System** - Fixes ejection of Vall, Bop, and Pol out of Joolean system; increases SMA of Vall, Tylo, Bop, and Pol, and makes Bop's orbit retrograde. ~~Values copied directly from Principia's patch.~~ Values differ from Principia's patch for better stability (Vall still tended to escape the system a few hundred years in with the original patch). New patch changes the orbital resonances to 1 : e : e<sup>2</sup> : sqrt(5)\*e<sup>2</sup> : 2\*sqrt(5)\*e<sup>2</sup>. (2 instead of sqrt(5) was used at first but Bop would leave the system after a few thousand years due to proximity to Tylo/Pol.)
    ***Necessary if installing a planet pack.***
  
  **Outer Planets Mod** - Fixes disturbances of inner Sarnus system; increases Ovok's SMA to outer system and eccentricity, and makes Ovok orbit retrograde. Values derived from the work of EnderDragneel and ryansennis.
  
  **Minor Planets Expansion** - ~~Fixes unstable orbit of Kal; increases Kal's SMA and eccentricity to more closely resemble Namaka. Values derived from https://bit.ly/3jeKkab, with the ratio of Ki'Ki's to Hi'iaka's SMA as reference.~~ (< This has now been included in the base install of MPE.) Lint-Mikey's orbit has been changed slightly with the intent to avoid interactions with Jool. While stable (enough), its implementation was not thorough and it is likely entirely optional. Even with the change, Lint-Mikey still interacts with Duna (and possibly Jool).
  
  **Neidon Plus** - Nito and Tito have been moved out from their dangerous proximity to Neidon; Nito is now an asteroid-like body akin to Nissee, and Tito is now a retrograde moon of Chymere. Chymere has been moved out as well (SMA\*4.5) past the orbit of Thatmo.
  
  **Extrasolar** - SMA of Serex increased by 1.25x to avoid apparent "Schwarzschild radius" effect. SMAs of Solyth, Fust, Mir, and Lomina have been increased by 1.25533185x for general stability. Tested to 3,691 years.
  
  **Kcalbeloh System** - ***The wormhole around Jool will disrupt the system! It has not been adjusted in this patch. A simple increase in SMA should work fine, say 1.25-1.5x, but this has not been tested nor implemented.***
