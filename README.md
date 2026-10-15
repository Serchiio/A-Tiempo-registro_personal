# A Tiempo

**A Tiempo** es un programa para Windows que controla la asistencia del personal: registra la entrada y la salida de cada empleado, calcula llegadas tarde, horas extra, domingos y festivos, y genera el reporte en Excel. Funciona sin internet y los datos se guardan solo en el computador de la empresa.

## Descargar

Ve a la sección [**Releases**](../../releases/latest) y baja el instalador que corresponda a tu Windows:

| Archivo | Para |
|---|---|
| `Instalador_ATiempo_x64.exe` | Windows de 64 bits (lo normal en equipos de los últimos años) |
| `Instalador_ATiempo_x86.exe` | Windows de 32 bits y Windows 7 |

Cada release trae un archivo `SHA256SUMS.txt` para comprobar que la descarga no se corrompió.

> Si Windows muestra el aviso de SmartScreen, pulsa **Más información › Ejecutar de todas formas**.

## Así se ve

*Capturas con datos de ejemplo (empleados inventados).*

### Para todos los gustos: modos de apariencia

Claro, oscuro, **alto contraste** (para leer sin esfuerzo) o **personalizado** con tus dos colores. Además puedes elegir el color de acento y el tamaño de la letra. El programa ajusta solo los colores para que el texto siempre se lea bien.

<table align="center">
  <tr>
    <td align="center"><img src="docs/capturas/01_menu_principal.png" width="230" alt="Modo claro"><br><sub><b>Claro</b></sub></td>
    <td align="center"><img src="docs/capturas/02_menu_oscuro.png" width="230" alt="Modo oscuro"><br><sub><b>Oscuro</b></sub></td>
    <td align="center"><img src="docs/capturas/03_menu_alto_contraste.png" width="230" alt="Modo de alto contraste"><br><sub><b>Alto contraste</b></sub></td>
  </tr>
  <tr>
    <td align="center"><img src="docs/capturas/04_menu_personalizado.png" width="230" alt="Modo personalizado"><br><sub><b>Personalizado</b> (tus dos colores)</sub></td>
    <td align="center"><img src="docs/capturas/05_acento_verde.png" width="230" alt="Acento verde"><br><sub><b>Acento verde</b> (modo claro)</sub></td>
    <td align="center"><img src="docs/capturas/06_acento_morado.png" width="230" alt="Acento morado"><br><sub><b>Acento morado</b> (modo oscuro)</sub></td>
  </tr>
</table>

### El día a día

**Registrar entrada y salida** con lector de código de barras, tarjeta RFID o de forma manual:

<p align="center"><img src="docs/capturas/10_registrar_entrada_salida.png" width="460" alt="Registrar entrada y salida"></p>

**Control del día (Pendientes)**: quién falta por marcar, los cambios de turno, lo que hay que confirmar y quién está ausente, todo en un solo lugar y por turno. También en modo oscuro:

<p align="center"><img src="docs/capturas/12_pendientes_del_dia.png" width="470" alt="Pendientes del día">&nbsp;<img src="docs/capturas/13_pendientes_oscuro.png" width="470" alt="Pendientes del día en modo oscuro"></p>

**Cambio de turno y llegadas muy temprano**: el programa explica qué pasó (turno asignado, a qué hora entró, con qué turno coincide, lo que hizo ese día) y deja elegir qué turno cuenta. Los avisos no se pierden al terminar el día y se resuelven solos cuando la salida lo aclara:

<p align="center"><img src="docs/capturas/14_cambio_de_turno.png" width="460" alt="Cuadro para resolver un cambio de turno"></p>

**Llegadas tarde**: quién llegó tarde y cuánto, con el tiempo que queda por decidir:

<p align="center"><img src="docs/capturas/11_llegadas_tarde.png" width="760" alt="Llegadas tarde"></p>

**Justificar o compensar**: nada se descuenta ni se justifica solo. Cada tiempo sin cubrir lo decide una persona: justificar, justificar y descontar, descontar o compensar con horas extra que ya tenía:

<p align="center"><img src="docs/capturas/15_justificar_o_compensar.png" width="430" alt="Justificar o compensar el tiempo"></p>

**Ausencias y permisos**: vacaciones, incapacidades, permisos por horas y otras, con avisos en la campanita antes de que terminen:

<p align="center"><img src="docs/capturas/16_ausencias.png" width="760" alt="Ausencias"></p>

**Empleados y turnos** (fijos, rotativos y de apoyo) y **corrección de marcas** cuando alguien olvida marcar:

<p align="center"><img src="docs/capturas/17_gestionar_empleados.png" width="620" alt="Gestionar empleados">&nbsp;<img src="docs/capturas/18_editar_registro.png" width="620" alt="Editar registro"></p>

**Estadísticas** para ver cómo va el personal de un vistazo: puntualidad, llegadas tarde, horas extra y ausencias:

<p align="center"><img src="docs/capturas/19_estadisticas.png" width="760" alt="Estadísticas"></p>

**Configuración** por categorías: horario, márgenes, festivos, marcación, reportes, respaldos y apariencia:

<p align="center"><img src="docs/capturas/20_configuracion.png" width="640" alt="Configuración"></p>

## Qué hace

- **Marcación** de entrada y salida por código, código de barras, lector RFID o número de identificación, con foto opcional y confirmación por voz.
- **Pendientes del día** por turno: marcas que faltan, cambios de turno, llegadas muy temprano, salidas con motivo y jornadas incompletas.
- **Decisiones con una persona al mando:** el tiempo que no se cubrió se justifica, se descuenta o se compensa con horas extra, siempre eligiéndolo alguien, con el motivo anotado.
- **Turnos fijos, rotativos y de apoyo**, con detección del cambio de turno según la hora de llegada.
- **Editar registro** para corregir o completar las marcas de un empleado.
- **Ausencias** (vacaciones, incapacidades, permisos por horas y otras) con avisos en la campanita.
- **Domingos y festivos:** lista de citados, faltantes e impresión en PDF con varios estilos; se puede indicar si la empresa los trabaja o no.
- **Reporte de Excel** por rango de fechas, con una hoja por empleado (semana por semana, con las notas y decisiones de cada día y de dónde sale cada cifra), logo y colores de la empresa.
- **Estadísticas** de puntualidad, horas extra y ausencias.
- **Gestión de empleados** y turnos.
- **Respaldos automáticos** y copias externas (USB o nube), con restauración guiada.
- Temas claro, oscuro, de alto contraste y personalizado, color de acento y tamaño de letra ajustable.
- Se **repara solo** si la base de datos viene de una versión vieja, y avisa si falta o se dañó.

## Instalación y actualización

1. Ejecuta el instalador y sigue los pasos.
2. Abre A Tiempo y configura el horario y los empleados desde **Configuración**.
3. Cuando hay una versión nueva, A Tiempo avisa y se actualiza en el mismo lugar **sin tocar tus datos** (antes crea un respaldo automático).

## Requisitos

- Windows 7 o superior (32 o 64 bits).
- No necesita internet para el uso diario; solo para buscar actualizaciones.

## Privacidad

Las marcaciones, los datos de los empleados y las fotos se guardan **únicamente en el equipo donde está instalado el programa**. El programa no envía datos de asistencia a ningún servidor. Lo único que sale del equipo es lo que el usuario decide enviar a soporte (por ejemplo, una nota o el paquete de diagnóstico) y la consulta de actualizaciones.

## Soporte

Dentro del programa: **Configuración › Soporte** (ayuda, notas de la versión y paquete de diagnóstico).

## Estado del proyecto

Software de uso comercial con licencia. Este repositorio publica los instaladores y las notas de cada versión.
