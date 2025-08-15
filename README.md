# 🔍 Query4Jobs – Proyecto de Adrian Valerio  

**Query4Jobs** es una aplicación web interactiva desarrollada por **Adrian Valerio García**, estudiante de Ingeniería de Software en la **Universidad Peruana de Ciencias Aplicadas (UPC)**.  
El proyecto tiene como finalidad realizar un análisis comparativo de oportunidades laborales en **Estadística** y **Ciencia de Datos** a nivel internacional, permitiendo filtrar por puesto y país, visualizar métricas clave mediante gráficos dinámicos y explorar cursos recomendados en Coursera para fortalecer la formación profesional.  

---

## 💡 Objetivos del proyecto

- Facilitar el análisis del mercado laboral en campos estadísticos y relacionados con ciencia de datos.
- Presentar tendencias salariales, tecnologías demandadas y experiencia requerida de manera visual e intuitiva.
- Recomendar formación especializada mediante cursos populares disponibles en Coursera.

---

## 🚀 Funcionalidades principales

### 🧭 Búsqueda personalizada
- Filtrado por **puesto de trabajo especializado** (más de 15 opciones) y **país extranjero**:
  - Estados Unidos 🇺🇸
  - España 🇪🇸
  - México 🇲🇽
  - Alemania 🇩🇪
  - Francia 🇫🇷

### 📊 Visualización de resultados
- Estadísticas clave:
  - Total de empleos encontrados
  - Salario promedio
  - Tecnología más mencionada
- Gráficos dinámicos con **Chart.js**:
  - 📉 Distribución salarial
  - 💻 Tecnologías más demandadas
  - 📈 Experiencia requerida
  - 🏢 Fuentes de publicación

### 📚 Panel Coursera
- Cursos recomendados para potenciar el perfil profesional:
  - Python
  - SQL
  - R  
*Datos obtenidos mediante integración con SerpAPI.*

---

## 🖼️ Componentes visuales

- Formulario con validación y selección de filtros
- Indicador de carga animado
- Panel de resultados interactivo
- Sección de errores personalizada
- Lista dinámica de empleos
- Panel de formación con categorías de cursos

---

## 🛠️ Tecnologías utilizadas

| Componente     | Tecnología                  |
|----------------|-----------------------------|
| Frontend       | HTML, CSS, JavaScript       |
| Visualización  | Chart.js                    |
| Backend        | Python                      |
| Datos externos | Jooble, Adzuna, SerpAPI     |

---

## 📁 Salida de datos

Los reportes generados se almacenan en formato `.json`, organizados por puesto y país para su reutilización o análisis posterior.

---

## ⚠️ Limitaciones y problemas conocidos

- En algunos casos **no se encuentra información** para determinados **puestos** en ciertos **países** debido a la cobertura variable de las APIs y/o a la traducción de títulos.  
- La disponibilidad de resultados depende de **Adzuna** y **Jooble**: pueden aplicar **límites de tasa**, cambios de endpoint o fluctuaciones en la cantidad/calidad de datos.  
- Para evitar errores de **CORS**, la aplicación debe ejecutarse desde un **servidor web local** y los archivos `.json` deben generarse previamente con `data_collector.py`.  
- Las métricas (salarios/experiencia) se calculan con los datos disponibles; si no hay valores, algunos gráficos pueden **no mostrarse** o aparecer como **N/A**.

---

## 📌 Créditos de fuentes

- [Jooble](https://www.jooble.org/)
- [Adzuna](https://www.adzuna.com/)
- [Coursera](https://www.coursera.org/) (vía [SerpAPI](https://serpapi.com/))

---

✍ **Autor:** Adrian Valerio García  
🎓 **Carrera:** Ingeniería de Software – UPC  
📅 **Año:** 2025
