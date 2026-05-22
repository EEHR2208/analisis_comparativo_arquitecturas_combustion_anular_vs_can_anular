```json
{
  "titulo": "Análisis Comparativo de Arquitecturas de Combustión en Aviación Comercial: Desempeño y Sostenibilidad de Sistemas Anulares vs. Can-Anulares",
  "folder_name": "analisis_comparativo_arquitecturas_combustion_anular_vs_can_anular",
  "abstract_preliminar": "Este artículo presenta un análisis comparativo exhaustivo entre las arquitecturas de combustores anulares y can-anulares en motores de aviación comercial. Se evalúan métricas clave de desempeño como eficiencia de combustión, distribución de temperatura, pérdida de presión y estabilidad de operación bajo condiciones representativas de vuelo. Desde la perspectiva de sostenibilidad, se cuantifican emisiones de NOx, CO, HC y partículas, junto con el potencial de integración con combustibles sostenibles de aviación (SAF) y hidrógeno. Utilizando datos de simulaciones CFD, pruebas en banco y revisiones de literatura reciente (2022-2026), se identifican ventajas de los combustores anulares en uniformidad térmica y reducción de emisiones, frente a la mayor mantenibilidad de los can-anulares. Los resultados indican reducciones potenciales de hasta 40% en NOx y mejoras en eficiencia del 5-10% con diseños anulares optimizados. Se discuten implicaciones para el diseño de próxima generación de motores turbofan de alto bypass ratio y se proponen recomendaciones para futuras investigaciones en combustión lean y materiales avanzados.",
  "secciones": [
    {
      "nro": 1,
      "titulo_seccion": "Introducción",
      "objetivos": ["Presentar el contexto de las arquitecturas de combustión en aviación comercial", "Establecer la importancia de la sostenibilidad y eficiencia en el sector", "Definir objetivos y alcance del análisis comparativo"],
      "subsecciones": ["1.1. Motivación y relevancia", "1.2. Evolución histórica de los combustores", "1.3. Objetivos de investigación y estructura del artículo"],
      "insumos": ["Figura 1: Esquemas comparativos", "Tabla 1: Requisitos regulatorios ICAO"],
      "llaves_bibtex": ["Makida2008", "Moreno2024", "Jeong2021"]
    },
    {
      "nro": 2,
      "titulo_seccion": "Antecedentes y Estado del Arte",
      "objetivos": ["Revisar la evolución de las tecnologías de combustores", "Analizar estudios comparativos existentes", "Identificar brechas en investigación sobre sostenibilidad"],
      "subsecciones": ["2.1. Tipos de combustores: can, can-anular y anular", "2.2. Avances en reducción de emisiones (2022-2026)", "2.3. Integración con SAF e hidrógeno"],
      "insumos": ["Tabla 2: Comparación histórica de eficiencia y emisiones"],
      "llaves_bibtex": ["SafeFly2025", "Liu2024", "Chen2025"]
    },
    {
      "nro": 3,
      "titulo_seccion": "Descripción de las Arquitecturas de Combustión",
      "objetivos": ["Detallar principios de diseño de cada arquitectura", "Comparar características geométricas y aerodinámicas"],
      "subsecciones": ["3.1. Combustores Can-Anulares", "3.2. Combustores Anulares", "3.3. Análisis comparativo preliminar de parámetros de diseño"],
      "insumos": ["Figura 2: Diagramas esquemáticos", "Eq. 1: Ecuaciones de flujo y mezcla"],
      "llaves_bibtex": ["Makida2008", "Moreno2024"]
    },
    {
      "nro": 4,
      "titulo_seccion": "Metodología de Análisis Comparativo",
      "objetivos": ["Definir el marco metodológico", "Describir herramientas de simulación y validación"],
      "subsecciones": ["4.1. Modelos CFD y 1D", "4.2. Condiciones operativas y métricas de evaluación", "4.3. Criterios de sostenibilidad"],
      "insumos": ["Tabla 3: Parámetros de simulación", "Eq. 2: Modelos de emisión NOx"],
      "llaves_bibtex": ["Jeong2021", "Moreno2024"]
    },
    {
      "nro": 5,
      "titulo_seccion": "Análisis de Desempeño",
      "objetivos": ["Comparar eficiencia, estabilidad y perfiles térmicos"],
      "subsecciones": ["5.1. Eficiencia de combustión y pérdida de presión", "5.2. Distribución de temperatura y patrón factor", "5.3. Estabilidad en condiciones de vuelo"],
      "insumos": ["Figura 3: Gráficos de eficiencia", "Tabla 4: Resultados cuantitativos"],
      "llaves_bibtex": ["Liu2024", "Jeong2021"]
    },
    {
      "nro": 6,
      "titulo_seccion": "Evaluación de Sostenibilidad y Emisiones",
      "objetivos": ["Cuantificar impacto ambiental", "Evaluar compatibilidad con combustibles alternativos"],
      "subsecciones": ["6.1. Emisiones contaminantes (NOx, CO, soot)", "6.2. Análisis de ciclo de vida y SAF", "6.3. Métricas de sostenibilidad"],
      "insumos": ["Tabla 5: Comparación de emisiones", "Figura 4: Perfiles de NOx"],
      "llaves_bibtex": ["Chen2025", "SafeFly2025"]
    },
    {
      "nro": 7,
      "titulo_seccion": "Discusión",
      "objetivos": ["Interpretar resultados", "Analizar trade-offs y limitaciones"],
      "subsecciones": ["7.1. Ventajas y desventajas comparativas", "7.2. Implicaciones para diseño de motores futuros", "7.3. Limitaciones del estudio"],
      "insumos": [],
      "llaves_bibtex": ["Liu2024", "Moreno2024"]
    },
    {
      "nro": 8,
      "titulo_seccion": "Conclusiones y Trabajos Futuros",
      "objetivos": ["Sintetizar hallazgos principales", "Proponer recomendaciones y direcciones futuras"],
      "subsecciones": ["8.1. Conclusiones clave", "8.2. Recomendaciones de diseño", "8.3. Trabajos futuros"],
      "insumos": [],
      "llaves_bibtex": ["Chen2025", "Jeong2021"]
    }
  ]
}
```

```bibtex
@article{Makida2008,
  author    = {Makida, M. and Yamada, H. and Yamamoto, T.},
  title     = {Development of Full Annular Combustor for Small Aircraft Jet Engine in JAXA TechCLEAN Project},
  journal   = {Proceedings of the 26th International Congress of the Aeronautical Sciences},
  year      = {2008},
  pages     = {559},
  url       = {http://www.icas.org/icas_archive/ICAS2008/PAPERS/559.PDF},
  note      = {Base para actualizaciones en diseños anulares}
}

@article{Moreno2024,
  author    = {Moreno-Pacheco, L. A. and Sánchez-López, et al.},
  title     = {Design and Numerical Analysis of an Annular Combustion Chamber for CFM-56 Engine},
  journal   = {Fluids},
  volume    = {9},
  number    = {7},
  pages     = {161},
  year      = {2024},
  doi       = {10.3390/fluids9070161},
  url       = {https://www.mdpi.com/2311-5521/9/7/161},
  note      = {[Online]. Available: https://www.mdpi.com/2311-5521/9/7/161}
}

@article{Jeong2021,
  author    = {Jeong, G. and Ahn, K.},
  title     = {One-Dimensional Analysis of Double Annular Combustor for Reducing Harmful Emissions},
  journal   = {Energies},
  volume    = {14},
  number    = {13},
  pages     = {3930},
  year      = {2021},
  doi       = {10.3390/en14133930},
  url       = {https://www.mdpi.com/1996-1073/14/13/3930},
  note      = {[Online]. Available: https://www.mdpi.com/1996-1073/14/13/3930}
}

@misc{SafeFly2025,
  author    = {SafeFly Editorial},
  title     = {Combustor Technology: From Can to Annular to Hydrogen-Powered Engines},
  year      = {2025},
  url       = {https://safefly.aero/jet-engine-combustor-evolution/},
  note      = {Accessed: 2026}
}

@article{Liu2024,
  author    = {Liu, Z. and et al.},
  title     = {Analyzing Engine Performance and Combustor Characteristics with Sustainable Aviation Fuels},
  journal   = {Aerospace},
  volume    = {11},
  number    = {12},
  pages     = {1053},
  year      = {2024},
  doi       = {10.3390/aerospace11121053},
  url       = {https://www.mdpi.com/2226-4310/11/12/1053}
}

@article{Chen2025,
  author    = {Chen, L. and et al.},
  title     = {The role of sustainable aviation fuel in reducing emissions: A comparative analysis},
  journal   = {Progress in Aerospace Sciences},
  year      = {2025},
  doi       = {10.1016/j.paerosci.2025.100998},
  url       = {https://www.sciencedirect.com/science/article/abs/pii/S0376042125000983}
}
```

```json
{
  "seccion_nro": 1,
  "titulo_seccion": "Introducción",
  "mapa_uso": {
    "Makida2008": {
      "razon_seleccion": "Proporciona base experimental en desarrollo de combustores anulares completos para motores de aviación.",
      "guia_redaccion": "Usar en 1.2 para contextualizar evolución desde diseños legacy a anulares, citando logros en reducción NOx.",
      "subseccion_destino": "1.2"
    },
    "Moreno2024": {
      "razon_seleccion": "Estudio reciente de diseño numérico de combustor anular para CFM-56.",
      "guia_redaccion": "Integrar en 1.1 y 1.3 para motivar análisis comparativo con datos CFD modernos.",
      "subseccion_destino": "1.1"
    },
    "Jeong2021": {
      "razon_seleccion": "Análisis 1D de double annular combustor enfocado en emisiones.",
      "guia_redaccion": "Citar en 1.3 para destacar brechas en sostenibilidad y justificar metodología.",
      "subseccion_destino": "1.3"
    }
  }
}
```

```json
{
  "seccion_nro": 2,
  "titulo_seccion": "Antecedentes y Estado del Arte",
  "mapa_uso": {
    "SafeFly2025": {
      "razon_seleccion": "Revisión actualizada de evolución desde can a annular y hacia hidrógeno.",
      "guia_redaccion": "Usar tabla comparativa en 2.1 para destacar ventajas cuantitativas (peso, eficiencia, emisiones).",
      "subseccion_destino": "2.1"
    },
    "Liu2024": {
      "razon_seleccion": "Análisis de desempeño con SAF en motores jet.",
      "guia_redaccion": "Integrar en 2.3 para discutir compatibilidad y reducciones de emisiones.",
      "subseccion_destino": "2.3"
    },
    "Chen2025": {
      "razon_seleccion": "Revisión del rol de SAF en reducción de emisiones.",
      "guia_redaccion": "Citar en 2.2 y 2.3 para estado del arte en sostenibilidad.",
      "subseccion_destino": "2.2"
    }
  }
}
```

```json
{
  "seccion_nro": 3,
  "titulo_seccion": "Descripción de las Arquitecturas de Combustión",
  "mapa_uso": {
    "Makida2008": {
      "razon_seleccion": "Detalles de implementación de full annular combustor.",
      "guia_redaccion": "Describir características en 3.2, citando pruebas experimentales.",
      "subseccion_destino": "3.2"
    },
    "Moreno2024": {
      "razon_seleccion": "Metodología detallada de diseño anular para motor comercial.",
      "guia_redaccion": "Usar en 3.2 y 3.3 para ecuaciones y parámetros geométricos.",
      "subseccion_destino": "3.2"
    }
  }
}
```

```json
{
  "seccion_nro": 4,
  "titulo_seccion": "Metodología de Análisis Comparativo",
  "mapa_uso": {
    "Jeong2021": {
      "razon_seleccion": "Modelo 1D optimizado para DAC y emisiones.",
      "guia_redaccion": "Base para 4.1 y Eq. 2 en metodología de modelado.",
      "subseccion_destino": "4.1"
    },
    "Moreno2024": {
      "razon_seleccion": "Enfoque CFD para diseño anular.",
      "guia_redaccion": "Describir herramientas NUMECA/CFD en 4.1 y parámetros en Tabla 3.",
      "subseccion_destino": "4.1"
    }
  }
}
```

```json
{
  "seccion_nro": 5,
  "titulo_seccion": "Análisis de Desempeño",
  "mapa_uso": {
    "Liu2024": {
      "razon_seleccion": "Resultados de desempeño en motores con diferentes combustibles.",
      "guia_redaccion": "Soporte cuantitativo para gráficas de eficiencia en 5.1.",
      "subseccion_destino": "5.1"
    },
    "Jeong2021": {
      "razon_seleccion": "Datos de emisiones y optimización en annular.",
      "guia_redaccion": "Comparar perfiles térmicos y estabilidad en 5.2-5.3.",
      "subseccion_destino": "5.2"
    }
  }
}
```

```json
{
  "seccion_nro": 6,
  "titulo_seccion": "Evaluación de Sostenibilidad y Emisiones",
  "mapa_uso": {
    "Chen2025": {
      "razon_seleccion": "Análisis comparativo de SAF en emisiones.",
      "guia_redaccion": "Tabla 5 y discusión de reducciones en 6.1-6.2.",
      "subseccion_destino": "6.1"
    },
    "SafeFly2025": {
      "razon_seleccion": "Datos cuantitativos de reducción de emisiones en annular vs can.",
      "guia_redaccion": "Citar ventajas (~40% reducción) en introducción de sección.",
      "subseccion_destino": "6.1"
    }
  }
}
```

```json
{
  "seccion_nro": 7,
  "titulo_seccion": "Discusión",
  "mapa_uso": {
    "Liu2024": {
      "razon_seleccion": "Trade-offs en desempeño y emisiones.",
      "guia_redaccion": "Analizar implicaciones prácticas y limitaciones en 7.1 y 7.3.",
      "subseccion_destino": "7.1"
    },
    "Moreno2024": {
      "razon_seleccion": "Insights de diseño CFD aplicables a comercial.",
      "guia_redaccion": "Soporte para recomendaciones de diseño futuro.",
      "subseccion_destino": "7.2"
    }
  }
}
```

```json
{
  "seccion_nro": 8,
  "titulo_seccion": "Conclusiones y Trabajos Futuros",
  "mapa_uso": {
    "Chen2025": {
      "razon_seleccion": "Perspectivas de SAF y sostenibilidad a largo plazo.",
      "guia_redaccion": "Citar en 8.3 para trabajos futuros en combustibles alternativos.",
      "subseccion_destino": "8.3"
    },
    "Jeong2021": {
      "razon_seleccion": "Optimización de parámetros en annular para emisiones.",
      "guia_redaccion": "Sintetizar hallazgos clave de reducción de NOx/CO en 8.1.",
      "subseccion_destino": "8.1"
    }
  }
}
```