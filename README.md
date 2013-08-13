0%      = [0.0/100];
35%     = [3.5/100];
78%     = [7.8/100%];
100%    = [100%].
Ajout   = [+].
Retrait = [-].

                        Amélioration de mon DSDT | ASUS K73SD (2450M, ALC269, Optimus, HD3000).

I. Modifications d'objets :

- [+]README
- [+]DSDT origina
- [+]DSDT contenant la désactivation d'Optimus               (GFX0 -> IGPU)


II. Avancement des améliorations :

- [100%]Convertion de GFX0 (0x00020000 Fichier A) en IGP.
- [100%]Fonction RPUN && SPUN (Rev.2)
- [100%]Fonction ECCM && Q12O && PINI (Rev.2)
- [+]Correction de bugs mineurs (Rev.2)
- [+]Patch de correctif
      -               [100%]Convertion de _T_* en TT_*
      -               [100%]Fonction DTG
      -               [100%]Fonction B1B2
      -               [100%]Fonction SMBUS
      -               [100%]Correctif _PRW dans AC0
      -               [100%]Correctif _DSM dans HDEF           (Alc269, hda-gfx)
      -               [100%]Correctif _DSM dans GFX0           (HD3000, hda-gfx)
      -               [100%]Correctif IRQs Flags                 (Sandy Bridge)
      -               [100%]Correctif RTC                      (??, Sandy Bridge)
      -               [100%]Correctif Backlight                     (PNLF)
      -               [100%]Correctif _CID dans HPET               (PNP0C01)
      -               [100%]Fonction EMEI && MCHC           (EMEI && MCHC -> PCI0)
      -               [100%]Correctif _DSM dans EHC1 && ECH2   (USB MacBookP8.1)
      -               [100%]Correctif _DSM dans UHCI           (USB MacBookP8.1)
      -               [100%]Convertion de AC0 en ADP1 
- [-]Fonction _REG (Rev.1)
