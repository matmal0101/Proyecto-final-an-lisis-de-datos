# Proyecto-final-an-lisis-de-datos

# 🌾 Dashboard de Monitorización Agrícola en España
### Proyecto de Análisis de Datos · Universidad Europea · 2025–2026

---

## 📋 Descripción del proyecto

Este proyecto consiste en un **dashboard interactivo de análisis y monitorización del sector agrícola español**, desarrollado como entrega final de la asignatura de Análisis de Datos. El panel permite visualizar, cruzar e interpretar datos agrícolas, climáticos y económicos de las 17 comunidades autónomas de España durante el período **2020–2024**, con el objetivo de apoyar la toma de decisiones en política agraria, gestión hídrica y planificación territorial.

El proyecto está alineado con la **Agenda 2030** y los Objetivos de Desarrollo Sostenible **ODS 2** (Hambre cero), **ODS 6** (Agua limpia y saneamiento), **ODS 13** (Acción por el clima) y **ODS 15** (Vida de ecosistemas terrestres).

---

## 👥 Equipo

| Integrante | Rol | Responsabilidad |
|---|---|---|
| **Paula** | Data Engineer / Business Analyst | Recopilación, limpieza y preparación de los datos |
| **Marcos** | Diseñador de Visualización (UI/UX) | Maquetación y diseño del dashboard |
| **Noa** | Consultora Estratégica y Sostenibilidad | Introducción, contexto y marco ODS |
| **Matías** | Project Manager / Analista de Negocio | Objetivos, KPIs, interpretación, conclusiones y repositorio |

---

## 🗂️ Estructura del repositorio

```
📁 dashboard-agricultura-españa/
│
├── 📁 datos/
│   ├── Agricultura_copia.xlsx        # Dataset limpio con variables por CCAA (2020–2024)
│   └── fuentes.md                    # Descripción de fuentes, supuestos y limitaciones
│
├── 📁 memoria/
│   └── Memoria_Dashboard_Agricultura.pdf   # Informe completo del proyecto (PDF)
│
├── 📁 presentacion/
│   └── Presentacion_Defensa.pptx     # Diapositivas de apoyo para la defensa oral
│
├── 📁 prompts/
│   └── prompts_utilizados.md         # Registro de prompts de IA empleados en el proyecto
│
└── README.md                         # Este archivo
```

---

## 📊 Dashboard

El dashboard está desarrollado en **Looker Studio** y es accesible públicamente en el siguiente enlace:

🔗 **[Ver dashboard en Looker Studio](https://datastudio.google.com/s/vrnqpRstxds)**

> El dashboard es completamente navegable e incluye filtros interactivos por comunidad autónoma y año.

---

## 🗃️ Descripción del dataset

El archivo principal `Agricultura_copia.xlsx` contiene datos agregados por comunidad autónoma y año, con las siguientes variables:

| Variable | Descripción |
|---|---|
| `anio` | Año de referencia (2020–2024) |
| `comunidad` | Comunidad autónoma |
| `Anomalia` | Desviación de temperatura respecto a la media histórica (°C) |
| `coste_agua_eur/m3` | Coste del agua de riego por metro cúbico (€) |
| `Fecha Anual` | Fecha de referencia anual |
| `precio_eur_ha` | Precio medio de la tierra agraria (€/ha) |
| `precipit_l/m2` | Precipitación media anual (l/m²) |
| `renta_Meur` | Renta agraria total (millones de €) |
| `superficie_cultivada_Mha` | Superficie cultivada total (millones de ha) |
| `superficie_regadio_Mha` | Superficie en regadío (millones de ha) |
| `superficie_secano_Mha` | Superficie en secano (millones de ha) |
| `temp_media` | Temperatura media anual (°C) |
| `Anomalia Max` | Anomalía térmica máxima registrada (°C) |
| `Lluvia Media` | Precipitación media del período (l/m²) |
| `Temp. Media` | Temperatura media del período (°C) |

**Fuentes de datos:** MAPA (Ministerio de Agricultura, Pesca y Alimentación), AEMET, INE y datos públicos de open data agrario.

---

## 🎯 Objetivos y KPIs principales

El dashboard está diseñado para responder a las siguientes preguntas de negocio:

- ¿Qué comunidades autónomas generan mayor renta agraria y por qué?
- ¿Cómo evoluciona la relación entre anomalía térmica y superficie de regadío?
- ¿Dónde es más ineficiente el uso del agua en relación con la renta generada?
- ¿Qué territorios son más vulnerables ante el cambio climático?

**KPIs monitorizados:** renta agraria por CCAA, coste del agua por m³, ratio regadío/secano, anomalía térmica anual, evolución del precio por hectárea y precipitación media.

---

## 📚 Referencias principales

- Ministerio de Agricultura, Pesca y Alimentación. (2024). *Informe anual de indicadores 2023*. Gobierno de España.
- Agencia Estatal de Meteorología. (2024). *Informe sobre el estado del clima de España 2023*. MITECO.
- Instituto Nacional de Estadística. (2025). *Encuesta sobre la estructura de las explotaciones agrícolas 2023*. INE.
- IPCC. (2022). *Climate Change 2022: Impacts, Adaptation and Vulnerability (AR6)*. Cambridge University Press.
- Naciones Unidas. (2015). *Agenda 2030 para el Desarrollo Sostenible* (A/RES/70/1).

---

## ⚙️ Herramientas utilizadas

- **Looker Studio** — Construcción del dashboard
- **Microsoft Excel** — Limpieza y preparación de datos
- **Microsoft PowerPoint** — Presentación de la defensa
- **GitHub / Google Drive** — Control de versiones y almacenamiento

---

## 📬 Contacto docente

**Jose Luis Gómez** · joseluis.gomez.o@universidadeuropea.es
Universidad Europea · Curso 2025–2026
