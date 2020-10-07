# Comandos o Códigos para escribir el informe
#
##  Lo Básico
### Letras en negrita
  ```
  \textbf{texto en negrita:}
  ```
### Salto de linea
Se puede hacer de 2 formas:
  ```
  \\
  ```
  o
  ```
  \newline
  ```
### Salto de pagina  
```
\newpage
```
#### Añadir Capítulo
```
\chapter[lo que va al indice]{lo que se muestra en el desarrollo}
```
ej: Capitulo I

Se registra automáticamente en el indice
#### Nueva Sección
```
\section
```
ej: Seccion 1.1

##### Para una subsección
#
```
\subsection
```
ej: Seccion 1.1.1

##### Nota: Si se desean mas subsecciones, por ejemplo, seccion 1.1.1.1, se debe importar librerias
#
## Listar elementos
#### Listar sin ordenar
```
\begin{itemize}
    \item elemento 1
    \item elemento 2
    \item elemento 3
\end{itemize}
```

#### Listar ordebados alfabeticamente
```
\begin{sortedlist}
    \sortitem{ elemento 1 }
    \sortitem{ elemento 2 }
    \sortitem{ elemento 3 }
\end{sortedlist}
```
## Incluir imagenes
```
\begin{figure}[H]
    \centering
    \includegraphics[angle=0, scale=0.8]{./images/nombreImagen}
    \caption{Descripcion de la imagen.}
    \label{fig:etiquetaImagen}
\end{figure}
```
##### Para referenciar a la figura se utiliza el label, por ejemplo:
... se aprecia en la siguiente figura ```\ref{fig:etiquetaImagen}```

### 

