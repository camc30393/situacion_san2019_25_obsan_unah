# Dashboard · Panorama de la Seguridad Alimentaria y Nutricional en Honduras (2019–2025)
 
<div align="center">
[![Institución](https://img.shields.io/badge/UNAH-IIS%20%2F%20FCCSS-223A75?style=flat-square&labelColor=0C1E3A)](https://www.unah.edu.hn)
[![OBSAN](https://img.shields.io/badge/OBSAN-Observatorio%20SAN-1BAEC7?style=flat-square&labelColor=0C1E3A)](https://obsan.unah.edu.hn)
[![Versión](https://img.shields.io/badge/Dashboard-v1.0-FDBA13?style=flat-square&labelColor=0C1E3A)](.)
[![Boletín](https://img.shields.io/badge/Boletín-v3%20%C2%B7%20abril%202026-85C6E4?style=flat-square&labelColor=0C1E3A)](.)
[![Licencia](https://img.shields.io/badge/Licencia-CC%20BY--NC%204.0-green?style=flat-square)](LICENSE)
 
**Tablero interactivo de visualización de datos** que acompaña al Boletín Temático  
*Situación de la Seguridad Alimentaria y Nutricional en Honduras, 2019–2025*  
producido por el **OBSAN / IIS / FCCSS / UNAH**.
 
</div>
---
 
## Tabla de contenidos
 
- [Acerca del proyecto](#acerca-del-proyecto)
- [Vista previa](#vista-previa)
- [Secciones del tablero](#secciones-del-tablero)
- [Indicadores clave](#indicadores-clave)
- [Fuentes de datos](#fuentes-de-datos)
- [Tecnologías](#tecnologías)
- [Uso y despliegue](#uso-y-despliegue)
- [Actualización de datos](#actualización-de-datos)
- [Citar este recurso](#citar-este-recurso)
- [Equipo](#equipo)
- [Licencia](#licencia)
---
 
## Acerca del proyecto
 
Este repositorio contiene el tablero digital interactivo desarrollado por el **Observatorio en Seguridad Alimentaria y Nutricional (OBSAN)**, adscrito al Instituto de Investigaciones Sociales (IIS) de la Facultad de Ciencias Sociales (FCCSS) de la **Universidad Nacional Autónoma de Honduras (UNAH)**.
 
El tablero es el componente de visualización que acompaña al *Boletín Temático SAN Honduras 2019–2025 (v3, abril 2026)* y tiene como propósito:
 
- Sintetizar y comunicar la evidencia empírica sobre la situación de la Seguridad Alimentaria y Nutricional (SAN) en Honduras entre 2019 y 2025.
- Facilitar la lectura crítica de indicadores multidimensionales para tomadores de decisión, investigadores, organismos de cooperación y sociedad civil.
- Generar insumos estratégicos para la incidencia pública del OBSAN en materia de política alimentaria y nutricional.
El análisis articula las cinco dimensiones estructurales de la SAN —**disponibilidad, acceso, consumo, utilización biológica y estabilidad**— con enfoques de resiliencia, vulnerabilidad climática, desarrollo humano y gobernanza institucional.
 
> **Nota metodológica:** Los datos contenidos en el tablero son de naturaleza académica y de difusión pública. Toda conclusión cuantitativa debe ser verificada y validada por el equipo investigador antes de su uso en documentos oficiales.
 
---
 
## Vista previa
 
```
┌─────────────────────────────────────────────────────────────┐
│  OBSAN · Dashboard SAN Honduras 2019–2025                   │
│  ─────────────────────────────────────────────────────────  │
│  [01 Resumen]  [02 Acceso]  [03 Precios]  [04 Disponib.]   │
│  [05 CIF/IPC]  [06 Nutrición]  [07 Refs.]                  │
│                                                             │
│  KPIs  ·  Gráficas de serie temporal  ·  Tablas            │
│  Clasificación CIF departamental  ·  Modo oscuro           │
└─────────────────────────────────────────────────────────────┘
```
 
El tablero está implementado como un único archivo HTML autocontenido, sin dependencias de servidor. Basta abrirlo en cualquier navegador moderno.
 
---
 
## Secciones del tablero
 
| # | Sección | Contenido principal |
|---|---------|---------------------|
| 01 | **Resumen ejecutivo** | KPIs críticos: subalimentación, pobreza, CIF F3+, remesas, CBA, desnutrición crónica, sector agropecuario |
| 02 | **Acceso alimentario** | Evolución de la Canasta Básica Alimentaria (CBA) urbana y rural; pobreza por ingreso 2019–2024; salario mínimo real vs. inflación |
| 03 | **Precios de alimentos** | Series mensuales de precios de granos básicos (maíz, frijol, arroz, sorgo); índice de precios al consumidor (IPC) alimentario |
| 04 | **Disponibilidad** | Sector agropecuario según el Censo Agropecuario Nacional (CAN 2024): productores, explotaciones, tenencia de tierra, acceso a crédito y asistencia técnica |
| 05 | **Inseguridad alimentaria aguda (CIF)** | Clasificación Integrada de Fases (CIF/IPC) 2019–2025: evolución nacional y distribución departamental; fases F1–F5 |
| 06 | **Nutrición** | Desnutrición crónica (retraso del crecimiento), emaciación, sobrepeso en menores de 5 años; brechas urbano/rural y por quintil de ingreso (ENDESA/MICS 2019) |
| 07 | **Referencias** | Bibliografía completa en formato APA 7.ª edición de todas las fuentes citadas en el tablero |
 
---
 
## Indicadores clave
 
Los siguientes indicadores son presentados con sus valores más recientes disponibles al momento de publicación del boletín (v3, abril 2026):
 
| Indicador | Valor | Período | Fuente |
|-----------|-------|---------|--------|
| Subalimentación | 20.4 % | 2021–2023 | FAO et al. (2025) |
| Inseguridad alimentaria aguda CIF F3+ | 1.78 millones de personas | Dic 2024 – Mar 2025 | UTSAN (2025) |
| Pobreza total (hogares) | 62.9 % | 2024 | INE (2025a) |
| Pobreza extrema (hogares) | 40.1 % | 2024 | INE (2025a) |
| Remesas familiares | USD 11,904 millones | 2025 | BCH (2026) |
| Canasta Básica Alimentaria urbana | L 2,683.60 / persona / mes | 2025 | OBSAN (2026) |
| Productores agropecuarios | 408,965 | CAN 2024 | INE/SAG (2025) |
| Desnutrición crónica (< 5 años) | 19 % nacional | 2019 | ENDESA/MICS (2019) |
| Desnutrición crónica — quintil más pobre | 33 % | 2019 | ENDESA/MICS (2019) |
| Acceso a crédito agropecuario | 4.8 % de productores | CAN 2024 | INE/SAG (2025) |
| Asistencia técnica agropecuaria | 11.6 % de productores | CAN 2024 | INE/SAG (2025) |
 
---
 
## Fuentes de datos
 
El tablero integra datos de las siguientes fuentes institucionales primarias:
 
| Fuente | Documento / Serie | Año |
|--------|-------------------|-----|
| **FAO, FIDA, OPS, PMA y UNICEF** | Panorama regional de la SAN en América Latina y el Caribe 2024 | 2025 |
| **FAO, FIDA, OPS, PMA y UNICEF** | Panorama regional de la SAN en América Latina y el Caribe 2022 | 2023 |
| **Banco Central de Honduras (BCH)** | Encuesta Nacional de Ingresos y Gastos de los Hogares (ENIGH) 2023–2024 | 2025 |
| **Banco Central de Honduras (BCH)** | Remesas familiares corrientes — reportes dinámicos | 2025–2026 |
| **Instituto Nacional de Estadística (INE)** | Encuesta Permanente de Hogares de Propósitos Múltiples (EPHPM) | 2019–2024 |
| **Instituto Nacional de Estadística (INE) / SAG** | Censo Agropecuario Nacional (CAN 2024) | 2025 |
| **UTSAN** | Informe del Análisis de Inseguridad Alimentaria Aguda de la CIF: Honduras 2019–2025 | 2025 |
| **SCGG / SESAL / INE / UNFPA / UNICEF** | Encuesta Nacional de Demografía y Salud (ENDESA/MICS 2019) | 2021 |
| **INE / UN / WFP / UNICEF** | Evaluación de la situación nutricional y de SAN en 4 regiones priorizadas | 2022 |
| **INE / AECID** | Análisis del impacto de COVID-19 en la SAN en 39 municipios de Honduras | 2022 |
| **OBSAN / IIS / UNAH** | Monitoreo de precios de granos básicos | 2026 |
| **OBSAN / IIS / UNAH** | Monitoreo de precios de alimentos y costo de la CBA | 2026 |
| **CEPAL** | Índice de necesidades críticas — Honduras | 2024 |
 
La bibliografía completa en formato APA 7 está disponible en la sección 07 del tablero y en el boletín académico que lo acompaña.
 
---
 
## Tecnologías
 
El tablero es un archivo HTML estático autocontenido. No requiere servidor, base de datos ni proceso de compilación.
 
| Componente | Tecnología / Versión |
|------------|----------------------|
| Lenguaje base | HTML5 / CSS3 / JavaScript (ES2020) |
| Gráficas | [Chart.js 4.4.1](https://www.chartjs.org/) |
| Visualizaciones avanzadas | [D3.js 7.8.5](https://d3js.org/) |
| Tipografía | [Fraunces](https://fonts.google.com/specimen/Fraunces) · [IBM Plex Sans](https://fonts.google.com/specimen/IBM+Plex+Sans) · [IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono) (Google Fonts) |
| Paleta de color | Institucional UNAH (`#223A75`, `#FDBA13`, `#0C1E3A`, `#1BAEC7`, `#85C6E4`, `#5C5858`) |
| Paleta CIF | Colores oficiales IPC/CIF (`F1–F5`) |
| Tema | Claro / Oscuro (modo nativo del sistema, conmutable por el usuario) |
| Dependencias externas | CDN jsDelivr (Chart.js) · CDN jsDelivr (D3.js) · Google Fonts |
 
> El tablero no almacena ni transmite datos del usuario. No utiliza cookies, *localStorage* ni ningún servicio de analítica de terceros.
 
---
 
## Uso y despliegue
 
### Visualización local
 
```bash
# Clonar el repositorio
git clone https://github.com/<usuario-o-org>/obsan-dashboard-san-hn.git
cd obsan-dashboard-san-hn
 
# Abrir directamente en el navegador
open OBSAN_Dashboard_SAN_Honduras_2019_2025.html
# o bien
start OBSAN_Dashboard_SAN_Honduras_2019_2025.html   # Windows
xdg-open OBSAN_Dashboard_SAN_Honduras_2019_2025.html  # Linux
```
 
No se requiere instalar dependencias. El archivo carga Chart.js y D3.js desde CDN; para uso **completamente offline**, descargue las bibliotecas y actualice las rutas en las etiquetas `<script>` del encabezado.
 
### Despliegue en GitHub Pages
 
1. En el repositorio, ir a **Settings → Pages**.
2. Seleccionar la rama `main` y la carpeta raíz `/`.
3. Guardar. El tablero quedará disponible en:  
   `https://<org>.github.io/<repositorio>/OBSAN_Dashboard_SAN_Honduras_2019_2025.html`
### Despliegue en servidor propio
 
Copie el archivo `.html` a cualquier directorio público de su servidor web (Apache, Nginx, etc.). No se requiere configuración adicional.
 
---
 
## Actualización de datos
 
El tablero está diseñado para facilitar la actualización de datos sin alterar el código de visualización. Todos los datos se centralizan en el objeto `OBSAN_DATA` y la lista `REFS` al inicio del bloque `<script>`.
 
**Para actualizar el tablero en futuras revisiones del boletín:**
 
1. Abra el archivo HTML en un editor de texto.
2. Localice el bloque:
   ```javascript
   const OBSAN_DATA = {
     // ...
   };
   ```
3. Modifique únicamente los valores numéricos y cadenas de texto dentro de `OBSAN_DATA`.
4. Actualice la lista `REFS` con las nuevas referencias APA 7 si corresponde.
5. Actualice el número de versión del boletín en el pie de página (`footer-bottom`).
> El código de renderizado lee automáticamente `OBSAN_DATA`; no es necesario modificar las funciones de visualización.
 
**Convención de versiones del archivo:**  
`OBSAN_Dashboard_SAN_Honduras_2019_2025_v<N>.html`
 
---
 
## Citar este recurso
 
Si utiliza este tablero o los datos que presenta en publicaciones académicas, informes técnicos o materiales de difusión, cite de la siguiente manera:
 
### Cita del tablero (APA 7)
 
```
Manzanares Cruz, C. A. (2026). Dashboard SAN Honduras 2019–2025 (v1.0)
  [Tablero interactivo de datos]. Observatorio en Seguridad Alimentaria
  y Nutricional (OBSAN), Instituto de Investigaciones Sociales (IIS),
  Facultad de Ciencias Sociales, Universidad Nacional Autónoma de
  Honduras (UNAH). https://github.com/<org>/<repositorio>
```
 
### Cita del boletín que lo acompaña (APA 7)
 
```
Observatorio en Seguridad Alimentaria y Nutricional (OBSAN). (2026).
  Situación de la Seguridad Alimentaria y Nutricional en Honduras,
  2019–2025 (Boletín Temático SAN, v3). Instituto de Investigaciones
  Sociales (IIS), Facultad de Ciencias Sociales, Universidad Nacional
  Autónoma de Honduras (UNAH).
```
 
---
 
## Equipo
 
| Rol | Nombre | Unidad |
|-----|--------|--------|
| Diseño, desarrollo y análisis | **Christian Alexis Manzanares Cruz** | Especialista en Sistemas de Información — OBSAN/IIS/FCCSS/UNAH |
 
**Institución:**  
Observatorio en Seguridad Alimentaria y Nutricional (OBSAN)  
Instituto de Investigaciones Sociales (IIS)  
Facultad de Ciencias Sociales (FCCSS)  
Universidad Nacional Autónoma de Honduras (UNAH)  
Tegucigalpa, M.D.C., Honduras
 
---
 
## Licencia
 
Este trabajo se distribuye bajo la licencia  
**Creative Commons Atribución-NoComercial 4.0 Internacional (CC BY-NC 4.0)**.
 
[![CC BY-NC 4.0](https://licensebuttons.net/l/by-nc/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc/4.0/)
 
Usted puede compartir y adaptar el material siempre que otorgue el crédito correspondiente al OBSAN/IIS/UNAH y no lo utilice con fines comerciales.
 
Los datos estadísticos presentados provienen de fuentes institucionales de acceso público y conservan las condiciones de uso establecidas por cada organismo emisor.  
Consulte el archivo [`LICENSE`](LICENSE) para los términos completos.
 
---
 
<div align="center">
**OBSAN / IIS / FCCSS / UNAH · 2026**  
*El OBSAN tiene como propósito generar evidencia académica, investigación aplicada y análisis de información estratégica que aporten al debate público sobre seguridad alimentaria, desarrollo humano y políticas alimentarias en Honduras.*
 
</div>
