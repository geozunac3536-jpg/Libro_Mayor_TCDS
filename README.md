![Reloj Causal TCDS](assets/reloj_causal.svg)

<h1 align="center">TCDS — Libro Mayor DOI</h1>

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
