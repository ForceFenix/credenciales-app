Versión inicial completa del sistema de credenciales - v1.0

- Automatización del recorte de fotos centrado en rostro y hombros, con eliminación de fondo y fondo blanco final.
- Procesamiento de firmas con mejora de visibilidad y redimensión.
- Configuración dinámica a través de config.py: MARGEN_SUP, MARGEN_INF, ANCHO_CROP.
- Interfaz de calibración visual con sliders, previsualización en tiempo real y guardado automático de parámetros.
- Interfaz principal (main_gui.py) para seleccionar carpetas, ejecutar procesamiento individual o conjunto, y ver resultados en consola.
- Correcciones de errores críticos en Tkinter al gestionar múltiples ventanas.
- Migración de PhotoImage a CTkImage para soporte HiDPI y compatibilidad con customtkinter.
- Refactor para que RecorteApp funcione como ventana secundaria (CTkToplevel), evitando conflictos con la GUI principal.

Estructura modular finalizada:
- core/: lógica de procesamiento
- utils/: herramientas de imagen
- calibrador_recorte.py
- main_gui.py
- config.py
