UniCIEO — Sistema de Virtualización Académica y Proyección de Costos
Universidad CIEO | Vicerrectoría Académica
Vigilada Mineducación

Descripción
Sistema integral de gestión académica diseñado para la Universidad CIEO, enfocado en el seguimiento del proceso de virtualización de programas académicos, el control de costos, la gestión de contratos y el cumplimiento de condiciones de Registro Calificado ante el MEN (Ministerio de Educación Nacional de Colombia).
Se trata de una aplicación web de página única (SPA) que funciona completamente en el navegador, sin necesidad de servidor backend. Toda la lógica, datos y visualizaciones están contenidos en un solo archivo HTML portable.

Módulos
1. Dashboard Ejecutivo
Panel de control con indicadores clave de gestión:

Total de programas activos y su estado SACES (Con Registro, Renovación, Radicado, En Proceso, Pendiente)
Avance general de virtualización (asignaturas ejecutadas vs. proyectadas)
Resumen financiero consolidado (costos de virtualización + inversión en contratos)
Estado de programas por categoría
Gráficos interactivos: avance por programa, distribución por sección, ejecutado vs. proyectado, costo transversal vs. propio

2. Datos Programas (Registro Calificado)
Seguimiento de las 15 condiciones del Decreto 1330 para cada programa académico:

Tarjetas interactivas por programa con indicadores de avance
Detalle de etapas SACES (Denominación, Justificación, Contenidos Curriculares, Organización de Actividades, Investigación, Relación con el Sector Externo, Personal Docente, Medios Educativos, Infraestructura Física, Mecanismos de Selección, Estructura Administrativa, Autoevaluación, Programa de Egresados, Bienestar Universitario, Recursos Financieros)
Filtros por estado: Renovación, Con Registro, Radicados, En Proceso, Pendientes
Edición de etapas con cambio de estado y observaciones

3. Virtualidad Académica
Gestión de la virtualización de 15 programas y 216 asignaturas:

Tabla con 15 programas (5 actuales/renovación, 5 nuevos confirmados, 5 en proyección)
Detalle expandible por programa con información de SNIES, créditos, resolución, costos
216 asignaturas clasificadas como Transversales (65) y Propias (151)
Editor de asignaturas con asignación multi-programa
Filtros por sección, estado y modalidad
Barra de resumen con KPIs de virtualización

4. Flujo de Caja
Proyección financiera mensual (Dic-2025 a Jul-2026):

Montos ejecutados vs. proyectados por período
Integración de datos de contratos al flujo financiero
Gráfico de barras comparativo
Cálculo automático de totales

5. Inversión y Contratos
Módulo de seguimiento de 6 contratos por un total de $267.700.000 COP:

KPIs compactos: inversión total, avalado, pendiente, ejecutado, % avance
Tabla de contratos con barra de progreso visual
Detalle expandible de pagos por contrato
Doble aprobación: VB Académica (aval del Vicerrector) + Pago Financiera (ejecución)
Proyección mensual vs. ejecución real
Gráfico de análisis por contrato (Chart.js)

6. Bitácora de Cambios
Registro cronológico de todas las acciones del sistema:

Filtros por programa y tipo (Actualización, Aprobación, Comentario)
Registro automático de cambios en contratos y programas
Formulario para agregar entradas manuales


Programas Académicos
CódigoProgramaModalidadEstado SACESSecciónGSOGest. Serv. OdontológicosVirtualCon RegistroActualesORTOrtodonciaPresencialRenovaciónActualesIMPImplantología OralPresencialRenovaciónActualesENDEndodonciaPresencialCon RegistroActualesPERPeriodonciaPresencialCon RegistroActualesGMSGcia. Mercadeo en SaludVirtualRadicadoNuevosGCSGcia. Calidad en SaludVirtualRadicadoNuevosADMAdministración en SaludVirtualRadicadoNuevosRORehabilitación OralPresencialRadicadoNuevosODOOdontologíaPresencialRadicadoNuevosGSGerencia de la SaludVirtualEn ProcesoProyecciónAUDAuditoría en SaludVirtualEn ProcesoProyecciónSSTGerencia de la SSTVirtualEn ProcesoProyecciónPSIPsicologíaVirtualEn ProcesoProyecciónISIngeniería de SoftwareVirtualPendienteProyección

Contratos Registrados
IDContratistaProgramaValorCPS-PJ-001-2025Visu S.A.SVirtualización (Asesoría Cond. 8)$9.000.000CPS-PN-002-2026Daniel Orlando Montes ToroAdm. Servicios de Salud$20.000.000CPS-PN-003-2026Daniel Orlando Montes ToroGerencia de Calidad en Salud$8.000.000CPS-PN-004-2026Daniel Orlando Montes ToroAdministración de Empresas$18.000.000CPS-PN-005-2026Politécnico de ColombiaGerencia de Mercadeo en Salud$30.000.000CPS-PJ-001-2026Politécnico de ColombiaPaquete Programas Virtuales$182.700.000Total Inversión$267.700.000

Tecnologías

HTML5 / CSS3 / JavaScript ES6 — Aplicación SPA de archivo único
Chart.js — Gráficos interactivos (barras, donas, pie)
LocalStorage API — Persistencia de datos y auto-guardado
CSS Variables — Sistema de diseño con paleta institucional UniCIEO
PapaParse — Importación/exportación de datos CSV


Uso

Descargar el archivo UniCIEO_Virtualizacion_FINAL.html
Abrir directamente en cualquier navegador moderno (Chrome, Edge, Firefox)
No requiere servidor, instalación ni conexión a internet

Auto-guardado

Los cambios se guardan automáticamente en el navegador cada 30 segundos
Al hacer cambios en contratos, programas o etapas, el guardado es inmediato
El botón "Guardar archivo" descarga una copia HTML con el estado actual
Al reabrir el archivo en el mismo navegador, se restauran los datos guardados


Estructura del Proyecto
/
├── UniCIEO_Virtualizacion_FINAL.html   # Aplicación principal (archivo único)
├── README.md                            # Este archivo
└── docs/                                # Documentación adicional (opcional)

Paleta de Colores Institucional
VariableColorUso--color-red#D40E1EColor principal UniCIEO--color-black#171717Texto y encabezados--color-success#27ae60Estados completados / aprobados--color-warning#f39c12Estados pendientes--color-danger#e74c3cAlertas y urgencias

Autor
Andrés Iván Toledo
Vicerrector Académico — Universidad CIEO

Licencia
Uso interno institucional — Universidad CIEO.
Todos los derechos reservados.
