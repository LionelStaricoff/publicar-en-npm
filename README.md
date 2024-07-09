<div align="center">
  
# Publicar en npm:

1_ Crear cuenta en npm.

2_ Verificar que el nombre de nuestra app no exista en npm.

3_ Crea un Readme.md para explicar como funciona tu proyecto. Preferiblemente tenerlo en GitHub.

2_ Crear archivo para sacar lo que no se necesita: <pre> <code> .npmignore </code> </pre> 

3_ Iniciar el archivo JSON y completar con los datos del proyecto:  <pre> <code> npm init </code> </pre> 

4_ Testear el empaquetado del porgrama con un archov .tgz y verificar todo lo que entra en el empaquetado sea solo lo necesario: <pre> <code> npm pack </code> </pre>

5_ Probamos el archivo con <pre> <code> npm install ruta/del/archivo.tgz  </code> </pre> 

6_ Si todo funciona bien lo desinstalamos: <pre> <code> npm uninstall  </code> </pre> 

7_ Si todo esta correcto Borra el archivo .tgz y publiccar.
Al hacerlo, se generará de nuevo el .tgz, pero esta vez se enviará directamente al registro npm. Al cabo de unos momentos, si no hay ningún problema, recibiremos un correo electrónico de confirmación diciéndonos que el paquete está publicado: <pre> <code>  npm publish  </code> </pre> 

<pre>

  ejemplo json:

{
  "name": "Paint
code",
  "version": "2.1.0",
  "description": "libreria para colorear codigo html",
  "main": "Paint.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "repository": {
    "type": "git",
    "url": "git+https://github.com/LionelStaricoff/paint-code.git#main"
  },
  "keywords": [
    "libreria",
    "pintar",
    "bookshop",
    "paint",
    "code",
    "paint-code",
    "paint-code-html",
    "html"
  ],
  "author": "staricofflionel@gmail.com (https://www.linkedin.com/in/lionel-staricoff/)",
  "license": "ISC",
  "bugs": {
    "url": "https://github.com/LionelStaricoff/paint-code/issues"
  },
  "homepage": " https://github.com/LionelStaricoff/paint-code/tree/main#readme"
}

</pre>


</div>
