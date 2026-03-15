# Validación de Usuarios (XML + XSD)

Este proyecto contiene un archivo XML de usuarios y su correspondiente esquema XSD para garantizar la integridad y el formato correcto de los datos almacenados.

## Estructura de Archivos

* usuarios.xml: Documento con los datos de los usuarios.
* usuarios.xsd: Definición de las reglas de validación (esquema).



## Especificaciones de Validación

El archivo `usuarios.xsd` aplica las siguientes restricciones mediante expresiones regulares:

nombreUsuario Empieza con minúscula, longitud total de 3 a 15 caracteres (alfanuméricos). |
email Formato estándar: texto + @ + dominio + extensión. |
telefono 9 dígitos, debe comenzar por 6, 7, 8 o 9. |
codigoPostal Código postal español (01-52 seguido de 3 dígitos). |
contrasena Mínimo 8 caracteres; debe incluir mayúsculas, minúsculas, números y caracteres especiales. |

## Cómo validar

Para comprobar que el archivo `usuarios.xml` cumple con las reglas, puedes utilizar:

 **Editores de código**: VS Code (con la extensión "XML" de Red Hat) marcará errores automáticamente.
