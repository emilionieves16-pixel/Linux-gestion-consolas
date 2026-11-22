# Linux-grstion-consolas
# Sistema Operativo Linux para Gestión de Alquileres y Control Financiero

Proyecto de grado desarrollado en la UNEFA - Núcleo Aragua. 
Consiste en un sistema operativo Linux embebido y especializado, diseñado para automatizar el control de tiempos de alquiler de consolas de videojuegos y la gestión financiera de un establecimiento comercial en Palo Negro, Estado Aragua.

#Objetivos
- Control Operativo:Monitoreo en tiempo real de consolas mediante daemons en segundo plano.
- Módulo Financiero:Automatización de cobros, registro de flujo de caja y eliminación de errores manuales.
- Ejecución de Apps; Integración de **Waydroid** sobre un compositor **Wayland** para ejecutar el módulo financiero de manera eficiente.

 #Stack Tecnológico y Requerimientos Clave
- Base: Linux (Kernel personalizado con soporte para `memfd` en lugar de `ashmem`).
- Gráficos: Compositor Wayland (requisito excluyente para Waydroid).
- Contenedores:Waydroid.
- Licencia: Software Libre / Código Abierto.

# Equipo de Desarrollo (Grupo 3 - Sección D-2)
- José Flores (C.I: 31.381.418)
- Yorman Jesus (C.I: 31.540.613)
- Gabriel Emilio (C.I: 28.249.117)
- Tutora:Prof. Yanmar Rodriguez

#Estructura del Proyecto
- `/os-build`: Configuración del kernel y sistema base.
- `/apps`: Código fuente de los módulos de control y financiero.
- `/docs`: Documentación técnica y capítulos de la investigación.