                        Amélioration de mon DSDT | ASUS K73SD (2450M, ALC269, Optimus, HD3000).

I. Modifications d'objets :

- [+] README.
- [+] DSDT original.
- [+] DSDT contenant la désactivation d'Optimus. (GFX0 -> IGPU)


II. Avancement des améliorations :

- [100%] Convertion de GFX0 (0x00020000) en IGP.
- [100%] Fonction RPUN && SPUN (Rev.2)
- [100%] Fonction ECCM && Q12O && PINI (Rev.2)
- [100%] Fonction SMCD (Rev.2)
- [100%] Convertion de IDE0 (0x001F0002) en SATA.
      -               [100%] Convertion de CHN0 en PRT0.
- [100%] Modification de TACH (Rev.3)
- [+] Correction de bugs mineurs (Rev.3)
- [+] Patch de correctif
      -               [100%] Convertion de _T_* en TT_*
      -               [100%] Fonction DTG
      -               [100%] Fonction B1B2
      -               [100%] Fonction SMBUS
      -               [100%] Correctif _PRW dans AC0
      -               [100%] Correctif _DSM dans HDEF
      -               [100%] Correctif _DSM dans GFX0
      -               [100%] Correctif IRQs Flags
      -               [100%] Correctif RTC
      -               [100%] Correctif Backlight
      -               [100%] Correctif _CID dans HPET
      -               [100%] Fonction EMEI && MCHC
      -               [100%] Correctif _DSM dans EHC1 && ECH2
      -               [100%] Correctif _DSM dans UHCI
      -               [100%] Convertion de AC0 en ADP1 
      -               [100%] Correctif LID + PBFE
- [-] Fonction _REG (Rev.1).
