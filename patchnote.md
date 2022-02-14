[Retour vers la list des véhicules](index.md)
## Patch note 09 février
- *(Shleidja)* Fix duplicated handling for exemplar
- *(Shleidja)* Fix wrong vehicle class for somes vehicule (no real change just more optimised)
- *(Shleidja)* Update vehicle list with correct class for staff [Link](shleidja.github.io)

## Patch note 08 février
- *(Gost)* Remove PolTarv / LSSDinsurgent
- *(Gost)* Add CenturionLSPD / CenturionLSSD

## Patch note 07 février
- *(Shleidja)* Add Modkit to Gruppesechs vehicule float [Preview](https://streamable.com/gym9gc)
- *(Shleidja)* Remove some unused vehicule from cnt & move all the other to cnt2
  - ummarkbuff
  - sanchezbcso
  - newsvan (Same inside WEAZEL pack inside ve_civil)
  - marverick2 (Previously Maverick BCSO)
**Livery**
  - Remove Stockade (Brinks on veille sur vos bourses)
  - Remove Old Darnell Bros (a new one is available from previous version)

## Patch note 29 janvier
- (Gost) Add LScoFD Pack
**Add Livery**
  - lsfdstanier2
  - lsfdamb4
  - lsfdtruck
  - lsfdtruckold
  - lsfdtruckhazmat
  - LSFDwaterres
  - LSFDutil
  - LSFDamb3
  - LSFDamb4
**Add New model**
  - ambucara
  - bcfdbufac
  - lsfdbufac (+livery umk)
  - lsfdbufs (+livery BCFD & umk)
  - lsfdscout (+livery BCFD)
  - lsfdscout2
  - lsfdyosemite

## Patch note 24 janvier
- *(Shleidja)* LSPD/LSSD: All torrence buff vMax & Accel
- *(Shleidja)* LSPD/LSSD: Alamo fix attempt for rebound
- *(Gost)* Add livery SAMS (Lite)
  - airbus
  - Lconteder
  - Leveron
  - LSFDfugitive
  - LSFDgranger
  - emsroamer
  - LSFDamb3
  - MOCPACKER2
  - LSPDmav

## Patch note 23 janvier
- *(Gost)* 
  - LSPD: Fix Layout LSPDbus 
  - MED: Fix Carcols EMSNSPEEDO w/ CNT2
  - LSSD : Fix Carcols LSSDNewScout16 w/ CNT2

- *(Shleidja)* ENTREPRISE: Ajout de 15 livery sur le pounder classique pour les entreprise suivantes:
    - E Cola
    - Bean Machine Coffee
    - Mirror Pack Garage
    - Burger Shot
    - LTD
    - Sprunk
    - NAPL
    - Up'n'Atom
    - Cooperative
    - Los Santos Custom
    - Benny's
    - LS Fuel
    - S.A Cleaning
    - Pearls
    - Auto Repair

## Patch note 19 janvier
- *(Shleidja)* CIVIL: Buff Kusa & Kunoichi

## Patch note 18 janvier
- *(Shleidja)* LSPD/LSSD: Buff de la polbuffalo (autre buffalo que TD)

## Patch note 16 janvier
- *(Shleidja)* LSPD: Changement de la Torrence 2016 > Buffalo 09 (Trafic division)

## Patch note 12 janvier
- *(Gost)* Optimisation des ytd (yellow -> blue)
- *(Shleidja)* Fix scharmann qui gigotte comme un flamby #2
- *(Shleidja)* Buff des alamo LSPD/LSSD pour ajouter de la diversité (equivalent a un scoot avec des attributions différentes) et travail sur les suspensions
- *(Shleidja + Brigann)* Changement léger sur le modele du towtruck3 pour éviter les soucis de collisions avec les gros véhicules
- *(Shleidja)* Nerf du speedo police pour l'adapter a la version civil et rename d'un handling qui avait un nom similaire pour éviter les conflits (EMS/POLICE)

## Patch note 10 janvier
- *(Gost)* Fix carcols all SASP / LSSDnewScout16 / EMSnspeedo

## Patch note 9 janvier
**Police**
- *(Shleidja)* TD (LSPDtorrence) / TED (LSSDbuffalo09): Mise a jour du handling vMax: ~220 / buff accéléraration

**Rangers**
- *(Shleidja)* SASPseminole: Rename du handling & fix de la maniabilité, il ne se retourneras plus

**Global VE**
- *(Shleidja)* Ajout du frein moteur sur différents modéle ayant été oublié 
- *(Shleidja)* Retrait de handling non utilisé
- *(Shleidja)* Rename de handling ayant le même nom/nom incohérant pour moins de conflits / plus de clarté

**cnt/cnt2**
- *(Shleidja)* Supression du fichier Tow (Mise du contenus dans les fichiers présent dans datals)
- *(Shleidja)* Suppresion du fichier datacasino (Mise du contenus dans les fichies présent dans datals)
- *(Shleidja)* Mise a jour du FXmanifest (retrait du load des fichier inexistant)
- *(Shleidja)* FXmanifest, fix d'un fichier qui ne loadais pas (WEAPON_SHOP_INFO > WEAPON_SHOP_INFO_METADATA_FILE (hose LSFD))

## Patch note 8 janvier
- *(Gost)* Fix carcols Lifeguard
- *(Gost)* Changement de la texture de la pushbar du LSSDcontender (Retrait des smiley)

**Global**
- *(Shleidja)* Retrait de certains handling non utilisé des fichiers
- *(Shleidja)* Tentative de retrait des supersportive dans le spawn naturel des véhicule (Turismor & adder)

**Police**
- *(Shleidja)* MRD LSPDRaiden: set de la vMax à 130 km/h (ce n'est pas un véhicule de poursuite mais bien de démonstration)
- *(Shleidja)* MRD LSSDoldcoquette: set de la vMax à ~140 km/h (ce n'est pas un véhicule de poursuite mais bien de démonstration) + fix de la maniabilité, elle ne se retourneras plus

**USSS**
- *(Shleidja)* Fix d'un handling qui ne chargais pas 
- *(Shleidja)* Nerf du scout USSS qui était bien trop puissant (plus que les scout police)

## Patch note 7 Janvier
**Police**
- *(Shleidja)* LSPD/LSSD fugitive: Buff afin qu'elle égale les autres véhicule (Stanier, washington, buffalo, etc)
- *(Gost)* Ajout d'un YTD manquant pour le OLD Alamo GND qui causais un probléme de chargement
- *(Gost)* Changement du bruit moteur de toute les stanier suite a de nombreuses plaintes.

**Gruppeschs**
- *(Shleidja)* Fix d'un probleme de conflits entre les noms de handling scout

**FXManifest**
- *(Shleidja)* Retrait du S a "game" qui causais le non chargement des ressources.

## Patch note 6 Janvier
- *(Gost)* changement des nom de fichier (dans le fxmanifest aussi) avec des _ à la place des - (demande par stacked, c'est plus conventionnel)

## Patch note 5 Janvier
- *(Gost)* Ajout du nouveau Alamo OLD + d'une livery GND (Replace)

**Police**
- *(Shleidja)* Buff de l'accélération des stanier & washington
- *(Shleidja)* Rename du handling de la washington pour éviter les conflits avec le véhicule vanilla
- *(Shleidja)* Retrait d'un handling inutilisé causant des conflits

**Global**
- *(Shleidja)* Buff légér  de la wolfsbane qui ne suivais pas dutout la cadence des autres motos (Maintenant un poil moins puissante qu'une sovereign)
- *(Shleidja)* Ajout d'une vitesse à la Sovereign qui n'en avait que 4
- *(Shleidja)* Buff léger de la primo2 qui manquais un peu d'accélération (vMax ~160)