Para poder ejecutar tailwind es necesario tener Node ejecutado para poder indicarle el paquete del framework para implementar. 

Si no se requieren de configuraciones avanzadas, se puede usar el siguiente comando:
 
 npm init -y

Una vez instalado, en la documentación oficial del framework se va indicando paso a paso como ir instalandolo, para ello el primer paso será instalarlo mediante el siguiente comando:

npm install tailwindcss @tailwindcss/cli

Una vez instalado la versión de cliente solo es necesario indicarle al html una direccion de un css de salida y un css de entrada, para ello en la carpeta de estilos se puede crear el archivo de entrada y salida, indicandole al html que genere los estilos automaticamente con el siguiente comando:
 npx @tailwindcss/cli -i ruta relativa entrada -o ./src/ruta relativa salida --watch

Hecho eso, se pueden consultar diferentes adaptaciones de empresas para poder ejecturar el codigo tailwind con más afcilidad, por ejemplo en este caso se ha decidio implementar DaisyUI (https://daisyui.com/), que facilita que los diseños tengan responsividad más facil de manejar. Se puede instalar por npm pero tambien se puede adjuntar como enlace dentro de cada archivo a implementar, como por ejemplo con la siguiente linea:

<link href="https://cdn.jsdelivr.net/npm/daisyui@latest/dist/full.css" rel="stylesheet" type="text/css" />

Otra implementación de empresa a utilizar será