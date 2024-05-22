# <img src="https://github.com/Alex313031/Notepad-NT/blob/main/winnt_flag.svg" width="48">&nbsp; Notepad &nbsp;<img src="https://github.com/Alex313031/Notepad-NT/blob/main/notepad/notepad.ico" width="42">

Notepad clásico de Windows con fixes y optimizaciones. La traducción al español es de mi autoría.

Optimizaciones y Fixes por [Alex313031](https://github.com/Alex313031/Notepad-NT):

 - Sets de instrucciones [SSE2](https://en.wikipedia.org/wiki/SSE2) y [SIMD](https://en.wikipedia.org/wiki/Single_instruction,_multiple_data).
 - Opción del compilador [/O2](https://learn.microsoft.com/es-es/cpp/build/reference/o1-o2-minimize-size-maximize-speed) para una optimización máxima.
 - Se removieron variables indefinidas del código fuente.
 - Agregado 'Ctrl+Shift+S' para abrir la ventana de "Guardar como".
 - Ahora es posible activar "Ajuste de línea" y "Barra de estado" al mismo tiempo.

Agregados míos:

 - "Seleccionar todo" se puede hacer tanto con `Ctrl+E` como con `Ctrl+A`.
 - "Buscar" se puede hacer tanto con `Ctrl+B` como con `Ctrl+F`.
 - "Reemplazar" se puede hacer tanto con `Ctrl+R` como con `Ctrl+H`.
 - Eliminadas de los menúes opciones que no se usan, tales como "Imprimir", "Configurar página", "Ayuda", "Acerca de".
 - Barra de estado habilitada por defecto.
 - Agregado atajo `Alt+Z` para alternar el "Ajuste de línea".

To-Do:

 - Importante: arreglar el tema de los caracteres especiales.
 - Usar un ícono de menor resolución para alivianar ejecutable.

Funciona desde Windows XP hasta Windows 10. En Windows 11 NO funciona correctamente.

### Compilar

Requiere MSVS 2017 o 2019 *Y* el conjunto de herramientas de Windows XP `v141_xp`.
Este se puede encontrar en el instalador de Visual Studio yendo a "Componentes Individuales" y buscando "Windows XP". Info [aquí](https://learn.microsoft.com/es-es/cpp/build/configuring-programs-for-windows-xp#install-the-windows-xp-platform-toolset).
