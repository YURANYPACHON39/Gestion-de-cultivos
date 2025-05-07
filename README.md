# PROYECTO-PROGRAMACION-2

# AGROGESTIÓN: Sistema Inteligente para la Administración de cultivos

## Descripción del problema que resuelve:

Los agricultores dedicados al cultivo de zanahoria en zonas de clima frío enfrentan dificultades en la gestión técnica y operativa de sus cultivos, lo que reduce la eficiencia y rentabilidad de sus actividades. Algunos de los problemas más comunes incluyen:

  - Registro manual y desorganizado: Muchos agricultores aún utilizan notas en papel o la memoria para el seguimiento del cultivo, lo que genera pérdidas de información clave.
  - Desperdicio de recursos: Sin un control eficiente de insumos como agua, fertilizantes y pesticidas, es común incurrir en sobrecostos y aplicar materiales de manera inadecuada.
  - Falta de planificación: La ausencia de cronogramas estructurados genera retrasos en labores críticas como la siembra, el riego o la cosecha, afectando el rendimiento.
  - Dificultad para analizar datos: La falta de reportes estructurados impide evaluar el desempeño productivo y hacer mejoras en futuras temporadas.
    
AgroGestión es una aplicación web moderna, que centraliza y automatiza la gestión del cultivo de zanahoria, especialmente en zonas de clima frío. Ofrece una interfaz intuitiva, accesible desde cualquier navegador, con registro automatizado, control de recursos, planificación de actividades y reportes visuales.

## Integrantes del Equipo
   - [Monica Alejandra Avellaneda](https://github.com/MONICAAVELLANEDA78)
   - [Yurany Alejandra Pachon](https://github.com/YURANYPACHON39)

## Lista Inicial de Módulos del Sistema

Módulos del Sistema

1. Registro y Seguimiento de Cultivos
   - Permite registrar información de cada cultivo (tipo de planta, fecha de siembra, tratamientos aplicados, fecha de cosecha).
   - Visualización clara del historial con gráficos de crecimiento y productividad.
   - Envío automático de alertas por correo electrónico para recordar tareas programadas como el riego, la fertilización y la cosecha.

2. Planificación de Actividades
   - Creación de calendarios de siembra, riego, fertilización y cosecha.
   - Generación de recordatorios y notificaciones sobre tareas pendientes.

3. Generación de Reportes y Análisis de Datos
   - Creación de informes detallados sobre rendimiento de cultivos, costos y uso de recursos.
   - Visualización de datos con gráficos y estadísticas interactivas.
   - Exportación de reportes en PDF o en Matlab para análisis y seguimiento.

## Interfaz de Usuario
La interfaz de AgroGestión ha sido diseñada para ser intuitiva, moderna y accesible desde cualquier navegador web. Está enfocada en brindar una experiencia clara, ordenada y visualmente atractiva para agricultores y administradores del cultivo de zanahoria.
- Diseño General
  - Aplicación web responsiva, accesible desde PC, tabletas o celulares.
  - Navegación lateral fija mediante menú vertical, con íconos y nombres claros de cada módulo.
  - Panel principal tipo dashboard con visualización de datos clave.
  - Diseño basado en Material Design, con uso de colores suaves, tarjetas informativas, y tipografía legible.

- Componentes Principales

1. Pantalla de Inicio
   - Opción de inicio de sesión con correo y contraseña (seguridad básica).
   - Acceso directo sin autenticación si el sistema se configura en modo libre.
   - Logo del sistema y frase de bienvenida personalizable.

2. Panel Principal
   - Número de cultivos activos.
   - Consumo de recursos en la última semana.
   - Tareas próximas (con colores según prioridad).
   - Gráficos de productividad por cultivo.
   - Accesos directos a los 3 módulos principales (Registro, Planificación, Reportes).

3. Módulo de Cultivos
   - Formulario de registro: nombre del cultivo, fecha de siembra, tipo de planta, tratamientos aplicados, etc.
   - Tabla con historial de cultivos, ordenable y con filtros por fecha o estado.
   - Gráficos de crecimiento generados automáticamente con base en los datos ingresados.

4. Módulo de Planificación
   - Calendario dinámico (tipo Google Calendar).
   - Vista mensual/semanal de tareas programadas.
   - Al hacer clic en una fecha, se puede agregar una nueva actividad (riego, fertilización, cosecha, etc.).
   - Envío de alertas por correo electrónico en la fecha programada.

5. Módulo de Reportes
   - Generador de reportes por rango de fechas, cultivo o tipo de actividad.
   - Visualización en pantalla de gráficos de barras, líneas o pastel.
   - Botón para exportar a PDF.
   - Posibilidad de exportar datos en formato compatible con MATLAB.

## Tecnología 
   - Lenguaje: JavaScript
   - Framework Web: HTML, CSS, JS
   - Base de Datos: Firebase Firestore
   - Editor: Visual Studio Code
   - Servicio de correo: EmailJS

## Flujo del Sistema
1. Inicio de Sesión
   - Ingreso desde el navegador.
   - Acceso mediante autenticación o modo libre.
   - Visualización del panel principal.
    
2. Registro y Seguimiento
   - Acceso al módulo de cultivos desde el menú.
   - Formulario para registrar datos clave.
   - Almacenamiento en Firestore.
   - Tabla con cultivos históricos y filtros.
   - Gráficos de productividad automáticos.
   - Configuración de alertas por fecha.

3. Planificación de Actividades
   - Acceso al calendario.
   - Registro de tareas por fecha y tipo.
   - Almacenamiento de tareas y prioridades.
   - Recordatorios por correo electrónico.

4. Reportes y Análisis
   - Filtros por fecha, tipo de cultivo o actividad.
   - Visualización de gráficos estadísticos.
   - Exportación en PDF o descarga para MATLAB.
  
5. Panel Principal
   - Resumen de cultivos activos.
   - Estadísticas de recursos.
   - Tareas programadas.
   - Indicadores visuales de productividad.
