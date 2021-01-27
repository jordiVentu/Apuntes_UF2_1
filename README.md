# Apuntes_UF2_1
Apuntes_UF2_1

## Objetivos
objetivos de una prueba eficiente
- probar si el software no hace lo que debe hacer
- probar si el software hace lo que no debe hacer

## FRAMWORK
Permite a un conjunto de desarrolladores realizar un programa con mallor facilidad
- conjunto de practicas y suposiciones
- herraminetas comunes
- bibliotecas

# Pruebas
- **Preubas dinamicas**: Durante la aplicacion en ejecucion permite medir el rendimiento de esta
- **Preuebas estaticas**: Sin ejecutar elcodigo se examina el codigo fuente

## Estrategias de prueba
- **Caja negra**: Probando desde fuera se mide la funcionalidad
- **CAja blanca**: Se examina el codigo fuente para analizar el codigo

### Estrategias de prueba de caja negra
- Se estudia el sistema desde fuera
- No se analiza de forma interna
- Se proporcionan entradas y se estudian las salidas
- Principales tecnicas: PArticiones de equivalencia, valores limite

### Estrategias de prueba de caja blanca
- Se prueba ejecuta el codigo fuente
- Se prueban todas las unidadres (funcion,clase,modulo)
- Se comrpeuban las unidades durante la integracion
- Incluyendo los sub subsistemas
- Principales tecnicas: Cobertura de codigo
- Prueba de bucles

## Tipos de PRUEBAS
- **Funcionales**: Evaluan que se cumplan los requisitos
- **NO funcionales**: Evalua rendimiento, y seguridad

## PRUEBAS FUNCIONALES
- **Preuebas unitarias**: Se utilizar para asegurar que funcione correctamente una unidad de codigo en
espeficifico i saber si en conjunto todas funcionan de forma correcta si que alguna por
separado sin darnos cuenta de algun problema

- **Pruebas de regresion**: consiste en buscar problemas que o fallas con la idea original
del producto

- **Preuebas de integracion**: Aqui se comprueba que todos los componenes que se hacen
por separado en un programa funcionen correctamente unidos

- **Preuebas de humo**: Aqui se comprueba de forma rapida si hay errores evidentes

- **Preuebas del sistema**: Esta tiene la idea de comprobar como se relaciona el sistema
con todo lo que tenga contacto con el mismo

- **Preuebas alfa y beta**: Aqui vamos pasando el desarrollo de la aplicacion pro 
diferentes dases mejorando notoramiente los errores de fase a fase con tal 
de avanzar de forma segura

- **Preuebas de aceptacion**: Esta preuba consiste en analizar el programa para saber si
cumple con lo esperado por el cliente/usuario

## Preubas NO FUNCIONALES
- **Preubas de usabilidad**: Se trata de hacer una preuba con el usuario real para
detectar carencias en el programa

- **Pruebas de rendimiento**: Se trata de analizar como funciona el programa en tiempo
reali i buscar soluciones para optimizar el programa i hacer que vaya con mayor
fluidez

- **Pruebas de stress**: Se trata de poner mucha presion en el programa i comprobar lo
que es capaz de soportar

- **Preubas de seguridad**: Aqui comprobamos si hay posibles errores de seguridad que
puedan perjudicar al usuario

- **Pruebas de compatibilidad**: Aqui cimporbamos la compatibilidad con los 
distintos sistemas con los que funcionara nuestra aplicacion con tal 
de assegurar el producto

- **Preubas de portabilidad**: Aqui hacemos que la aplicacion transmita i reciva datos con 
de garantizar la portabilidad

## Mecanismo de prueba
- **Manual**: Es realizado por los empleados de la empresa o externos
- **Automatico**: Es ejecutado por un software que analiza de forma 
automatica

## Soporte del depurador
- **Puntos de reptura**
- **Ejecucion paso a paso**
- **Analisis de variables**

## Aurimarizacion de pruebas 
 **Un sistema automatizat que verifica el programa(xUnit)**
 
 ## Frameworks para pruebas
**Java:JUnit, TestNG**
 
 ## Caso de prueba
 - **Un caso de prueba de compone de:**
 Una entrada conocida --> Una salida esperada
 
 ## Anotaciones
- **BeforeClass**: el método es invocado antes de iniciar todos los tests
- **AfterClass**: el método es invocado después de finalizar todos los tests
- **Before**: Se ejecuta antes de cada test
- **After**: Se ejecuta después de cada test
- **Ignore**: Los métodos marcados con esta anotación no serán ejecutados
- **Test**: Representa un test que se debe ejecutar
 
## TDD
**Test Driven Development**
- **Escribir las pruebas primero**
- **Refactorizacion**
 
 # FORMAS DE INTEGRACION
 - **Integracio Big bang**
 - **Integracion Descendente**
 - **Integracion Ascendente**
 - **Integracion Continua (CI)**
 
 ## Servidores de integracion continua
 -  **Jenkins**
 - **Bamboo**
 - **TravisCI**
 - **CircleCI**
 
 ## Cobertura del codigo
 - Indica en partentaje el codigo ejecutado
 - Es acomsejable que este cerca del 100%
 - Es mejor simpre ejecutar el 100% de codigo
 - Es posible realizar la cobertura tanto desde el IDE como desde un servicio web apropiado.
 
 # CONTROL DE CALIDAD
 Para poder verder el producto de forma buena es necesario un buen control de calidad
 
 ## CALIDAD DEL PROCESO/PRODUCTO
 - **QA**: ES el conjunto de acciones que implican un buen desarrolo del producto 
 - **QC**: Es un conjunto de actividades para garantizar la calidad 
 de los productos, i se centra en identificar errores del producto

# FACTORES DE CALIDAD

## OPERACION DEL PRODUCTO
- **Correccion:** Correjir la mayor cantidad de fallos en la creacion del producto
- **Fiabilidad:** Garantiza confiabilidad del producto hacia el cliente
- **Eficiencia:** Eficiencia tanto en la producion com para el cliente
- **Seguridad:** Garantizar seguridad tanto como para el producto
- **Facilidad de uso:** Facilitar al usuario usar tu producto
## REVISION DEL PRODUCTO
- **Mantenibilidad:** Darle mantenimiento a tu producto
- **Flexibilidad:** Darle a tu producto la capacidad de adaptarse en la mayoria de situaciones
- **Facilidad de prueba:** Una forma sencilla de que el usaurio sepa si esta interesado en tu producto
## TRANSICION DEL PRODUCTO
 - **Portabilidad:** Poder usar tu producto en diferentes campos
 - **Reusabilidad:** QUe tu producto pueda tener varias funciones para distintos casos
 - **Interoperatividad:** Que tu programa de una forma sencilla pueda intercambiar informacion con otro programa
 
 
 
 
