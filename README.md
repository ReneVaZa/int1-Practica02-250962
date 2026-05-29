# Int1-Practicfa02-MATRICULA
---
En esta practica aprenderemos a utilizar las herramientas Git y GitHub para el control de versiones de proyectos de desarrollo de software, aplicando principios de buenas practicas en Documentacion, Desarrollo Colaborativo y Respaldo en la Nube del Proyecto Integrador


Elaborado por: **Rene Vargas Zarate** \
Materia: **Proyecto Integrador** \
Docente **M.T.I Marco Antonio Ramirez Hernandez** \
Periodo: *Mayo - Agosto 2026* \

## Comandos Basicos para Maquetado de la Documentacion utilizando el estandar de Markdown (.md)
---

Markdown es el estandar utilizado por Git y GitHub, para estilizar (maqueta) la documentacion de proyectos, lo que permite a usuarios y colaboradores del proyecto entender el contexto y operacion del mismo

### 1. Encabezados o Titulos (Headers)

Para poder realizar una buena documentacion del proyecto debemos distribuir correctamente los contenidos, para poder delimitar o hacer enfasis (enfatizar), es decir resaltar las secciones mas importantes, podemos utilizar lo siguient:

**Ejemplos**

# Encabezado de Nivel 1
## Encabezado de nivel 2
### Encabezado de nivel 3
#### Encabezado de nivel 4
##### Encabezado de nivel 5
###### Encabezado de nivel 6
####### Encabezado de nivel 7
septimo seran presentado como texto plano (sin estilo)

**Ejemplo**

### 2. Separadores (Separators)

Si se desea marcar una separacion visual de los contenidos podemos utilizar una linea horizontal indicando tres caracteres - continuos, en el maquetado

**Ejemplo**

### Titulo de la seccion
---
parrafo 1: Este texto es del parrafo 1 Este texto es del parrafo 1 Este texto es del parrafo 1 Este texto es del parrafo 1 Este texto es del parrafo 1 Este texto es del parrafo 1 Este texto es del parrafo 1 Este texto es del parrafo 1 Este texto es del parrafo 1 Este texto es del parrafo 1 Este texto es del parrafo 1 Este texto es del parrafo 1 Este texto es del parrafo 1 Este texto es del parrafo 1

parrafo 2: Este texto es del parrafo 2 Este texto es del parrafo 2 Este texto es del parrafo 2 Este texto es del parrafo 2 Este texto es del parrafo 2 Este texto es del parrafo 2 Este texto es del parrafo 2 Este texto es del parrafo 2 Este texto es del parrafo 2 Este texto es del parrafo 2 Este texto es del parrafo 2 Este texto es del parrafo 2 Este texto es del parrafo 2 Este texto es del parrafo 2

en caso de que necesitemos alineat el parrafo a **izquierda**, **derecha**, **central** o
**justificar** deberemos utilitar una etiqueta <p> con la propiedad aling y direccion deseada

<p align="left">parrafo alineado parrafo alineado parrafo alineado parrafo alineado parrafo alineado parrafo alineado parrafo alineado parrafo alineado parrafo alineado parrafo alineado parrafo alineado parrafo alineado parrafo alineado parrafo alineado parrafo alineado parrafo alineado
<p align="center">parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro
<p align="right">parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha

<p align="justify">parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado


### 4. Enfatizado de texto

- Texto en negritas: para resaltar texto importante que no sea un titulo por questo inicialmente esta en nedritas, debemos encerrar el texto desdeando entre dobles asteriscos (**)

ejemplo: este texto esta en **Negrita**

- Texto en cursiva (Italico): Para hacer referancia a texto utilizando el formato inclinado o italico bastara con encerrar el texto deseado entre dos asteriscos simples (*)

ejemplo: este *texto* estara *inclinado*

- Texto en cursiva y negrita: Para lograr esta estilizacion en la documentacion basta con juntar ambas configuraciones, es decir encerramos el texto en un triple asterisco (***)

ejemplo: ***Este texto esta negrito e italico***

-texto tachado: En algunas ocaciones es necesario dar formato al texto con un efecto de como es incorrecto, generalmente esta idea se transmite por que el texto esta tachado, es decir con una linea que lo marca por la mitad. Para lograr este efecto tendremos que encerrar el texto entre una doble tilde de (~)

ejemplo: Se dice haya no ~~haiga~~

-Texto subrayado: En este tipo de formato el texto queda sobre una linea inferior para detonar su relevancia, este formato no tiene un version rapida en el estandar MARKDOWN, pero dado su similiaridad a HTML podemos utilizar las etiquetas ```<u>``` y ```</u>```

ejenplo: El <u>texto</u> debe estar <u> subreayado</u>

- texto en super indice: en algunas ocaciones se requiere dar formato a formulas estadisticas que requiere potencias entre otras aplicaciones, podemos utilizar el tag de HTML ```<sup>``` y ```</sup>``` para delimitar el formato

ejemplo: Para elevar x al cuadrado tendiamos lo siguiente x<sup>2</sup>

-Texto subindice: En el caso de Quimica se utiliza subindices para representar formulas, para ello podemos utilizar el formato de texto con la etiqueta HTML ```<sub>``` y ```</sub>```

ejemplo: La formula del agua es H<sub>2</sub>O



### 5. Listas
Cuando realizamos documentacion  utilizando el estandar de MARKDOWN, es comun que tengamos que listar elementos, requisitos de hardware, requisitos de softwarre o enumerar pasos de como el software debe ser instalado paso a paso, por eso debemos saber como crear listas de las cuales hay 3 tipos: **Ordenadas (numeros)**, **Desordenadas (viñetas)** y **Mixtas (Viñetas y numeros)**

1. Listas ordenadas

Estas deberan estar enumeradas con un numero seguido por un punto y un espacio en blanco para comenzar con el listado

1. pc
2. wifi
3. modem
4. smartphone
6. smart tv
5. tablet

2. Listas desordenadas

Estas listas no llevan un numero, sino una viñeta (simbolo), y suele listar elementos que no requieren un orden especifico

- pan
- leche
- huevo
- azucar

3. Listas mixtas

son aquellas que mezclan ambos elementos

- 3° A DSM
   1. juan
   2. Pedro
   3. Alejandro 
- 3° B DSM
   1. Romina
   2. Daniel
- 3° C DSM
   1. Yahir
   2. Liseth
   3. Jeovany
   4. Erick


### 6. Bloque de codigo(Code blocks) o citas(Blok Quotes)

estos estilos de texto se utilizan para llamar la atencion del lector, en pasos que son importantesm realizar alguna reseña o segmentar lineas de codigo que se deberan ingresar en una terminal de comandos o lineas de ejecucion

- Cuadro de citas (Block Quotes)

Son cajas estilizadas en colores grises popr defecto con un nargen mas claro

ejemplo: 
Para listar las carpetas y archivos desde una terminal de comandos en el sistema operativo de windows debemos usa el comando:

> C: /dir

Despues oprimimos la tecla *enter*

Tambien podemos usar texto multilinea

ejemplo
Pass para instalar MySQL
> - Descargar el archivo instalador desde la pagina oficial www.mysql.com
> - Instalar el servidor de bases de datos
> - Definir el puerto y contraseña para el usuario **root**
> - Inicializar el servicio de bases de datos
> - Conectamos a la base de datos para veificar que se instalo correctamente
 