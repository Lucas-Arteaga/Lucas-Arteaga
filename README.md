<div align="center">

# Lucas Arteaga

**Petroleum Engineering @ UBA · Technical Contract Analyst & Expeditor @ Valbol Worcester**

*I understand the economics behind every technical decision — and I optimize operating flows with data.*

<a href="https://www.linkedin.com/in/lucas-arteaga-/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<a href="mailto:larteaga@fi.uba.ar"><img src="https://img.shields.io/badge/Email-Write_me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
<img src="https://img.shields.io/badge/Buenos_Aires-Argentina-2ea44f?style=for-the-badge" alt="Buenos Aires, Argentina">
<img src="https://img.shields.io/badge/Open_to_relocate-Neuqu%C3%A9n_Vaca_Muerta-1f6feb?style=for-the-badge" alt="Open to relocate to Neuquén">

### 📌 [What I do](#what-i-do) · [Proof](#proof) · [Work](#work) · [Certifications](#certifications) · [How I work](#how-i-work) · [Español](#español)

</div>

---

<a id="what-i-do"></a>
## 🛠️ What I do

Fifth-year Petroleum Engineering student at Universidad de Buenos Aires, working full time at an API valve manufacturer that supplies upstream operators. I review engineering specifications for a living, I know what a specification deviation costs once it reaches the shop floor, and I automate the analysis around it.

> **Where I sit:** between hard petroleum engineering — API 6A/6D, ASME, ASTM, well and production data — and operating data: Python, SQL, machine learning and workflow automation.

| | |
| :--- | :--- |
| 🔧 **Technical compliance** | Review and validate engineering documentation for ball, control, butterfly and retention valves against **API 6D, API 6A, ASME B16.34, ASME B16.5** and **ASTM** — detecting data sheet deviations *before* manufacturing starts, not after. |
| 🚚 **Expediting & delivery risk** | Coordinate critical deliveries with the shop floor, anticipate blockers, and report status to operators with numbers instead of optimism. |
| 📊 **Well & production data** | Certified in **OpenWells, Data Analyzer and PROFILE** (Halliburton Landmark). Production analytics, GOR/RGP modelling, well KPIs, reservoir characterization. |
| ⚙️ **Automation & AI** | Python and SQL pipelines, scikit-learn models, n8n workflows, API integrations, Docker. Certified in **AI Automation, advanced level**. |

---

<a id="proof"></a>
## 📈 Proof, not adjectives

| | |
| :---: | :--- |
| **146** | certified hours across petroleum data science, industrial software and technical communication |
| **174,815** | raw well-month records processed in the project awarded a **special mention** by Fundación Sadosky & Fundación YPF |
| **125,018** | records surviving a documented cleaning policy (non-physical production removed, p99.5 outlier cap) |
| **5** | regression models compared under 5-fold cross-validation, with a cost/benefit call, not just a leaderboard |

---

## 🧭 Tech stack

<table>
<tr><td><b>Petroleum & operations</b></td><td>

`API 6A / 6D` `ASME B16.34 / B16.5` `ASTM` `OpenWells` `Data Analyzer` `PROFILE` `Aspen HYSYS` `QROD` `E&P concepts` `Reservoir & production`

</td></tr>
<tr><td><b>Data & code</b></td><td>

`Python` `pandas` `NumPy` `scikit-learn` `SQL` `Matplotlib` `Seaborn` `Jupyter`

</td></tr>
<tr><td><b>Automation & delivery</b></td><td>

`n8n` `FastAPI` `Docker` `REST APIs` `Git` `SAP ERP` `Excel + VBA`

</td></tr>
</table>

---

<a id="work"></a>
## 📂 Selected work

| Project | What it is | Stack |
| :--- | :--- | :--- |
| 🔬 **[well-production-data-mining](https://github.com/Lucas-Arteaga/well-production-data-mining)** | CRISP-DM data mining over official Argentine per-well production data: business filters, percentile-based categorisation, Self-Organizing Map (20×20) plus KMeans over the SOM weights, and cluster profiling. | `Python` `pandas` `MiniSom` `scikit-learn` `Jupyter` |
| 🏅 **GOR / RGP regression comparison** | Course project at Fundación Sadosky & Fundación YPF — **awarded a special mention**. Cleaned 174,815 well-month records down to 125,018 with a documented policy, log-transformed a heavily skewed target, and compared a linear baseline against decision trees and random forests under 5-fold cross-validation. Chose a 50-tree forest over a 100-tree one for near-identical accuracy at half the training cost. | `Python` `pandas` `scikit-learn` `Seaborn` |

> 🔨 **In progress** — a reproducible production analytics pipeline over Argentina's **official open well-production dataset** (Secretaría de Energía, CC-BY-4.0): validated ingestion, data-quality reporting, basin and operator profiling, and GOR modelling. The data is public, so anyone can run it.

---

<a id="certifications"></a>
## 🎓 Certifications

| Certification | Issuer | Year | Hours |
| :--- | :--- | :---: | :---: |
| **OpenWells, Data Analyzer & PROFILE** — code `NWS-2026-016` | Next Well Solutions / Halliburton Landmark | 2026 | 12 |
| **Data Science for Petroleum Engineers: first steps into AI** — *special mention* for *Comparison of regression models for GOR prediction* | Fundación Sadosky & Fundación YPF | 2025 | 48 |
| **AI Automation, advanced level** | Coderhouse | 2026 | 20 |
| **Microsoft Excel, advanced level** — certificate 12321 | UTEPSA Postgrado | 2025 | 30 |
| **SAP and Excel integration with script** — certificate 12405 | UTEPSA Postgrado | 2025 | 24 |
| **Public speaking and Storytelling** — Res. (D) 5849/24 | Universidad de Buenos Aires, Facultad de Derecho | 2024 | 12 |
| **Gas Plant Operator** | Instituto Tecnológico de la Patagonia | — | — |

---

<a id="how-i-work"></a>
## 🧠 How I work

Four things I actually do, every time:

**1. Validate before it gets built.** A deviation caught on a data sheet costs a revision. The same deviation caught on the shop floor costs a scrapped part, a delayed delivery and an angry operator. The earlier the check, the cheaper the fix — that is true of data and of valves.

**2. Clean the data before touching the model.** In the project that earned the special mention, 48,533 of 174,815 records were non-physical — zero or negative production. Modelling on top of those would have produced a confident answer to a question nobody asked.

**3. Report the cost of a decision, not just the number.** The 100-tree forest scored 0.57 and the 50-tree forest scored 0.56. The second one trains in half the time. In a plant, that difference decides which one gets deployed.

**4. Say what does not work.** Every analysis has limits. Mine had a snapshot-only dataset, no bottom-hole pressure and no petrophysics — so the model describes wells, it does not predict them. Knowing which of the two you have is most of the job.

---

## 📬 Contact

- **LinkedIn** — [lucas-arteaga-](https://www.linkedin.com/in/lucas-arteaga-/) (best for opportunities)
- **Email** — [larteaga@fi.uba.ar](mailto:larteaga@fi.uba.ar)
- **Based in** Buenos Aires · open to relocation to **Neuquén** (Vaca Muerta)
- **Languages** — Spanish (native) · English (professional working proficiency)

<div align="center">
<sub>Open to Petroleum Engineering, production data, well operations and technical automation roles.</sub>
</div>

---

<a id="español"></a>
<details>
<summary><b>🇪🇸 Leer esta página en castellano</b></summary>

<br>

## 🛠️ Qué hago

Estudiante de quinto año de Ingeniería en Petróleo (UBA), trabajando a tiempo completo en un fabricante de válvulas API que provee a operadoras de Upstream. Reviso especificaciones de ingeniería todos los días, sé cuánto cuesta una desviación de especificación cuando ya llegó al taller, y automaticé el análisis alrededor de eso.

> **Dónde me paro:** entre la ingeniería dura — API 6A/6D, ASME, ASTM, datos de pozo y de producción — y los datos operativos: Python, SQL, machine learning y automatización de flujos.

| | |
| :--- | :--- |
| 🔧 **Cumplimiento técnico** | Reviso y valido documentación de ingeniería de válvulas esféricas, de control, mariposa y retención bajo **API 6D, API 6A, ASME B16.34, ASME B16.5** y **ASTM** — detectando desvíos en data sheets *antes* de que arranque la fabricación, no después. |
| 🚚 **Expediting y riesgo de entrega** | Coordino entregas críticas con planta, anticipo bloqueos y reporto estado a las operadoras con números, no con optimismo. |
| 📊 **Datos de pozo y producción** | Certificado en **OpenWells, Data Analyzer y PROFILE** (Halliburton Landmark). Analítica de producción, modelado de RGP/GOR, KPIs de pozo, caracterización de reservorios. |
| ⚙️ **Automatización e IA** | Pipelines en Python y SQL, modelos con scikit-learn, flujos en n8n, integración de APIs, Docker. Certificado en **AI Automation, nivel avanzado**. |

## 📈 Prueba, no adjetivos

- **146 horas** certificadas entre ciencia de datos aplicada a petróleo, software industrial y comunicación técnica.
- **174.815** registros pozo-mes procesados en el trabajo que recibió **mención especial** de Fundación Sadosky & Fundación YPF.
- **125.018** registros que sobrevivieron a una política de limpieza documentada (se descartó producción no física y se acotaron outliers en el percentil 99,5).
- **5 modelos** de regresión comparados con validación cruzada de 5 folds, con decisión de costo-beneficio y no sólo un ranking.

## 🎓 Certificaciones

| Certificación | Emisor | Año | Horas |
| :--- | :--- | :---: | :---: |
| **OpenWells, Data Analyzer y PROFILE** — código `NWS-2026-016` | Next Well Solutions / Halliburton Landmark | 2026 | 12 |
| **Fundamentos en Ciencias de Datos para Ingenieros en Petróleo: primeros pasos hacia la IA** — *mención especial* por *Comparación de modelos de regresión para la predicción de RGP* | Fundación Sadosky & Fundación YPF | 2025 | 48 |
| **AI Automation, nivel avanzado** | Coderhouse | 2026 | 20 |
| **Microsoft Excel, nivel avanzado** — certificado 12321 | UTEPSA Postgrado | 2025 | 30 |
| **Integración de SAP y Excel con script** — certificado 12405 | UTEPSA Postgrado | 2025 | 24 |
| **Oratoria e Introducción al Storytelling** — Res. (D) 5849/24 | Universidad de Buenos Aires, Facultad de Derecho | 2024 | 12 |
| **Operador de Plantas de Gas** | Instituto Tecnológico de la Patagonia | — | — |

## 🧠 Cómo trabajo

**1. Validar antes de construir.** Una desviación detectada en el data sheet cuesta una revisión. La misma desviación detectada en el taller cuesta una pieza rechazada, una entrega demorada y una operadora enojada. Cuanto más temprano el control, más barata la corrección — vale para datos y vale para válvulas.

**2. Limpiar los datos antes de tocar el modelo.** En el trabajo que ganó la mención, 48.533 de 174.815 registros eran no físicos: producción cero o negativa. Modelar encima de eso habría dado una respuesta segura a una pregunta que nadie hizo.

**3. Reportar el costo de una decisión, no sólo el número.** El bosque de 100 árboles dio 0,57 y el de 50 dio 0,56, entrenando en la mitad del tiempo. En una planta esa diferencia decide cuál se pone en producción.

**4. Decir lo que no funciona.** Todo análisis tiene límites. El mío tenía datos de una sola foto al año, sin presión de fondo ni petrofísica — así que el modelo describe pozos, no los predice. Saber cuál de las dos cosas tenés es la mayor parte del trabajo.

## 📬 Contacto

- **LinkedIn** — [lucas-arteaga-](https://www.linkedin.com/in/lucas-arteaga-/)
- **Email** — [larteaga@fi.uba.ar](mailto:larteaga@fi.uba.ar)
- **Base** Buenos Aires · con disponibilidad de relocalización a **Neuquén** (Vaca Muerta)
- **Idiomas** — español (nativo) · inglés (competencia profesional)

</details>
