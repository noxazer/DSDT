0%      = [0.0/100];
35%     = [3.5/100];
78%     = [7.8/100%];
100%    = [100%].
Ajout   = [+].
Retrait = [-].

                        Amélioration de mon DSDT | ASUS K73SD (2450M, ALC269, Optimus, HD3000).

I. Modifications d'objets :

- READM				__________________[+].
- DSDT origina				__________________[+].
- DSDT contenant la désactivation d'Optimus               (GFX0 -> IGPU)	__________________[+].


II. Avancement des améliorations :

- Convertion de GFX0 (0x00020000 Fichier A) en IGP	_______________________________________[100%].
- Fonction RPUN && SPUN (Rev.2		_______________________________________[100%].
- Fonction ECCM && Q12O && PINI (Rev.2		_______________________________________[100%].
- Correction de bugs mineurs (Rev.2		__________________________________________[+].
- Patch de correctif			__________________________________________[+].
      -               Convertion de _T_* en TT_*		_______________[100%].
      -               Fonction DTG			_______________[100%].
      -               Fonction B1B2  			_______________[100%].
      -               Fonction SMBUS 			_______________[100%].
      -               Correctif _PRW dans AC0 			_______________[100%].
      -               Correctif _DSM dans HDEF           (Alc269, hda-gfx	_______________[100%].
      -               Correctif _DSM dans GFX0           (HD3000, hda-gfx	_______________[100%].
      -               Correctif IRQs Flags                 (Sandy Bridge	_______________[100%].
      -               Correctif RTC                      (??, Sandy Bridge	_______________[100%].
      -               Correctif Backlight                     (PNLF		_______________[100%].
      -               Correctif _CID dans HPET            (_CID.PNP0C01)	_______________[100%].
      -               Fonction EMEI && MCHC           (EMEI && MCHC -> PCI0	_______________[100%].
      -               Correctif _DSM dans EHC1 && ECH2   (USB MacBookP8.1	_______________[100%].
      -               Correctif _DSM dans UHCI           (USB MacBookP8.1	_______________[100%].
      -               Convertion de AC0 en ADP1 		_______________[100%].
- Fonction _REG (Rev.1) 		__________________________________________[-].
