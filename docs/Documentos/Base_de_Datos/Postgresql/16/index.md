---
title: Documentación de PostgreSQL 16.2
---

[El Grupo de Desarrollo Global de PostgreSQL](https://www.postgresql.org/developer/core/)
-------------------------------------------

Copyright © 1996-2024 Grupo de Desarrollo Global de PostgreSQL

[Aviso legal]()

Tabla de contenido

Prefacio

    1. ¿Qué es PostgreSQL?
    2. Breve Historia de PostgreSQL
    3. Convenciones
    4. Información adicional
    5. Directrices para la notificación de errores

I. Tutorial

    1. Introducción
    2. El lenguaje SQL 
    3. Características avanzadas


II. El lenguaje SQL

    4. Sintaxis SQL
    5. Definición de datos
    6. Manipulación de datos
    7. Consultas
    
[8. Tipos de datos](II.El_lenguaje_SQL/8.Tipos_de_datos.md)

    9. Funciones y operadores
    10. Conversión de tipos
    11. Índices
    12. Búsqueda de texto completo
    13. Control de concurrencia
    14. Consejos de rendimiento
    15. Consulta paralela

III. Administración de servidores

    16. Instalación a partir de binarios
    17. 17. Instalación desde código fuente
    18. Instalación desde código fuente en Windows
    19. Configuración y funcionamiento del servidor
    20. Configuración del servidor
    21. Autenticación de clientes
    22. Funciones de la base de datos
    23. 23. Gestión de Bases de Datos
    24. Localización
    25. Tareas rutinarias de mantenimiento de bases de datos
    26. Copia de seguridad y restauración
    27. Alta Disponibilidad, Equilibrio de Carga y Replicación
    
[28. Monitorización de la Actividad de la Base de Datos](III.Administracion_de_servidores/28.Seguimiento_de_la_actividad_de_la_base_de_datos.md)
    
    29. Monitorización del Uso del Disco
    30. Fiabilidad y el registro de escritura anticipada
    31. Replicación Lógica
    32. Compilación Justo a Tiempo (JIT)
    33. Pruebas de regresión

IV. Interfaces cliente

    34. libpq - Biblioteca C
    35. Objetos grandes
    36. ECPG - SQL incrustado en C
    37. El esquema de información

V. Programación de servidores

    38. Extensión de SQL
    39. Disparadores
    40. Disparadores de eventos
    41. El sistema de reglas
    42. Lenguajes de procedimiento
    43. PL/pgSQL - Lenguaje procedimental SQL
    44. PL/Tcl - Lenguaje procedimental Tcl
    45. PL/Perl - Lenguaje de Procedimientos Perl
    46. PL/Python - Lenguaje de Procedimientos Python
    47. Interfaz de programación de servidor
    48. Procesos de trabajo en segundo plano
    49. Decodificación lógica
    50. Seguimiento del progreso de la replicación
    51. Módulos de archivo

VI. Referencia

    I. Comandos SQL
    II. Aplicaciones Cliente PostgreSQL
    III. Aplicaciones de Servidor PostgreSQL

VII. Internos

    52. Visión General de los Internos de PostgreSQL
    53. Catálogos del Sistema
    54. Vistas del Sistema
    55. Protocolo Frontend/Backend
    56. Convenciones de Codificación PostgreSQL
    57. Soporte de Lenguaje Nativo
    58. Escribiendo un Manejador de Lenguaje Procedimental
    59. Escritura de una Envoltura de Datos Foráneos
    60. Escritura de un Método de Muestreo de Tabla
    61. Escritura de un Proveedor de Escaneo Personalizado
    62. Optimizador Genético de Consultas
    63. Definición de la Interfaz del Método de Acceso a Tablas
    64. Definición de la interfaz del método de acceso a índices
    65. Registros WAL genéricos
    66. Gestores de Recursos WAL Personalizados
    67. Índices B-Tree
    68. Índices GiST
    69. Índices SP-GiST
    70. Índices GIN
    71. Índices BRIN
    72. Índices Hash
    73. Almacenamiento físico de bases de datos
    74. Procesamiento de transacciones
    75. Declaraciones del catálogo del sistema y contenido inicial
    76. Cómo utiliza las estadísticas el planificador
    77. Formato del Manifiesto de Copia de Seguridad

VIII. Apéndices

    A. Códigos de error PostgreSQL
    B. Soporte de Fecha/Hora
    C. Palabras Clave SQL
    D. Conformidad SQL
    E. Notas de Publicación
    F. Módulos y extensiones adicionales suministrados
    G. Programas adicionales suministrados
    H. Proyectos externos
    I. Repositorio de código fuente
    J. Documentación
    K. Límites de PostgreSQL
    L. Acrónimos
    M. Glosario
    N. Soporte de color
    O. Funciones obsoletas o renombradas
    Bibliografía
    Índice