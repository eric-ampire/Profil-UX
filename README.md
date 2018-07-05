# Profil-UX
![Resultat final](https://github.com/eric-ampire/Profil-UX/blob/master/DeepinScreenshot_select-area_20180705125036.png)

Les composants utiliser dans le fichier XML ne sont pas present par defaut dans Android studio, il faut donc les inclure en ajoutant toutes les dependances dans le fichier build.gradle se trouvant dans le module app
```
// Pour l'image circulaire
implementation 'de.hdodenhof:circleimageview:2.2.0'

// Pour les composants material desing
api 'com.android.support:design:28.0.0-alpha1'

// Pour les autres composants
implementation 'androidx.appcompat:appcompat:1.0.0-alpha1'
```
