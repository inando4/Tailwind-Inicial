Intalación mediante CLI: 
npm install tailwindcss @tailwindcss/cli
https://tailwindcss.com/docs/installation/tailwind-cli
- Requisistos: Tener instalado node, comprobar con:      node -v

Version de tailwind 4.0
Extension en visual studio code: Tailwind CSS IntelliSense

TailWind siempre debe estar "escuchando/mirando" los cambios que realizamos en nuestro proyecto, en la documentación oficial lo mencioná y realiza con la línea de código: 

npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch

Modificar las rutas para la carpeta donde se encuentra input.css y en dónde se va a crear el output.css
Para poder visualizar los cambios este código debe estarse ejecutando, para cancelar el proceso: "control + c"




