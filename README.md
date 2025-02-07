# IO-PrincipiaOrbitPatches
Contains patches to make various planet pack orbits stable with ***Principia*** tested to ~5,000+ years (unless stated otherwise).
Compatible with ***IO-AlteredOrbits***.

Currently contains:

  ***Stock Joolean System*** - Fixes ejection of Vall, Bop, and Pol out of Joolean system; increases SMA of Vall, Tylo, Bop, and Pol, and makes Bop's orbit retrograde. ~~Values copied directly from Principia's patch.~~ Values differ from Principia's patch for better stability (Vall still tended to escape the system a few hundred years in with the original patch). New patch changes the orbital resonances to 1 : e : e<sup>2</sup> : sqrt(5)\*e<sup>2</sup> : 2\*sqrt(5)\*e<sup>2</sup>. (2 instead of sqrt(5) was used at first but Bop would leave the system after a few thousand years due to proximity to Tylo/Pol.)
***Necessary if installing a planet pack.***
  
  ***Outer Planets Mod*** - Fixes disturbances of inner Sarnus system; increases Ovok's SMA to outer system as well as its eccentricity and inclination, making Ovok's orbit retrograde. Values derived from the work of @EnderDragneel and @ryansennis.
  
  ***Minor Planets Expansion*** - ~~Fixes unstable orbit of Kal; increases Kal's SMA and eccentricity to more closely resemble Namaka. Values derived from https://bit.ly/3jeKkab, with the ratio of Ki'Ki's to Hi'iaka's SMA as reference.~~ (< This has now been included in the base install of ***MPE***.) Lint-Mikey's orbit has been changed slightly with the intent to avoid interactions with Jool. While stable (enough), its implementation was not thorough and it is likely entirely optional. Even with the change, Lint-Mikey still interacts with Duna (and possibly Jool).
  
  ***Neidon Plus*** - Nito and Tito have been moved out from their dangerous proximity to Neidon; Nito is now an asteroid-like body akin to Nissee, and Tito is now a retrograde moon of Chymere. Chymere has been moved out as well, past the orbit of Thatmo. SMA of Hårgalað decreased a bit (stability of Hårgalað only tested to 1820 years). Please delete *GameData/NeidonPlus/Patches/GregoriaOPMMoverAndShaker.cfg* if it exists.
  
  ***Extrasolar*** - SMA of Serex increased by 1.25x to avoid apparent "Schwarzschild radius" effect. SMAs of Solyth, Fust, Mir, and Lomina have been increased by 1.25533185x for general stability. Tested to 3,691 years.
  
  ***Kcalbeloh System*** - Several changes were made, based off version 1.0.1, but with access to updated (1.0.2?) configs of the Simetra-Simeht system. Most notably, the Simetra-Simeht and Aralc binary systems were altered, removing the barycentre body and roughly shifting the sattelites (SMAs, inclinations, eccentricities) to account for it. In the Simetra-Simeht system specifically, Noyreg proved nontrivial to find a stable orbit (though I'm sure an SMA or meanAnomalyAtEpoch exists), but Norihc was fine, so I opted to merge the two into a binary system where Norihc was located. Noi and Noira use their updated (1.0.2?) configs. SMAs of Anehta/Aciore and Tot had to be changed for their stability; SMAs of Sunorc and Aralc increased for stability of Simetra-Simeht and Anehta/Aciore, respectively; and SMAs of Kcalbeloh sattelites increased so as to better space out the bodies in the empty space left by the previous changes. Enots was removed as a stable orbit does not appear to exist in proximity to Anehta/Aciore without making further creative changes to the system. It's fate, as well as the inclusion of this patch (or a version thereof) in ***Kcalbeloh*** proper will be left up to @Jason Kerman. Changes also include removal of explicit draw modes of patched conics and other unnecessary properties such as orbital periods, as well as fixing of tidal locking and rotation periods when appropriate (Simetra, Simeht, Norihc, Noyreg). 
**PLEASE NOTE: the wormhole around Jool will disrupt the system! It has NOT been adjusted in this patch. A simple increase in SMA should work fine, say 1.25-1.5x, but this has not been tested nor implemented.**

***Janet's Planets*** nor ***Grannus Expansion Pack*** do not require any adjustments to work with ***Principia***.
