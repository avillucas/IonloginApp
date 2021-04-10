# IONIC SERVE
`ionic serve`
# CAPACITOR
## Generar iconos y splash screen 
1. `capacitor-resources`
## ANDROID 
1. `ionic capacitor add android`
2. `ionic capacitor copy android`
3. `ionic capacitor run android -l --host=YOUR_IP_ADDRESS`
## Ubicar los dispositivos conectados
1. `adb devices` 
2. `ionic capacitor run android --livereload --external`
3. `ionic capacitor run android --livereload --external --public-host=192.168.0.32`
4. `ionic cap open android`
5. `ionic capacitor build`
6. `ionic capacitor build android` el apk queda en android/app/build/outputs/apk/debug
7. `ionic capacitor build ios`