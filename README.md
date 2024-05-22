# <img src="https://github.com/Alex313031/Notepad-NT/blob/main/winnt_flag.svg" width="48">&nbsp; Notepad &nbsp;<img src="https://github.com/Alex313031/Notepad-NT/blob/main/notepad/notepad.ico" width="42">

Notepad clásico de Windows con fixes y optimizaciones. La traducción al español es de mi autoría.

Optimizaciones y Fixes por [Alex313031](https://github.com/Alex313031/Notepad-NT):

 - Sets de instrucciones [SSE2](https://en.wikipedia.org/wiki/SSE2) y [SIMD](https://en.wikipedia.org/wiki/Single_instruction,_multiple_data).
 - Opción del compilador [/O2](https://learn.microsoft.com/es-es/cpp/build/reference/o1-o2-minimize-size-maximize-speed) para una optimización máxima.
 - Se cambió el ícono por el clásico de Windows NT.
 - Se removieron variables indefinidas del código fuente.
 - Se puede hacer la build con MSVS 2017/2019.
 - Agregado 'Ctrl+Shift+S' para abrir la ventana de "Guardar como".
 - Ahora es posible activar "Ajuste de línea" y "Barra de estado" al mismo tiempo.

Funciona desde Windows XP hasta Windows 10 (en Win11 no se muestra correctamente)

### Compilar

Requiere MSVS 2017 o 2019 *Y* el conjunto de herramientas de Windows XP `v141_xp`.
Esta se puede encontrar en el instalador del Visual Studio yendo a "Componentes Individuales" y buscando "Windows XP". Info [aquí](https://learn.microsoft.com/es-es/cpp/build/configuring-programs-for-windows-xp#install-the-windows-xp-platform-toolset).
