# Uso y sintaxis básica del marcado ligero o Markdown para crear el archivo `README.md`

Un archivo README contiene información acerca de otros archivos en un directorio. Es una forma de documentación de software, usualmente en un archivo de texto plano llamado `READ.ME`, `README.TXT`, `README.md` (para un archivo Markdown), `README.1ST` o simplemente `README`. En ocasiones, en español (y sobre todo en la década de 1990) puede venir traducido como `LEEME.TXT`.

El nombre del archivo es generalmente escrito en mayúsculas. En los sistemas Unix-like, generalmente los nombres se escriben en minúscula, y esto hace que en un listado de archivos salga primero el archivo README.

> Informacion extraida de [Wikipedia](https://es.wikipedia.org/wiki/README)

## Cómo escribir un buen README

No hay un estándar sobre cómo escribir un buen README, cada proyecto es diferente y depende de cada uno. Pero hay ciertas partes que sí o sí debería contener un buen README.

1. Nombre: Especificamos cómo se llama nuestro proyecto.

2. Descripción: es donde diremos para qué exactamente es el proyecto, qué problemas resuelve y cualquier información relevante.

3. Instalación: muestra los pasos específicos para instalar el proyecto. Por lo general se muestra un pedazo del código necesario para la instalación.

4. Cómo usar: describe rápidamente casos de uso en los cuales se puede usar el proyecto, además de mostrar funcionalidades.

5. Cómo contribuir: si es un proyecto open source se describe acá la forma en la que deberían crearse las contribuciones.

6. Licencia: muestra la licencia que tiene el proyecto.

Recuerda que tener un buen README permite que los demás colaboradores del proyecto tengan todo el contexto necesario para poder arrancar, usar y crear nuevas funcionalidades.

> Información extraida de [platzi.com](https://platzi.com/clases/1650-prework-2019/21969-como-crear-un-buen-readmemd-y-sintaxis-de-markdown/)

# Sintaxis

## Carácter de escape

Para evitar que algunos parametros tengan efecto como marcado ligero en el código se utiliza la barra invertida (backslash)( \ ).

## Salto de linea

El salto de linea cuando no se utiliza titulo o subtitulo se logra insertando 2 espacios al final de la linea y luego el enter.

## Comando en VS Code para la vista previa de un archivo de etiquetado ligero o Markdown

Comando para ver el archivo de marcado ligero en VSCode en vista previa **Ctrl + Shift + V**

---

## Encabezados

El signo # (numeral) y espacio al inicio permite definir el titulo y entre mayor cantidad de numerales se convierte en subtitulos.

```
# Titulo
## Subtitulo1
### Subtitulo2
#### Subtitulo3
```

Por ejemplo:

# Titulo

## Subtitulo1

### Subtitulo2

#### Subtitulo3

---

## Negrita

Parar esaltar en negrita se utiliza doble asterisco:

```
**Este texto está resaltado en Negrita**
```

Por ejemplo:  
**Este texto está resaltado en Negrita**

---

## Cita

Las citas se logran con el carácter de mayor ( \> ) que:

```
> Esto es una cita -El autor
```

Por ejemplo:

> Esto es una cita -El autor

---

## Links o Enlaces

Entre corchetes agregamos el texto que necesitemos y entre parentesis la url a donde queremos redireccionar.

```
[enlace a google](http://www.google.com)
```

Por ejemplo:  
[Sintaxis Markdown Wikipedia](https://es.wikipedia.org/wiki/Markdown)

---

## Lista de elementos

La lista de elementos se realiza con guiones y en la visualización los toma como puntos:

```
- Elemento 1
- Elemento 2
- Elemento 3
```

- Elemento 1
- Elemento 2
- Elemento 3

---

## Lista de elementos numerados

Se logra anteponiendo el número un punto y un espacio antes de la descripción del elemento.

```
1. Elemento numerado 1
2. Elemento numerado 2
3. Elemento numerado 3
```

Por ejemplo:

1. Elemento numerado 1
2. Elemento numerado 2
3. Elemento numerado 3

---

## Código

Se utiliza el acento grave para identificar código, y corchetes para identificar el lenguaje de programación:

```
`Fragmento de código que se requiera añadir`
```

Por ejemplo:  
`Fragmento de código que se requiera añadir`

![ejemplo_codigo.png](https://github.com/ivanfbj/Documentacion_Personal_de_Marcado_Ligero/blob/master/imagenes/ejemplo_codigo.png)

Por ejemplo:

```[language]
Código en
varias líneas
```

Otro ejemplo:

```bash
pip install pandas
```

---

## Insertar Imagenes

Para insertar imagenes se realizar por medio de la siguiente sintaxis:

```
![texto alternativo si la imagen no carga](Carpeta/archivo.extension)
![texto alternativo si la imagen no carga](Imagenes/noExisteNocarga.png)
```

por ejemplo:  
![texto alternativo si la imagen no carga](https://github.com/ivanfbj/Documentacion_Personal_de_Marcado_Ligero/blob/master/imagenes/NoexisteNoCarga.png)

otro ejemplo:

![texto alternativo si la imagen no carga](https://github.com/ivanfbj/Documentacion_Personal_de_Marcado_Ligero/blob/master/imagenes/vista_previa_README_md.png)

---

## Documentación realizada con base en:

[Sintaxis Markdown Wikipedia](https://es.wikipedia.org/wiki/Markdown)  
[Sintaxis Markdown](https://markdown.es/sintaxis-markdown/#links)  
[Perfil de Github con ejemplo de README.md](https://github.com/anabelisam/readme.md#how-to-clone)

---
