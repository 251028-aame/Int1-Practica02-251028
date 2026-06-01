# Int-Practica02-251028
---
En esta practica aprenderemos a utilizar las herramientas Git y GitHub para el control de versiones de proyectos de desarrollo de Software, aplicando principios de buenas practicas de documentacion, desarrollo colaborativo y respaldo en la nube del proyecto integrador.


Elaborado por: **Alma Ariadne Maldonado Eslava** \ 
Materia: **proyecto Integrador** \
Docente: **M.T.I Marco Antonio Ramírez Hernández** \
Periodo: *Mayo - Agosto 2026* \

## Comandos Básicos para Maquetado de la Documentación utilizando el estandar de Markdown (.md)
---

Markdown es el estándar utilizado por Git y Github, para estilizar (maquetar), la documentacion de proyectos, lo que permite a usuarios y colaboradores del proyecto entender el contexto y operacion del mismo. 

### 1. Encabezados o Títulos (HEADERS)

Para poder Realizar una buena documentación del proyecto debemos distribuir correctamente los contenidos, para poder delimitar o hacer enfasis (enfatizar), es decir resaltar las secciones mas importantes, podemos utilizar lo siguiente:

**Ejemplos**

# Encabezado nivel 1
## Encabezado nivel 2
### Encabezado nivel 3
#### Encabezado nivel 4
##### Encabezado nivel 5
###### Encabezado nivel 6
####### Encabezado nivel 7 - *El estandar solo permite 6 niveles para titulos, a partir del septimo seran presentados como texto plano (sin estilo)*

### 2. Separadores (SEPARATORS)

Si se desea marcar una separacion visual de los contenidos podemos utilizar una linea horizontal indicando tres caracteres - continuos, en el maquetado

***EJEMPLO***

### Titulo de la seccion
---
texto despues del separador 

### 3. Parrafos (PARAGRAPHS)

son utilizados para presentar grandes secciones que describen detalladamente el contenido de las secciones de la documentacion, detallas procesos, explican codigo o contexto teorico.

***EJEMPLO***

Parrafo 1: Este texto es del parrafo 1 Este texto es del parrafo 1 Este texto es del parrafo 1 Este texto es del parrafo 1 Este texto es del parrafo 1 Este texto es del parrafo 1Este texto es del parrafo 1 Este texto es del parrafo 1 Este texto es del parrafo 1  Este texto es del parrafo 1 Este texto es del parrafo 1  Este texto es del parrafo 1 Este texto es del parrafo 1 Este texto es del parrafo 1 Este texto es del parrafo 1 Este texto es del parrafo 1 Este texto es del parrafo 1 Este texto es del parrafo 1 Este texto es del parrafo 1 

Parrafo 2: este texto es del parrafo 2 este texto es del parrafo 2 este texto es del parrafo 2 este texto es del parrafo 2 este texto es del parrafo 2 este texto es del parrafo 2 este texto es del parrafo 2 este texto es del parrafo 2 este texto es del parrafo 2 este texto es del parrafo 2 este texto es del parrafo 2 este texto es del parrafo 2 este texto es del parrafo 2 este texto es del parrafo 2 este texto es del parrafo 2 este texto es del parrafo 2 este texto es del parrafo 2 este texto es del parrafo 2 este texto es del parrafo 2
 
En caso de que necesitemos alinear el parrafo a **Izquierda**, **derecha**, **centrado** o **justificado**, debemos utilizar una etiqueta ´´´<p>´´´ con la propiedad align y la direccion deseada.

<p align="left"> parrafo alineado a la izquierda parrafo alineado a la izquierda parrafo alineado a la izquierda parrafo alineado a la izquierda parrafo alineado a la izquierda parrafo alineado a la izquierdaparrafo alineado a la izquierda  parrafo alineado a la izquierda  parrafo alineado a la izquierda  parrafo alineado a la izquierda parrafo alineado a la izquierda parrafo alineado a la izquierda  parrafo alineado a la izquierda parrafo alineado a la izquierda parrafo alineado a la izquierda parrafo alineado a la izquierda parrafo alineado a la izquierda parrafo alineado a la izquierda parrafo alineado a la izquierda parrafo alineado a la izquierda

<p align ="center">parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro  parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro  parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro  parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro  parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro

<p align="right">parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha

<p align="justify"> parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado 

### 4.Texto Enfatizado (BOLD, ITALIC, BOLD/ITALIC)


- Texto en Negritas: Para resaltar texto importante que no sea un título por que esto inicialmente están en negrita, debemos encerrar el texto deseado entre dobles asteríscos (**)

Ejemplo: Este texto esta en **negrita**.

- Texto en Cursiva (Itálico): Para hacer referencia a texto utilizando el formato inclinado o itálico bastará con encerrar el texto deseado entre dos asteríscos simples (*).

Ejemplo: Este *texto* estará *inclinado*

- Texto en Cursiva y Negrita: Para lograr esta estilización en la documentación basta como juntar ambas configuraciones, es decir encerramos el texto en un triple asterísco (***)

Ejemplo: *** Este texto esta Negrito e Itálico.***

- Texto Tachado: En algunas ocaciones es necesario dar formato al texto con un efecto de como es incorrecto, generalmente esta idea se transmite por que el texto es tachado, es decir con una línea que lo marca por la mitad. Para lograr este efeto tendremos que encerrar el texto entre una doble tílde de (~)

Ejemplo: Se dice haya no ~~haiga~~.

- Texto Subrayado: En este tipo de formato el texto queda sobre una línea inferior para denotar su relevancia, este formato no tiene una versión rápida en el estándar MARKDOWN, pero dado su similiaridad a HTML podemos utilizae las etiquetas ``` <u> ``` y ``` </u>```.

Ejemplo: El <u>texto</u> debe estar <u>subrayado</u>. 

- Texto en Super Índice: En algunas ocaciones se requiere dar formato a fórmulas estadísticas que requiere potencias entre otras aplicaciones, podemos utilizar el tag de HTML ```<sup>``` y ```</sup>``` para delimitar el formato.

Ejemplo: Para elevar x al cuadrado tendriamos lo siguiente x<sup>2</sup>

- Texto en Subíndice: En el caso de Química se utilizan subíndices para representar formulas, para ello podemos utilizar el formato de texto con la etiqueta HTML ```<sub>``` y ```</sub>```.

Ejemplo: La formula del Agua es H<sub>2</sub>0.


### 5. Listas

Caundo realizamos documentación utilizando el estándar de MARKDOWN, es común que tengamos que listar elementos, requisitos de hardware, requisitos de software o enumerar pasos de cómo el software debe ser instalado paso a paso, por eso debemos ser como crear listas de las cuales hay de 3 tipos : **Ordenadas (Números)** , **Desordenadas (Viñetas)** y **Mixtas (Viñetas y Números)**.

1. Listas Ordenadas

Estas deberán estar enumeradas con un número seguido por un punto y un espacio en blanco para comenzar el listado.

1. PC
2. Wifi
3. Modém
4. Smartphone
6. Smart TV
5. Tablet 

Para reiniciar el conteo se debe poner una línea de texto sin numeralia.

2. Listas Desordenadas 

Estas listas no llevan un númeo, sino una viñeta (simbolo), y suele listar elementos que no requieren un orden específico.

- Pan
- Leche
- Huevo
- Azucar

3. Listas Mixtas

Son aquellas que mezcla ambos elementos

- 3° A DSM
    1. Juan
    2. Pedro
    3. Alejandra
- 3° B DSM
    1. Romina
    2. Daniel
- 3° C DSM
    1. Yair
    2. Liseth
    3. Jeovammy
    4. Erick

### 6. Bloques de Código (CODE BLOCKS) o Citas (BLOCK QUOTES) 

Estos estilos de texto se utilizan para llamar la atencion del lector, en pasos que son importantes, realizar alguna reseña o segmentar líneas de código que se deberán ingresar en una terminal de comandos o líneas de ejecución.


- Cuadro de Citas (Block Quotes)
Son cajas estilizadas en colores grises por defecto con un margén más claro

Ejemplo:

Para listar las carpetas y archivos desde una terminal de comandos en el sistema operativo de Windows debemos usar el comando:

> C:/dir

Despues oprimimos la tecla *Enter*.

Tambien podemos usar texto multilinea

**EJEMPLO:**

Pasos para instalar MySQL
> - Descargar el archivo instalador desde la página oficial www.mysql.com
> - Instalar el Servidor de Bases de Datos
> - Definir el puerto y contraseña para el usuario **root**
> - Inicializar el servicio de bases de datos
> - Conectarnos a la base de datos para verificar que se instaló correctamente


- Bloques de código

Es común que en la documentación del proyecto de software demos al usuario un par de instrucciones de como instalar, configurar, desplegar y testar (pruebas), nuestro producto desarrollado. Por tal motivo el estándar markdown nos permite enfatizar estas instrucciones, simulando estar en una terminal de sistema operativo, para delimitar este código basta encerrarlo en triples carácteres de bacltic (acento o tilde inversa ``` ` ```) 

Para clonar el proyecto ingresa la siguiente instrucción
```
C:\Users\PC-14\Desktop>git clone https://github.com/251028-aame/Int1-Practica02-251028.git
```

A diferencia de los bloques de citas, la tipografía y significado asociado cambian.




### 7. Tablas

En caso de que necesitemos estructurar datos o información relevante para la documentación podremos utilizar el formato de tablas, para lo que tenemos considerar la estructura base de una tabla:

- Usa | para delimitar las columnas
- Usa --- para separar las filas del encabezado

Ejemplo :

|Título 1 | Título 2 | Título 3 | Título 4 |
|---|---|---|---|
|Fila 1, Celda 1 |Fila 1, Celda 2 |Fila 1, Celda 3 |Fila 1, Celda 4|
|Fila 2, Celda 1 |Fila 2, Celda 2 |Fila 2, Celda 3 |Fila 2, Celda 4|
|Fila 3, Celda 1 |Fila 3, Celda 2 |Fila 3, Celda 3 |Fila 3, Celda 4|

### 8. Hipervínculos (Links)

Para poder hacer referencias a documentos internos o externos dentro del repositorio, debemos respetar la siguiente estructura

```
[Texto que el usuario leera](url a donde te dirigirá)"Texto que aparecerá cuando pongas el cursor sobre la liga"
```

Ejemplo

- Ligas externas
[Google](https://google.com)

- Ligas internas
[Acera del Autor](./aboutme.md "Cónoceme más!")