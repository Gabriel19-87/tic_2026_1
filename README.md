> # CICD de APPScript
> 
> ## Configuracion del repositorio y codespace
> - Configurar el entorno
> - Instalaciones necesarias
> - Habilitar la google apps script API en tu configuracion de usuario de google
> 
> ## Autenticacion de clasp
> - Archivo de credenciales de usuario
> 
> ## Estructura del proyecto
> - estructura del proyecto
> - Ejemplo de codigo para generar el documento (scr/code.js)
> 
> ```javascript
> // scr/code.js
> function createDocument() {
>   const doc = DocumentApp.create('Documento generado por Apps Script');
>   doc.getBody().appendParagraph('Hola desde Apps Script!');
>   return doc.getId();
> }