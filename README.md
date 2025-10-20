1.- Primero creamos la carpeta en donde vamos a trabajar con:
ionic start Gastos tabs --type=angular

2.- Instalamos las dependencias necesarias

ionic capacitor add android

npm install @capacitor/assets
npx cap sync

ionic build
npx cap copy
npx cap sync android
npm install @capacitor/preferences
npm install @capacitor/camera
3.- Ajustamos el código según lo solicitado
4.- Probamos con ionic serve
<img width="1591" height="445" alt="image" src="https://github.com/user-attachments/assets/9eeaeda4-5bb3-496a-961d-69da110823eb" />
<img width="1456" height="658" alt="image" src="https://github.com/user-attachments/assets/6d5eaf3c-189a-4e47-88fc-badf43bc98e8" />
<img width="1590" height="215" alt="image" src="https://github.com/user-attachments/assets/78a25010-514d-40c5-a084-09854108e6b4" />
5.- Luego probamos en android studio y generamos la apk que se encuentra en el repositorio:
comando: ionic capacitor open android





