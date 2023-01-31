# android

## Notification number on icones
* -> parameters -> Home -> Bagde d'icone d'application

## Full backup & restaure with adb
* https://www.moyens.net/android/comment-sauvegarder-vos-donnees-android-avec-adb-sur-ubuntu/
```
apt install adb
adb start-server

# Backup
adb backup -apk -shared -all -f backup-file.adb

# Restore
adb restore backup-file.abb
```

## Samsung rescue mode (mode sans echec)
* https://www.samsung.com/ch_fr/support/mobile-devices/comment-demarrer-mon-telephone-en-mode-securise/  

  => eteindre puis sur l'ecran maintenir sur le bouton eteindre jusqu'a ce que mode sans echec apparaisse  
  Rallumer en maintenant Volume -
  
  => Pour désactiver ce mode, balaie l’écran vers le bas pour ouvrir le panneau des notifications puis appuie sur « Mode sécurisé activé ». Tu peux également éteindre et redémarrer ton smartphone.  
  
  _________________________________________  
  
  => turn off then on the screen hold the turn off button until safe mode appears
   Turn it back on while holding Volume -
  
   => To deactivate this mode, swipe down the screen to open the notification panel then press "Safe mode activated". You can also turn off and restart your smartphone. 
