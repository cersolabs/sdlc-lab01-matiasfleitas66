[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/-s1_zvqh)
# SDLC-Lab01

- Requisitos de entrega y aprobacion:
  - Respetar el formato Markdown.
  - Solo se aceptan los trabajos por GitHub Classroom
  - Todas las respuestas deben realizarse en el archivo **README.md** del repositorio asignado..
  - El Trabajo en individual. Si bien se puede realizar de forma grupal, la entrega es siempre ***individual***
  - Defensa individual
  - Respetar las fechas de entraga. No se aceptan las actividades fuera de termino.

> Si surge algún cambio o aclaración adicional, se comunicará durante la clase.

### Actividad 1
Teniendo en cuenta el material de clase, responda las siguientes preguntas:

1. ¿Por qué el desarrollo de software no puede realizarse simplemente comenzando a programar?

   R: Dependiendo del caso es indispensable planear de ante mano lo que se necesita para poder realizar el desarrollo de manera efectiva manteniendo esos requisitos en mente

2. ¿Qué significa que un desarrollo sea dirigido por un plan?

   R: Significa que el desarrollo se realiza guiado por etapas claras, separadas y organizadas

3. ¿Cuáles son las ventajas de utilizar un plan de desarrollo?

   R: Sirve para poder estructurar la base del proyecto de manera fuerte en caso de necesitar mucha complejidad a futuro, para poder usar el tiempo y recursos de manera efectivas sabiendo que es lo necesario a realizar, y para organizar el flujo de trabajo.

4. ¿Qué críticas se hacen a los modelos tradicionales de desarrollo?

   R: Suelen ser criticados por su rigidez y poca adaptabilidad a cambios, lo que los hace ineficientes en casos donde el proyecto sea dinamico y sea necesario iterar de manera rapida

5. ¿Por qué en la práctica muchas organizaciones combinan metodologías ágiles y modelos dirigidos por un plan?

   R: Existen escenarios donde los enfoques tradicionales son efectivos, pero combinarlos con metodologias agiles hacen el trabajo aun mas efectivo debido a la naturaleza del proyecto y del desarrollo de software.


### Actividad 2

| Etapa                         | Descripción                                                                              |
| ----------------------------- | ---------------------------------------------------------------------------------------- |
| Análisis                      | Los analistas llevan a cabo un relevamiento exhaustivo de la organización para identificar sus necesidades y los problemas que deben abordarse mediante un sistema informático. El resultado de este proceso es la elaboración de un documento que, siguiendo reglas y convenciones específicas, capture todos los requerimientos de los usuarios. Asimismo, se deben identificar y tener en cuenta las restricciones y limitaciones pertinentes |
| Diseño                        | Se elabora el diseño de una solución informática que aborde los problemas identificados, teniendo en cuenta los requerimientos obtenidos en la fase anterior y respetando las restricciones establecidas. Se genera una documentación detallada y técnica que permita a los programadores construir el código de manera efectiva. |
| Codificación                  | Los programadores llevan a cabo la etapa de codificación siguiendo las especificaciones del diseño, donde construyen el código del software empleando un lenguaje de programación determinado |
| Prueba                        | La etapa de prueba se encarga de identificar posibles errores en el sistema antes de su puesta en uso, con el objetivo de reportarlos y corregirlos. |
| Puesta en marcha / Despliegue | Se realiza la instalación del programa en las computadoras del cliente y se proporciona capacitación a los usuarios para que puedan utilizar eficientemente el nuevo software. |

* Luego responda:
  * ¿En qué etapa se obtienen los requerimientos del sistema?
    
    R: Se capturan por los analistas en la etapa "Analisis"
  * ¿En qué etapa se construye el programa?

    R: Se construye por los programadores en la etapa "Codificacion"
  * ¿Cuál es el objetivo principal de las pruebas?
    
    R: Encontrar y arreglar errores para "endurecer" el programa
### Actividad 3
Ordene las siguientes etapas según corresponda al modelo lineal secuencial:
- Codificación
- Prueba
- Diseño
- Despliegue
- Ingeniería de requerimientos

---

R:
- Ingeniería de requerimientos
- Diseño
- Codificación
- Prueba
- Despliegue

---

- Luego responder:
  * ¿Qué problema puede surgir si hay un error en una etapa inicial?
    
    R: El problema podria convertirse en un error grave dificil de arreglar si no se maneja temprano en el diseño o las pruebas del proyecto
  * ¿Por qué este modelo puede ser problemático cuando los requerimientos cambian?

    R: Al estar estructurado linearlmente, si los requerimientos cambian se debe empezar de una etapa temprana para volver a seguir el plan
### Actividad 4
Complete la siguiente tabla.
| Modelo      | Característica principal | Cuándo conviene usarlo |
| ----------- | ------------------------ | ---------------------- |
| Cascada     | Es simple, sencillo y probado. Mejor que no usar ninguno | Debido a sus desventajas, conviene usarlo cuando se descarten los otros modelos si es que no son mas convenientes para el proyecto a desarrollar |
| Incremental | Requiere menos personal concurrente y los recursos se asignan mejor en el tiempo | En casos donde sea conveniente construir y entregar el sistema en partes |
| Prototipos  | Se enfoca en mostrar "maquetas" no funcionales al cliente para obtener mas requerimientos o cambios | En casos donde sea conveniente o util que el cliente pueda comprender y visualizar como funcionara el proyecto durante o antes del desarrollo |
| Espiral     | Durante el desarrollo se mantienen en cuenta activamente diferentes partes del proyecto como la seguridad | En casos donde sea conveniente entregas sucesivas, o, el proyecto viva en un entorno riesgoso y con mucha incertidumbre |
| RAD         | El software se divide en partes que puedan ser desarrolladas por varios equipos que trabajan en forma concurrente | En casos donde sea conveniente generar aplicaciones con mayor velocidad que los desarrollos tradicionales |

- Responder:
  - ¿Qué modelo es más adecuado cuando existen muchos riesgos en el proyecto?

    R: El modelo espiral.
  
  - ¿Qué modelo ayuda a comprender mejor los requerimientos del usuario?

    R: El modelo de prototipos.
    
### Actividad 5 – Caso práctico
Una empresa quiere desarrollar un sistema de ventas para un pequeño comercio.

**Características del proyecto:**
- Sistema relativamente pequeño
- Pocos usuarios
- Requerimientos claros
- Tiempo limitado

**Preguntas**

- ¿Qué modelo de desarrollo recomendaría? 

  R: 
- Justifique su respuesta.

  R:
- ¿Qué etapas principales tendría el desarrollo?

  R:

### Actividad 7 – Verdadero o Falso
Indique si las siguientes afirmaciones son Verdaderas (V) o Falsas (F). ***marcar con x la verdaderas, dejar en blanco las falsas***

1. [ ] El modelo en cascada permite cambios constantes en los requerimientos.
2. [ ] El modelo incremental entrega el sistema en varias versiones.
3. [ ] Un prototipo se utiliza para comprender mejor los requerimientos.
4. [ ] El modelo RAD busca reducir los tiempos de desarrollo.
5. [ ] El modelo en espiral incorpora el análisis de riesgos.
