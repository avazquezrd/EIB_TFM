
# Plantilla para TFMs en LaTeX

Plantilla para la edición del **Trabajo Fin de Máster** siguiendo la normativa de la Escuela de Ingeniería de Bilbao (UPV/EHU) y la [guía de expresión de marca de la UPV/EHU](https://www.ehu.eus/documents/10136/3950780/GUIA_EXPRESION_UPV_es.pdf/4d538337-2577-4260-ae02-d0fed29a26b5). 

> *Se recomienda trabajar con [Overleaf](https://es.overleaf.com) y utilizar `LuaLaTex` para la compilación.*

## 📓 Portada

En la parte superior del fichero `main.tex` se pueden editar y personalizar los datos relevantes de la portada, como el título del Máster o los nombres del estudiante y director o directora del TFM. **¡No es necesario tocar nada más!**

```latex
% Título:
\newcommand{\titulo}{<Título del trabajo>}
% Nombre del Máster:
\newcommand{\tituloMaster}{XXXXXXXXXX} 
% Alumno/Alumna:
\newcommand{\estudiante}{<Apellido 1, Apellido 2, Nombre>}
% Dirección del TFG:
\newcommand{\direccion}{<Apellido 1, Apellido 2, Nombre>}
% Departamento:
\newcommand{\departamento}{<Departamento>}
% Curso académico:
\newcommand{\curso}{<Curso>} 
% Fecha:
\newcommand{\fecha}{Bilbao, X de XXXX de 2020}
```

## ⌨️ Bloques de código

Puedes insertar bloques de código usando el entorno `lstlisting` y especificando el lenguaje utilizado para resaltar la sintaxis correctamente. Por ejemplo, para insertar código escrito en `Python`:
```latex
\begin{lstlisting}[language=Python]
	% Aquí va el código
\end{lstlisting}
```

## 🟦 Resaltado de los enlaces

Por defecto, se han desactivado los recuadros para resaltar los enlaces, pero si quieres activarlos solo tienes que ir al fichero `preamble.tex` y eliminar el atributo `[hidelinks]` de `\usepackage{hyperref}`

## ✒️ Tipografías

Se utilizan como tipografías principales **EHUSans** y **EHUSerif**, [tipografías proporcionadas por la UPV/EHU](https://www.ehu.eus/es/web/gizartea/ehu-tipografia). Tal y como marca su propia guía de estilo, EHUSerif debe utilizarse para textos en euskera, y EHUSans para textos en el resto de idiomas, así que si vas a escribir algo en diferentes idiomas recuerda esto.

Como tipografía monoespaciada (utilizada en bloques de código) se ha utilizado **Ubuntu Mono**.

---

## 🧻 Licencia

```
DO I LOOK LIKE I GIVE A SHIT PUBLIC LICENSE 
Version 1, May 2020 

Copyright (C) 2020 Adrián Vázquez

Everyone is permitted to copy and distribute verbatim or modified 
copies of this license document, and changing it is allowed as long 
as the name is changed. 

DO I LOOK LIKE I GIVE A SHIT PUBLIC LICENSE 
TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION 

0. I don't give a shit what you do, just don't bother me with it.

1. I'm done with this shit, maintain it yourself.
```
