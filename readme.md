1.  Vincular una hoja de estilo CSS utilizando el elemento HEAD
    El elemento HEAD se utiliza para contener la información esto no se muestra en la pantalla. Href es la ubicación de la hoja de estilo CSS.
        <head>
        <link rel="stylesheet" href="URL">
        </head>

2.  Vincular tus estilos CSS utilizando la etiqueta style
    El atributo style se puede utilizar en cualquier elemento HTML.
    <style>    
        p {color:red; }    
    </style>    

3.  Vincular una hoja de estilo CSS utilizando @import
    El atributo @import se utiliza en el elemento style para importar otro archivo css en el documento html.
    <style>
        @import (“url”);
    </style>
