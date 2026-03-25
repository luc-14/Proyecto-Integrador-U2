# Proyecto-Integrador-U2
# Animación 2D con Grease Pencil en Blender

Un proyecto de animación tradicional 2D realizado en Blender, implementando la poderosa herramienta Grease Pencil para crear un ciclo de animación cuadro por cuadro.

## Descripción
Este repositorio contiene los archivos y la documentación de una animación 2D creada desde cero. El proyecto abarca desde la configuración inicial del entorno de dibujo hasta la aplicación de efectos de postprocesado como iluminación y sombras, logrando un acabado profesional y dinámico de un personaje (mascota).

## Características Principales
* **Entorno de Trabajo:** Utilización del espacio 2D nativo de Blender [00:00:11].
* **Gestión de Materiales:** Uso independiente de materiales personalizados para las líneas (trazos) y las áreas de color (relleno) [00:01:40].
* **Animación Tradicional:** Secuencia de 8 poses dibujadas y espaciadas cada 3 fotogramas en una línea de tiempo base de 24 frames [00:04:44].
* **Capas Organizadas:** Estructuración del dibujo usando una capa exclusiva para los contornos y otra para los rellenos [00:06:20].
* **Herramientas de Trazado:** Uso de herramientas vectoriales precisas como arcos, curvas, círculos y líneas poligonales [00:06:58].
* **Efectos Visuales (VFX):** Integración de efectos de ribete (Rim Light) y sombras proyectadas para otorgar profundidad a la escena [00:32:12].

## Requisitos
* **Software:** Blender 3.0 o superior (recomendado para asegurar la máxima compatibilidad con las herramientas recientes de Grease Pencil).

## Proceso de Desarrollo
El flujo de trabajo implementado para la creación de esta animación consistió en las siguientes etapas clave:

1. **Configuración y Referencias:** Se inició con un lienzo en blanco (*Grease Pencil Blank*) y se importó una hoja de referencias fotográfica con las 8 poses del ciclo de movimiento [00:03:50]. Se ajustó la opacidad de esta imagen al 50% para facilitar el proceso de calco.
2. **Creación de Materiales:** Se definieron las paletas de colores separando estrictamente las propiedades de *Stroke* (Trazo) y *Fill* (Relleno) para mantener el orden [00:01:40].
3. **Proceso de Trazado (Lineart):** Pasando al modo de dibujo (*Draw Mode*), se trazó cuidadosamente el contorno de cada pose utilizando herramientas de geometría rápida para un trazo limpio [00:07:46].
4. **Aplicación de Color (Relleno):** Tras finalizar las líneas, se procedió a rellenar las áreas cerradas en la capa de relleno correspondiente, asegurando que el color quedara siempre por debajo y contenido en los límites del trazo [00:12:52].
5. **Sincronización y Alineación:** Una vez terminados todos los dibujos, se utilizó el modo edición para ajustar y superponer la posición de todos los fotogramas, centrando la acción y estabilizando el movimiento general de la mascota [00:28:31].
6. **Postproducción e Iluminación:** Se añadieron efectos visuales en tiempo real desde el panel de renderizado. Se configuró un ribete de luz direccional para separar al personaje del fondo [00:32:23], se proyectó una sombra en el suelo virtual [00:32:52] y se personalizó el color de entorno del mundo [00:33:46].

## Créditos y Referencias
El desarrollo técnico y la metodología de este proyecto tomaron como base el tutorial de **STUDIO 5037**:
* **Video de Referencia:** [Blender 2D | Animación con Grace Pencil Paso a Paso](https://www.youtube.com/watch?v=0myBDB1vuq0)
