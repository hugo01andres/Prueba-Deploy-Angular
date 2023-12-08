# Prueba-Deploy-Angular

Recordatorio para hacer deploy de una app de angular en Github Pages 2023

´´´ng new frontend-app´´´


´´´ng add angular-cli-ghpages´´´ 

´´´ng build --prod --base-href "https://hugo01andres.github.io/Prueba-Deploy-Angula/" ´´´

Si no funciona intenta asi:

´´´ng build --base-href "https://hugo01andres.github.io/Prueba-Deploy-Angula/" ´´´
Si no funciona intenta asi:
´´´ng build --base-href="https://hugo01andres.github.io/Prueba-Deploy-Angula/" ´´´

Despues:
Se crea una carpeta dist/<app>
´´´npx ngh --dir=dist/frontend-app/browser  ´´´

Listo ver tu aplicacion en github

###No actives ghpages en angular, el cli lo hace solo.
