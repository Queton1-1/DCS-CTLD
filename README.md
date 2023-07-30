# DCS-CTLD

**CTLD** pour **Complete Troops and Logistics Deployment for DCS World** est un script crée par [Ciribob](https://github.com/ciribob).

Il permet de transporter des troupes et des caisses de matériels appelées "crates" à partir d'hélicoptères et d'avions.
La capture de base et le renforcement de positions  défensives fait désormais partie du gameplay.
  
Pour en savoir d'avantage sur le fonctionnement [Lien vers la page GitHub de Ciribob](https://github.com/ciribob/DCS-CTLD).  

Je partage ici ma version de CTLD, lourdement adaptée, modifiée et commentée.  
Une vidéo arrivera prochainement sur ma chaîne [YouTube](https://www.youtube.com/channel/UCkYOYKrKMwCV-3yASP9gf8Q).
  
  
## Pour mettre en oeuvre **CTLD** :  

### Télechargez la dernière version à partir de la page [Releases](https://github.com/Queton1-1/DCS-CTLD/releases)  

### Ajustez les paramètres du script suivant vos besoins
ajoutez dans le tableau *ctld.transportPilotNames* le nom des unités (pas des groupes) concernées par le transport.  
> ctld.transportPilotNames = {  
> "mon avion -1",
> "mon helico -1",  
> }  
 
A noter que les groupes ne peuvent être composés que d'**une** unité.  
  
### Le script nécessite que *Mist* soit chargé dans la mission au préalable.
 - Déclencheur de type une fois | Regles : tps sup à 1 seconde | Actions : charger script *Mist.lua*
  
![Chargement_Mist](https://github.com/Queton1-1/DCS-CTLD/assets/13013609/d70269cd-683e-4567-bebf-d498e2c46b24)  

  
### Pour charger *CTLD*, il faut charger le script et les deux sons (dans un pays inutilisé)
- Déclencheur de type une fois | Regles : tps sup à 3 secondes | Actions : charger script *CTLD.lua* ; son au pays *beacon.ogg* ; son au pays *beaconsilent.ogg*
  
![Chargement_CTLD](https://github.com/Queton1-1/DCS-CTLD/assets/13013609/2f807bfe-8f95-409a-88ba-ea55b0ff76c5)  
  

Y'a plus qu'à maintenant!  
  
o7  

Quéton 1-1 | [YouTube](https://www.youtube.com/channel/UCkYOYKrKMwCV-3yASP9gf8Q) | [Twitch](https://www.twitch.tv/queton11) | [DCS UserFiles](https://www.digitalcombatsimulator.com/fr/files/filter/user-is-TheJGi/apply/) | [GitHub](https://github.com/Queton1-1)


