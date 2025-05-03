##  Proyecto final de moduli  
Este proyecto forma parte del módulo de programacion del diplomado para ciencia de datos, impartido en la **Facultad de Ciencias** de la **UNAM** este se encuentra en el [repositorio  de GitHub](https://github.com/Fernando-Alvarado/colaboracion-git-equipo-11).


## Introducción / Objetivo del Proyecto  
El propósito de este proyecto es emplear técnicas de programación usando R para analizar datos reales, obtener conclusiones, evaluar si las acciones se correlacionan con los datos y generar interpretaciones significativas, así como proponer posibles planes de acción.



## Colaboradores

- **Fernando Alvarado Palacios**: [GitHub](https://github.com/Fernando-Alvarado)  [linkedin](https://www.linkedin.com/in/fernando-alvarado-37415b216/) 
- **Bryant Canseco Hernández**: [Nombre de la organización]  
- **Diego Gómez Santiago**: [Nombre de la organización]  


## 📈 Métodos Utilizados  
- Estadística inferencial  
- Estadística descriptiva
- Modelo no parametricos y de regresion. 
- Visualización de datos  y datos faltantes


##  🔧 Tecnologías  
- R  
- Rmarkdown

![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
![RMarkdown](https://img.shields.io/badge/RMarkdown-2C3E50?style=flat&logo=r&logoColor=white)


## 📊 Descripción del Proyecto  

** Descripcion tablas***

** Descricion del proyecto **

Este proyecto buscaba hacer una analisis de los jugadores de Beisball ......
......

** Descripcion preguntar Bryant**

-------------------------------------------------------------------------------------

Una de las preguntas que nos hicimos fue:

> **¿En promedio, un jugador que asiste a la universidad tiene un primer salario más alto que uno que no asiste?**

![](https://github.com/Bryantcanseco/diplo-modulo3-equipo-11/blob/main/Images/fer1.png)

La conclusión fue algo inesperada. Aunque comúnmente se espera que, a mayor nivel educativo, el salario inicial sea más alto, en el caso de los deportes esto no necesariamente se cumple.  
Nuestro análisis mostró que los jugadores universitarios, en promedio, reciben un **primer salario más bajo** que aquellos que no asistieron a la universidad.

Otra pregunta que nos interesó fue:

> **¿Existe una diferencia entre los salarios de bateadores y lanzadores?**

![](https://github.com/Bryantcanseco/diplo-modulo3-equipo-11/blob/main/Images/fer2.png)

Encontramos una **clara ventaja para los lanzadores**, quienes tienen, en promedio, un mayor sueldo inicial.  
Sin embargo, sus carreras tienden a ser de menor duración debido a que su posición es más **lesiva**, especialmente por el alto número de lesiones en el hombro.


![](https://github.com/Bryantcanseco/diplo-modulo3-equipo-11/blob/main/Images/fer3.png)


En otro tema, nos centramos en el análisis de la entrada al **Salón de la Fama**, donde observamos que en algunas décadas fue relativamente más fácil que los beisbolistas lograran ser aceptados.  
Además, la **experiencia previa** al momento de la postulación también influye significativamente en la probabilidad de ser inducido.

-------------------------------------------------------------------------------------
** Descripcion tablas Diego **


2. **Titulo**  
   

  **imagenes graficas**

3. **Titulo**  
   

  **imagenes graficas**


También se aplicaron procesos de limpieza, visualización y modelado básico para extraer conclusiones útiles de cada conjunto de datos.

## 💡 Necesidades del Proyecto  
- Desarrollo frontend  
- Estadísticas descriptivas  
- Limpieza y procesamiento de datos  
- Modelado estadístico  
- Redacción y documentación  

## Cómo Empezar  

Descarga Proyecto

```bash
git clone https://github.com/Fernando-Alvarado/colaboracion-git-equipo-11.git
```

## ▶️ Ejecución del Proyecto

1. Abrir `proyecto_final.Rmd` en RStudio.
2. Ejecutar en la terminal de R ` rmarkdown::render("proyecto_final.Rmd")`
3. Se generará automáticamente `proyecto_final.html` como salida.


## 📁 Organizacion del proyecto 

```text
proyecto/
├──  📂 Data/                              # Datos utilizados en el análisis
├──  📂   proyecto_final_files/     # Imágenes generadas por el Rmd
│        └── figure-html/
├──  📂   Image                          #Imagenes para el readme
├── .gitignore                              # Archivos ignorados por Git
├──  🅡 proyecto_final.Rmd               # Código fuente en R Markdown
└── README.md                          # Documentación del proyecto
```

## ⚙️ Requisitos

- Tener instalado R (versión ≥ 4.3.2)
- Tener RStudio (opcional pero recomendado)
- Instalar los siguientes paquetes de R:
  - `tidyverse`
  - `readr`
  - `dplyr`
  - `ggplot2`
  - `naniar`
