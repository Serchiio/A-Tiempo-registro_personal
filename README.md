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

## Qué hace

- **Marcación** de entrada y salida por código, código de barras, lector RFID o número de identificación, con foto opcional y confirmación por voz.
- **Llegadas tarde y pendientes** del día, con tiempo por compensar.
- **Editar registro** para corregir o completar las marcas de un empleado.
- **Ausencias** (vacaciones, incapacidades y otras) con avisos.
- **Domingos y festivos:** lista de citados, faltantes e impresión en PDF con varios estilos; se puede indicar si la empresa los trabaja o no.
- **Reporte de Excel** por rango de fechas, con logo y colores de la empresa.
- **Gestión de empleados** y turnos.
- **Respaldos automáticos** y copias externas (USB o nube), con restauración guiada.
- Temas claro, oscuro y de alto contraste, y tamaño de letra ajustable.
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
