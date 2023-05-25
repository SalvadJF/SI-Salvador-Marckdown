# INDICE

![Logo Markdown](/imagenes/logo.png)

## 1. ¿Qué es Markdown?
## 1.1 Etiquetas básicas de Markdown
### 1.1.1 Encabezados.
### 1.1.2 Negrita y cursiva.
### 1.1.3 Resaltar un comando.
### 1.1.4 Bloque de código.
### 1.1.5 Imágenes.
### 1.1.6 Listas desordenadas anidadas.
### 1.1.7 Listas ordenadas anidadas.
### 1.1.8 Comentarios.
### 1.1.9 Ecuaciones matemáticas.
## 2. Referencias.
---

# Taller de introducción a Markdown

## 1. ¿Qué es Markdown?  

**Markdown** es un _lenguaje de marcado ligero_ que permite escribir texto con formato fácilmente legible y convertirlo en HTML válido. Fue creado por **John Gruber** y **Aaron Swartz** en 2004 con el objetivo de ser fácil de leer y escribir.  

## 1.1 Etiquetas básicas de Markdown  


### 1.1.1 Encabezados.

Los _encabezados_ en **Markdown** se crean utilizando el _símbolo de numeral (#)_ seguido de un espacio y el texto del encabezado.  
El número de numerales indica el nivel de **jerarquía** del encabezado, siendo un numeral para el encabezado de nivel 1, dos numerales para el encabezado de nivel 2, y así sucesivamente hasta seis niveles.

**Ejemplo:**

```
# Encabezado de nivel 1
## Encabezado de nivel 2
### Encabezado de nivel 3
```

### 1.1.2 Negrita y cursiva.

Para aplicar formato de **negrita** a una palabra o frase, se deben utilizar dos asteriscos (*) o dos guiones bajos (_) antes y después del texto.  
Para aplicar formato de _cursiva_ se deben utilizar un asterisco o un guión bajo antes y después del texto.

**Ejemplo:**

```
**Texto en negrita**
_Texto en cursiva_
```

### 1.1.3 Resaltar un comando.

Para _resaltar_ un comando en **Markdown**, se puede utilizar el **acento grave (`)** alrededor del comando.

**Ejemplo:**

```
`comando`
```

### 1.1.4 Bloque de código.

Para mostrar un _bloque_ de código en **Markdown**, se deben utilizar **tres acentos graves (`)** antes y después del bloque de código.

**Ejemplo:**

\```
bloque de código
\```

### 1.1.5 Imágenes.

Para insertar una _imagen_ en **Markdown**, se utiliza la siguiente sintaxis:

```
![Texto alternativo](URL de la imagen)
```

**Ejemplo:**

```
![Logo de IES Doñana](https://pro.iesdonana.org/assets/logo.png)
```
**Ejemplo en funcionamiento:**  

![Logo de IES Doñana](https://pro.iesdonana.org/assets/logo.png)

### 1.1.6 Listas desordenadas anidadas.

Las _listas desordenadas_ anidadas se crean utilizando **cuatro espacios de indentación antes del guion (-) o asterisco (*)** que inicia cada ítem de la lista.

**Ejemplo:**

```
- Item 1
    - Subítem 1
    - Subítem 2
- Item 2
    - Subítem 3
```

### 1.1.7 Listas ordenadas anidadas.

Las _listas ordenadas anidadas_ se crean utilizando **cuatro espacios de indentación antes del número seguido de un punto (1., 2., 3., etc.)** que inicia cada ítem de la lista.

**Ejemplo:**

```
1. Item 1
    1. Subítem 1
    2. Subítem 2
2. Item 2
    1. Subítem 3
```

### 1.1.8 Comentarios.

En **Markdown**, se pueden agregar _comentarios_ utilizando la sintaxis **`<!-- Comentario -->`**.  
Estos comentarios **no se mostrarán** en la visualización del archivo final.

**Ejemplo:**

```
<!-- Este es un comentario en Markdown -->
```

### 1.1.9 Ecuaciones matemáticas.

Para escribir _ecuaciones matemáticas_ en **Markdown** se utiliza la sintaxis de LaTeX.  
Las ecuaciones **se encierran entre dos signos de dólar ($)**.

**Ejemplo:**

```
$E = mc^2$
```
**Ejemplo en funcionamiento:**  

$E = mc^2$  


## 2. Referencias.

- Tutorial en Español: [Enlace al tutorial](https://markdown.es/)
- Documentacion Oficial: [Enlace a la documentacion](https://www.markdownguide.org/getting-started/)
