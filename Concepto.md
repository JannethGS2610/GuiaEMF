# Eclipse Modeling Framework (EMF)
<p> El proyecto EMF es un marco de modelado y una instalación de generación de código para construir herramientas y otras aplicaciones basadas en un modelo de datos estructurados. A partir de una especificación de modelo descrita en XMI, EMF proporciona herramientas y soporte de tiempo de ejecución para producir un conjunto de clases de Java para el modelo, junto con un conjunto de clases de adaptadores que permiten la visualización y edición del modelo basada en comandos, y un editor básico. </p>

Fuente: https://www.eclipse.org/emf

![EMF vs Java](/images/1.jpg)

EMF también ha sido un estándar estable para muchas otras tecnologías de modelado. Recomendamos usar EMF para cualquier modelo de datos estructurados que desee crear en Eclipse, especialmente si se almacena, muestra y modifica en interfaces de usuario.

El flujo de trabajo básico de EMF es muy pragmático; se crea y define un modelo en el formato Ecore, que es básicamente un subconjunto de diagramas de clase UML. A partir de un modelo Ecore, puede generar código Java.