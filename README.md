# Trabajo LMSGI JSON & YAML
![Imagen de encabezado](https://cdn.hashnode.com/res/hashnode/image/upload/v1681699906103/4b002a49-bd69-4250-a047-89a131a410a3.png)

## Vamos a discutir sobre las diferencias entre JSON y YAML

## JSON:
[JSON](https://en.wikipedia.org/wiki/JSON) (JavaScript Object Notation) es un lenguaje ligero, basado en texto, que se utiliza para almacenar e intercambiar datos. Se basa en el lenguaje de programación JavaScript, pero es utilizado por una gran variedad de aplicaciones de software, lo que lo convierte en uno de los formatos de almacenamiento de datos más versátiles de la actualidad.

**Características principales:**

- **Compatibilidad**: el lenguaje JSON admite tipos de datos como las cadenas de texto, números, boolean, etc...
- **Fácil interpretación en navegador**: su facilidad para ser interpretado por los navegadores ha hecho que sea utilizado frecuentemente para el intercambio de datos entre servidores y aplicaciones web.
- **Legibilidad**: la estructura de JSON es fácil de entender lo que hace que la lectura y la escritura de este sea sencilla.

## YAML:
[YAML](https://en.wikipedia.org/wiki/YAML)  (Yet Another Markup Language) es un formato de serialización de datos legible por humanos. Aunque en ocasiones se utiliza como un formato de marcado, su diseño principal se enfoca en ser un formato de datos simple y fácil de leer. YAML es especialmente popular en la configuración de aplicaciones y en la definición de archivos de configuración debido a su sintaxis clara y concisa.

**Características principales:**

- **Legibilidad**: Es el mas legible de todos, por encima incluso de JSON.
- **Datos admitidos**: Admite todos los datos mediante colecciones de datos anidados.
- **Control de versiones**: Tiene control de versiones y además es muy fácil de analizar y comprender las diferencias entre las versiones.


## ¿Cuándo usar JSON o YAML?

Gracias al soporte generalizado y la integración con JavaScript, JSON es un formato de serialización de datos más popular que YAML para la mayoría de los casos de uso. JSON se usa ampliamente en comunicaciones de software distribuidas, aplicaciones web, archivos de configuración y API.

Aunque YAML pueda parecer una mejor opción en función de la tipificación de datos y su formato legible por humanos, normalmente se prefiere JSON por motivos de compatibilidad cruzada. Esto se debe a que muchas aplicaciones y servicios ya analizan el formato de datos JSON.

Por otro lado, YAML ha ganado una fuerte presencia en determinados ámbitos de la computación debido a su legibilidad y soporte de comentarios. En particular, YAML es el principal formato de serialización de datos para archivos de configuración en muchas herramientas y servicios de automatización, DevOps e infraestructura como código (IaC). Por ejemplo, YAML se usa a menudo en archivos de Docker y Kubernetes.
