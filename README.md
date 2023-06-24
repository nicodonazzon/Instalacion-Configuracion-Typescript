# Instalacion-Configuracion-Typescript
En este apartado les voy a explicar como instalar y configurar un entorno de desarrollo para TypeScript.

Es importante destacar que existen muchos métodos para agregar TypeScript a sus proyectos, nostros a lo largo de curso utilizaremos el primero que les muestro a continuación:

* Mediante el módulo npm de NodeJs y Visual Studio Code 

1. Instalar Visual Studio Code: https://code.visualstudio.com/download
2. Instalar la última versión de Nodejs desde su página oficial: https://nodejs.org/es/download.
3. Una vez instalado nodejs, creamos una carpeta para el proyecto vacío y lo abrimos con VS Code.
4. Con la terminal de IDE escribimos npm install typescript --save-dev apuntando a la ruta de la carpeta del proyecto.

Con esto ya estarían las bases para empezar a desarrollar en TypeScript, más adelante en el curso explicaré como personalizar el proyecto y sus formas de compilar a JavaScript según la configuración del archivo tsconfig.json.

* Otra alternativa más avanzada  que no se entratá mucho en detalle en este curso pero lo dejo de manera educativa es para casos en los que se desee utilizar Visual Studio 2022 en vez de Visual Studio Code y utilizar TypeScript junto a otras técnologías
como ASP.NET.

Para esto, en la pestaña Herramientas seleccionamos el manager:
![image](https://github.com/nicodonazzon/Instalacion-Configuracion-Typescript/assets/60930400/cd8c7a51-1d3d-4693-ae49-f619e4860bf5)

Lo abren, buscan TypeScriptt MSBuild y lo instalan en su proyecto de Visual Studio:

![image](https://github.com/nicodonazzon/Instalacion-Configuracion-Typescript/assets/60930400/e05a56ab-56dd-4e90-a429-7797b1a3bcdb)


¡Listo ya está todo configurado para empezar a desarrollar en TypeScript!

