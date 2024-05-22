# <img src="https://github.com/Alex313031/Notepad-NT/blob/main/winnt_flag.svg" width="48">&nbsp; Notepad &nbsp;<img src="https://github.com/Alex313031/Notepad-NT/blob/main/notepad/notepad.ico" width="42">

Notepad clásico de Windows con fixes y optimizaciones. La traducción al español es de mi autoría.


Optimizaciones & Fixes por [Alex313031](https://github.com/Alex313031/Notepad-NT):

 - Sets de instrucciones [SSE2](https://en.wikipedia.org/wiki/SSE2) y [SIMD](https://en.wikipedia.org/wiki/Single_instruction,_multiple_data).
 - Opción del compilador [/O2](https://learn.microsoft.com/es-es/cpp/build/reference/o1-o2-minimize-size-maximize-speed) para una optimización máxima.
 - Se removieron variables indefinidas del código fuente.
 - Agregado atajo ´Ctrl+Shift+S´ para abrir la ventana de "Guardar como".


Mejoras por aletondaX:

 - Traducción al Español.
 - "Seleccionar todo" se puede hacer tanto con `Ctrl+E` como con `Ctrl+A`.
 - "Buscar" se puede hacer tanto con `Ctrl+B` como con `Ctrl+F`.
 - "Reemplazar" se puede hacer tanto con `Ctrl+R` como con `Ctrl+H`.
 - Eliminadas de los menúes opciones irrelevantes, tales como "Imprimir", "Configurar página", "Ayuda", "Acerca de".
 - Barra de estado habilitada por defecto.
 - Agregado atajo `Alt+Z` para alternar el "Ajuste de línea".


To-Do:

 - Importante: arreglar el tema de los caracteres especiales.
 - Usar un ícono de menor resolución para alivianar ejecutable.
 - Remover todo el código relacionado a la impresión.

Funciona desde Windows XP hasta Windows 10. En Windows 11 NO funciona correctamente.


### Compilar

Requiere MSVS 2017 o 2019 *Y* el conjunto de herramientas de Windows XP `v141_xp`.
Este se puede encontrar en el instalador de Visual Studio yendo a "Componentes Individuales" y buscando "Windows XP". Info [aquí](https://learn.microsoft.com/es-es/cpp/build/configuring-programs-for-windows-xp#install-the-windows-xp-platform-toolset).
