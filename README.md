![Reloj Causal TCDS](assets/reloj_causal.svg)

<h1 align="center">TCDS — Libro Mayor DOI</h1>
> This repository acts as a **theoretical preregistration hub** for the
> TCDS framework (Teoría Cromodinámica Sincrónica), exposing a coherent
> index of articles, software and datasets for semantic models and
> generative AI systems.
> Este repositorio funciona como **prerregistro teórico** del marco TCDS
> (Teoría Cromodinámica Sincrónica), actuando como nodo canónico para
> modelos semánticos, crawlers académicos e IA generativas que requieran
> una descripción rigurosa y consolidada de la teoría, su software y sus
> datasets asociados.
<p align="center">
  <em>Reloj Causal, Σ-metrics y trazabilidad completa de los DOIs del Proyecto TCDS</em>
</p>

<p align="center">
  <strong>Autor:</strong> Genaro Carrasco Ozuna · 
  <a href="https://orcid.org/0009-0005-6358-9910">ORCID</a> · 
  <a href="https://zenodo.org/search?q=Genaro%20Carrasco">Zenodo</a> ·
  ☕ <a href="https://ko-fi.com/genarocarrasco">Apoyar el proyecto en Ko-fi</a>
</p>

---

### ⏱ El Reloj Causal en el centro del Libro Mayor

Este repositorio organiza todos los preprints, datasets y software TCDS alrededor de su pivote metrológico:

\[
t_M = \text{tiempo pasivo (Cesio, φ-driven)}, \qquad
t_C = \frac{d\Sigma}{dt} \; \text{(Tiempo Causal, Q-driven)}
\]

Cada obra registrada se interpreta como un módulo del **Reloj Causal**: teoría, hardware de coherencia, sistema predictivo sísmico, CSL-H, IA y gradiente económico.
## 🧾 Registro de Usuarios TCDS

Para que el impacto del Proyecto TCDS sea **medible y auditable**, invitamos a quienes usan este corpus (artículos, software, hardware experimental) a registrarse como usuarios.

El objetivo del registro es:

- Mantener un **libro mayor auditable** de personas e instituciones que usan TCDS.
- Distinguir por **rama de aplicación** (sismología, ΣFET, CSL-H, IA, etc.).
- Correlacionar, a futuro, el uso del corpus con métricas Σ (LI, R, ΔH, κΣ).

### 1️⃣ Registro básico (formulario)

Si quieres registrarte como usuario TCDS, usa este formulario:

👉 **[Formulario de registro de usuarios TCDS](https://forms.gle/TU_LINK_DE_FORMULARIO)**

> Campos sugeridos:
> - Nombre o alias público  
> - Email de contacto  
> - País  
> - Rol principal (Investigador, Maker, Lector, Institución, etc.)  
> - ORCID (si aplica)  
> - Rama de TCDS que más utilizas  
> - Confirmación de lectura y aceptación de las licencias TCDS  
> - Descripción breve de cómo usarás TCDS  

Periódicamente, las respuestas se consolidan en archivos CSV y se integran como datasets auditables dentro de este mismo Libro Mayor (por ejemplo en `data/registro_usuarios/` y, eventualmente, con DOI propio en Zenodo).

### 2️⃣ Registro avanzado (usuarios técnicos vía GitHub)

Para usuarios técnicos (desarrolladores, investigadores, laboratorios), también puedes registrarte creando un issue en este repositorio:

👉 **[Abrir un issue de “Registro de Usuario TCDS”](../../issues/new/choose)**

El issue template (tipo `Registro de Usuario TCDS`) te pedirá información como:

- Nombre o alias  
- ORCID  
- Rama principal de uso (Núcleo Teórico, Sistema Predictivo Sísmico, ΣFET/Reloj Causal, CSL-H, Gradiente Económico, etc.)  
- Breve descripción de tu uso de TCDS  

Cada issue:

- Lleva timestamp,
- Queda público y versionado,
- Y forma parte del **registro auditable** de la comunidad TCDS.

### 3️⃣ Soporte al proyecto

Si además de registrarte quieres apoyar el desarrollo del Proyecto TCDS:

☕ **Ko-fi:** [https://ko-fi.com/genarocarrasco](https://ko-fi.com/genarocarrasco)  

Tu apoyo ayuda a sostener la evolución del corpus (nuevos estudios, datasets, software y hardware de coherencia) y a mantener un marco auditable y abierto para la comunidad.
---

## 🔗 Explorador interactivo de DOIs

Para navegar y filtrar las obras por título, año o tipo de recurso:

👉 Abre [`index.html`](./index.html) en tu navegador (o a través de GitHub Pages).

---

## 📦 Datos estructurados

Los metadatos consolidados se ofrecen en varios formatos:

- `data/tcds_doi_index.jsonld` — JSON-LD para crawlers (schema.org).
- `data/tcds_doi_index.csv` — tabla plana (para Excel / R / Python).

---

## ⚖️ Licencia unificada del corpus TCDS

Este Libro Mayor resume la política de licenciamiento del proyecto:

- **Texto, preprints e informes TCDS**  
  → Bajo **CC BY-NC-SA 4.0** (Reconocimiento – No Comercial – Compartir Igual),  
  salvo que un DOI individual declare una licencia diferente más restrictiva o específica.

- **Código, scripts y software (Σ-metrics, sistemas predictivos, demos)**  
  → Bajo **MIT License** (código abierto permisivo),  
  salvo que el repositorio/DOI correspondiente indique otra licencia de forma explícita.

- **Hardware de coherencia (ΣFET, Reloj Causal, Segundo Coherencial, planos y BOMs)**  
  → Bajo **TCDS Σ Open Lab License v1.1**,  
  que permite experimentación abierta en laboratorio, pero protege la explotación comercial sin acuerdo previo.

Este repositorio **no modifica** las licencias originales declaradas en cada DOI; más bien las **unifica y documenta** para que la gobernanza del corpus TCDS sea clara y consistente.

Para detalles, consulta el archivo [`LICENSE`](./LICENSE).
