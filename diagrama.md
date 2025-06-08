```mermaid
graph TD
    A[Inicio] --> B[Apertura de archivos OCT\nExtracción de XML]
    B --> C[Procesamiento de intensidad\nFiltrado en decibeles]
    C --> D[Identificación de óvulos\nRed neuronal]
    D --> E[Exportación de cortes axiales]
    E --> F[Cálculo de vóxel\nEscala física]
    F --> G[Autenticación\nInterfaz segura]
    G --> H[Cifrado de datos\nAES]
    H --> I[Reporte automático\nDatos y metadatos]
    I --> J[Fin]
