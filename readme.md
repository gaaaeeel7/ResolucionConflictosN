 # Preguntas de control:
 
### 1. ¿Qué ocurre exactamente al hacer un push si alguien ya realizó y subió un cambio en la misma zona del código?
 
Cuando alguien ya ha subido un cambio en la misma parte del código, el push se rechaza porque el repositorio remoto tiene nuevos commits que no están en el equipo local. Git obliga a actualizar primero el proyecto antes de subir nuevos cambios para evitar que se pierda información.

### 2. ¿Por qué Git no decide automáticamente que el último push es el válido?

Git no elige automáticamente el último push porque podría sobrescribir el trabajo de otra persona y borrar código importante. Está diseñado para que el desarrollador decida manualmente qué versión debe quedarse.

### 3. ¿Cómo definirías un “conflicto” en Git basándote en lo que has visto en la herramienta de PyCharm?

Un conflicto en Git ocurre cuando dos personas modifican la misma línea o zona del archivo y el sistema no puede fusionar los cambios de forma automática, por lo que hay que elegir manualmente qué parte del código mantener en herramientas como PyCharm.


### 4. ¿Qué pasos debes seguir en el IDE tras aceptar los cambios para que la resolución sea definitiva en el repositorio remoto?

Después de resolver el conflicto hay que guardar el archivo, hacer un commit del merge y finalmente hacer push al repositorio de GitHub para que los cambios queden registrados de forma definitiva.

### 5. ¿Qué estrategia o flujo de trabajo consideráis más efectivo para evitar conflictos constantes en un equipo grande?

La mejor estrategia es trabajar con ramas independientes para cada funcionalidad, hacer pull frecuentemente para actualizar el código y comunicar los cambios importantes al equipo para evitar modificar la misma parte del archivo.