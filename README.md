# 🧭 Documentación de uso — **Safe Exam**
## 1. Introducción

**Safe Exam** es un navegador de examen seguro desarrollado en Python con **PySide6**, diseñado para evitar distracciones o trampas durante una evaluación en línea.
El programa abre una ventana a pantalla completa, bloquea menús y accesos externos, y supervisa el comportamiento del estudiante, registrando cualquier intento de salir del modo examen.

El sistema mantiene un **registro (log)** de los eventos relevantes y permite al profesor intervenir en caso necesario mediante combinaciones de teclas especiales.

[Descarga](https://github.com/josedom24/safe_exam/releases/download/1.0.0/safe_exam) la última versión.

## Guía para alumnos

### Antes de empezar

1. Si es necesario, dale permisos de ejecución al fichero: `chmod +x safe_exam`.
2. Cierra todas las demás aplicaciones y ventanas.
3. Descarga el fichero ++config.yaml` que te dará el profesor y ponlo en el mismo directorio que el ejecutable.
4. No uses combinaciones de teclas (Alt+Tab, Ctrl+T, etc.) durante el examen.
5. Una vez abierto, el programa **no permite salir** salvo confirmación explícita.


### Inicio del examen

1. Al abrir el programa, introduce tu **nombre completo**.
2. Haz clic en **“Iniciar examen”**.
3. Verás el navegador a pantalla completa con la página del examen.
4. En la barra superior aparecerán:

   * El título del examen.
   * Tu nombre e IP local.
   * Un botón rojo “🟥 Salir del examen” (solo úsalo cuando termines).


### Durante el examen

* No minimices la ventana ni cambies de aplicación.
* Si accidentalmente pierdes el foco (por ejemplo, presionando Alt+Tab), el sistema te advertirá.
* Tras **tres advertencias**, tu sesión quedará bloqueada y deberás avisar al profesor.


### Fin del examen

1. Cuando hayas terminado, pulsa el botón **🟥 “Salir del examen”**.
2. Confirma la salida cuando el sistema te lo pregunte.
3. El navegador se cerrará y se guardará tu registro.