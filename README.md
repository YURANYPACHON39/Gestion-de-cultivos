# PROYECTO-PROGRAMACION-2

# AGROGESTIÓN: Sistema Inteligente para la Administración de cultivos

## Descripción del problema que resuelve:

Los agricultores enfrentan dificultades en la gestión de sus cultivos, lo que reduce la eficiencia y rentabilidad de sus actividades. Algunos de los problemas más comunes incluyen:
   - Registro manual y desorganizado: La mayoría de los agricultores utilizan notas en papel o memoria, lo que dificulta el seguimiento preciso de cultivos.
   - Desperdicio de recursos: Sin un control adecuado de insumos como agua, fertilizantes y pesticidas, hay sobrecostos y uso ineficiente de materiales.
   - Falta de planificación: La ausencia de un cronograma estructurado puede generar retrasos en la siembra y cosecha, afectando la producción.
   - Dificultad para analizar datos: Sin reportes adecuados, es difícil evaluar el rendimiento de los cultivos y mejorar futuras temporadas.

Nuestra solución es AgroGestión, una plataforma de escritorio exclusiva para Windows que permite a los agricultores gestionar eficientemente sus cultivos mediante una interfaz intuitiva, almacenamiento seguro con SQLite, registros automatizados y reportes avanzados con gráficos y mapas interactivos.

## Integrantes del Equipo
   - [Monica Alejandra Avellaneda](https://github.com/MONICAAVELLANEDA78)
   - [Yurany Alejandra Pachon](https://github.com/YURANYPACHON39)

## Lista Inicial de Módulos del Sistema

Módulos del Sistema

1. Registro y Seguimiento de Cultivos
   - Permite registrar información de cada cultivo (tipo de planta, fecha de siembra, tratamientos aplicados, fecha de cosecha).
   - Visualización clara del historial con gráficos de crecimiento y productividad.
   - Alertas automáticas para recordar tareas como riego, fertilización y cosecha.

2. Gestión de Recursos Agrícolas
   - Control del uso de insumos (fertilizantes, pesticidas, semillas, agua).
   - Estimación de consumo futuro basado en datos históricos.
   - Posibilidad de ingresar datos manualmente desde sensores externos.

3. Planificación de Actividades
   - Creación de calendarios de siembra, riego, fertilización y cosecha.
   - Generación de recordatorios y notificaciones sobre tareas pendientes.
   - Optimización de tiempos y recursos para mejorar la eficiencia operativa.

4. Generación de Reportes y Análisis de Datos
   - Creación de informes detallados sobre rendimiento de cultivos, costos y uso de recursos.
   - Visualización de datos con gráficos y estadísticas interactivas.
   - Exportación de reportes en Excel y PDF para análisis y seguimiento.

## Interfaz de Usuario
La interfaz de AgroGestión Pro está diseñada para ser intuitiva, moderna y eficiente, facilitando el acceso a la información sin necesidad de conocimientos técnicos avanzados. Se utilizará un diseño basado en Material Design para una experiencia visual clara y ordenada.

- Diseño General
   - Interfaz de escritorio exclusiva para Windows, desarrollada con Electron.js.
   - Menú lateral fijo para una navegación rápida entre módulos.
   - Panel principal con un dashboard que muestra información relevante de un vistazo.
   - Gráficos interactivos y mapas para visualizar datos de productividad y consumo.
   - Uso de colores y tipografía accesible para mejorar la experiencia del usuario.

- Componentes Principales
1. Pantalla de Inicio y Autenticación (Opcional)
   - Inicio de sesión con credenciales (si se requiere seguridad en los datos).
   - Acceso directo sin autenticación para usuarios que no lo necesiten.

2. Dashboard (Panel Principal)
   - Resumen general con indicadores clave:
   - Número de cultivos activos.
   - Consumo de recursos en la última semana.
   - Próximas tareas pendientes.
   - Gráficos de productividad y consumo con visualización rápida de tendencias.
   - Accesos directos a los módulos principales.

3. Módulo de Cultivos
   - Formulario de registro para ingresar detalles del cultivo (nombre, tipo de planta, fecha de siembra, etc.).
   - Tabla con historial de cultivos con filtros y búsqueda rápida.
   - Gráficos de crecimiento en función de los datos ingresados.
   - Alertas visuales para tareas como riego, fertilización y cosecha.

4. Módulo de Gestión de Recursos
   - Listado de insumos agrícolas con cantidad disponible y consumo estimado.
   - Gráficos de consumo para visualizar tendencias de uso.
   - Alertas de bajo stock para evitar desperdicio o escasez de materiales.
     
5. Módulo de Planificación
   - Calendario interactivo con programación de tareas.
   - Notificaciones de actividades pendientes.
   - Opciones de reprogramación rápida en caso de cambios.
     
6. Módulo de Reportes
   - Generación de informes visuales sobre rendimiento de cultivos y costos.
   - Gráficos y mapas interactivos para análisis de productividad.
   - Consulta de reportes almacenados en la base de datos SQLite.

## Tecnología 
   - Lenguaje de Programación: JavaScript (con Electron.js).
   - Base de Datos: SQLite (almacenamiento estable y escalable).
   - Plataforma: Exclusiva para Windows.

## Flujo del Sistema
1. Inicio y Registro de Cultivos
   - Ingreso de datos de cultivos y visualización de su estado.
     
2. Gestión de Recursos
   - Registro y control del consumo de insumos.
     
3. Planificación de Actividades
   - Creación de tareas y alertas en el calendario interactivo.
     
4. Análisis y Reportes
   - Generación de informes gráficos sobre productividad y costos.
