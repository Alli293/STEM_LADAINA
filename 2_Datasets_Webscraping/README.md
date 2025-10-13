# 📁 Datasets_Webscraping

### 📘 Descripción general
Esta carpeta agrupa todos los **datasets obtenidos por web scraping sin limpiar**, organizados en carpetas por fecha **(AAMMDD)**.  
Cada subcarpeta corresponde a una ejecución de scraping y contiene los datos crudos antes del procesamiento o limpieza.

---

### 📁 Estructura
├── 20240508/
│ ├── puestosbase_crudas.csv
│ ├── linkedin_titulos.csv
│ └── metadata.json
├── 20240610/
│ ├── puestos_crudas.csv
│ └── metadata.json


---

### 🗓️ Registro de actualizaciones
| Fecha | Carpeta | Cambio realizado | Autor/a |
|--------|----------|------------------|----------|
| 2025-10-12 | 20251012 | Se agrego archivo mas reciente de trabajos sin limpiar (no se hizo scraping) | Allison Romero |


---

### ✅ Notas adicionales
- Los datos en esta carpeta **no deben modificarse manualmente**.  
- Si se detectan errores en la extracción, deben corregirse en el código fuente, no en los archivos.  
- Cada carpeta debe tener un `metadata.json` con información de la fuente, fecha y parámetros de scraping.
