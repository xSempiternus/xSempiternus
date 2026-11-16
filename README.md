<div align="center">

<img src="assets/banner.svg" alt="Nicolás Richardson · xSempiternus" width="100%">

<p>
<img src="https://img.shields.io/badge/Python-25231a?style=for-the-badge&logo=python&logoColor=d9d3ad" alt="Python">
<img src="https://img.shields.io/badge/Computer%20Vision-25231a?style=for-the-badge&logo=opencv&logoColor=7fb8b2" alt="Computer Vision">
<img src="https://img.shields.io/badge/FastAPI-25231a?style=for-the-badge&logo=fastapi&logoColor=d9d3ad" alt="FastAPI">
<img src="https://img.shields.io/badge/Next.js-25231a?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js">
<img src="https://img.shields.io/badge/Docker-25231a?style=for-the-badge&logo=docker&logoColor=7fb8b2" alt="Docker">
</p>

**Física aplicada a productos que se pueden medir: visión por computador, modelos de riesgo y software que llega a producción.**

</div>

<img src="assets/divider.svg" width="100%" alt="">

## Qué hago

Soy ingeniero físico (Universidad Andrés Bello). Me muevo entre tres mundos: **modelar** (ML, visión, estadística), **validar** (riesgo de crédito en banca) y **construir** (backend, web y herramientas). Co-fundé **[Fidelya](https://fidelya.cl)**, donde soy CSO.

| | |
|---|---|
| 🔬 **Ciencia** | Visión por computador y ML aplicados a minería, asistencia y salud |
| 🏆 **Premio** | Ganador del **NASA International Space Apps Challenge 2026** con [NOVA](https://github.com/4mser/nova), un médico de a bordo para astronautas |
| 🏦 **Riesgo** | Validación de modelos de riesgo de crédito como consultor |
| 🚀 **Producto** | Fidelya: fidelización y retención con IA para locales físicos |

<img src="assets/divider.svg" width="100%" alt="">

## Proyectos

<table>
<tr>
<td width="50%"><a href="https://github.com/xSempiternus/BermGuard"><img src="assets/card-bermguard.svg" alt="BermGuard AI"></a></td>
<td width="50%"><a href="https://github.com/xSempiternus/Facial-Recognition-FACUP"><img src="assets/card-facup.svg" alt="FACUP Face ID"></a></td>
</tr>
<tr>
<td width="50%"><a href="https://github.com/4mser/nova"><img src="assets/card-nova.svg" alt="NOVA, ganador NASA Space Apps 2026"></a></td>
<td width="50%"><a href="https://fidelya.cl"><img src="assets/card-fidelya.svg" alt="Fidelya"></a></td>
</tr>
</table>

> **FACUP Face ID** y **BermGuard** son los proyectos donde más medí. FACUP: 97.5% de acierto sin una sola falsa identificación en 735 verificaciones, comparando 4 modelos y 3 detectores. **BermGuard** destaca por cómo está medido: cifras con intervalos de confianza, umbral de operación explícito y decisiones corregidas con registro (ADR) cuando una medición mejor contradijo una anterior.

<img src="assets/divider.svg" width="100%" alt="">

## En acción

<table>
<tr>
<td width="50%" align="center"><img src="assets/bermguard-hero.gif" alt="BermGuard: pretil y proximidad entre equipos en un botadero" width="100%"><br><sub><b>BermGuard</b> · pretil y proximidad entre equipos (videos generados con IA)</sub></td>
<td width="50%" align="center"><img src="assets/facup-demo.gif" alt="FACUP: panel del staff con datos de prueba" width="100%"><br><sub><b>FACUP</b> · panel del staff (sede demo, datos de prueba)</sub></td>
</tr>
<tr>
<td width="50%" align="center"><img src="assets/nova-ar-cpr.gif" alt="NOVA: guía de RCP con realidad aumentada" width="100%"><br><sub><b>NOVA</b> · guía de RCP con realidad aumentada</sub></td>
<td width="50%" align="center"><img src="assets/nova-emergency.gif" alt="NOVA: protocolos de emergencia" width="100%"><br><sub><b>NOVA</b> · protocolos de emergencia paso a paso</sub></td>
</tr>
</table>

<img src="assets/divider.svg" width="100%" alt="">

## Mi parte en NOVA: salud ocular con visión por computador

Diseñé el módulo que mira los ojos de la tripulación con la cámara del teléfono. Parte del Face Landmarker de Google (MediaPipe, 478 puntos con iris) y mide:

- la distancia margen-reflejo del párpado superior e inferior (MRD1 y MRD2, en versión normalizada por el diámetro del iris),
- cuántas veces y por cuánto tiempo parpadea la persona (parpadeo y PERCLOS),
- todo contra su propia línea base, y con abstención cuando la calidad de la imagen no alcanza.

Corre en CPU, con una mediana de ~8 ms por cuadro. Ahora lo estoy entrenando para detectar bostezos; esa parte es exploratoria. NOVA no es un dispositivo médico ni diagnostica: la salida es una alerta de seguimiento. El código está en un repositorio privado.

<table>
<tr>
<td width="50%"><img src="assets/nova-ocular-pasos.png" alt="De la cámara a la alerta, en 4 pasos" width="100%"></td>
<td width="50%"><img src="assets/nova-ocular-mediciones.png" alt="Cuatro mediciones y qué tan sólidas son" width="100%"></td>
</tr>
</table>

<img src="assets/divider.svg" width="100%" alt="">

## Trayectoria

| | |
|---|---|
| **2023** | Práctica en el Instituto Milenio SAPHIR: detector de partículas alpha con fibras ópticas |
| **2024** | Ingeniero de ML en VASCOLAB (visión para túneles) y egreso de Ingeniería Física, UNAB |
| **Oct 2025** | Co-fundador y CSO de Fidelya; consultor de datos en riesgo de crédito |
| **2026** | Visión computacional y ML en B&N Solutions |
| **Nov 2026** | 🏆 Ganador del NASA International Space Apps Challenge con NOVA |

<img src="assets/divider.svg" width="100%" alt="">

## Divulgación

Escribo cuadernos de divulgación científica para [B&N Solutions](https://bnsolutions.cl): física, tiempo y entropía, con experimentos interactivos como el efecto mariposa. Las simulaciones del laboratorio son abiertas en [`bn-lab-simulations`](https://github.com/4mser/bn-lab-simulations): 40 experimentos de física y matemáticas para la web.

<img src="assets/divider.svg" width="100%" alt="">

## Stack, en órbita

<div align="center">
<img src="assets/orbit.svg" alt="Stack: ciencia, backend y producto" width="560">
</div>

## Cómo encaja todo

```mermaid
flowchart LR
    F["Física y estadística"] --> M["Modelos<br/>ML · visión · riesgo"]
    M --> B["BermGuard<br/>minería"]
    M --> A["FACUP Face ID<br/>asistencia"]
    M --> D["Fidelya · AURA<br/>retención"]
    M --> N["NOVA<br/>salud a bordo"]
    T["Backend y herramientas<br/>FastAPI · Next.js · Docker"] --> B
    T --> A
    T --> D
    T --> N
    T --> W["Brew<br/>git en VSCode"]
```

<details>
<summary><b>🧪 Laboratorio: análisis y experimentos</b></summary>

<br>

| Repo | Qué es |
|---|---|
| [`widget-git` (Brew)](https://github.com/xSempiternus/widget-git) | Widget de VSCode tipo cafetería para check, pull, commit y push de git |
| [`fastapi-sandbox`](https://github.com/xSempiternus/fastapi-sandbox) | Laboratorio de APIs REST con FastAPI, Pydantic y frontend |
| [`Exploratory-analisis-using-kmeans-of-instacart-data`](https://github.com/xSempiternus/Exploratory-analisis-using-kmeans-of-instacart-data) | Segmentación de clientes con k-means |
| [`Project1-PredictingBitcoinPrices`](https://github.com/xSempiternus/Project1-PredictingBitcoinPrices) | Predicción de precio con ML |
| [`climate-change-analysis.`](https://github.com/xSempiternus/climate-change-analysis.) | Análisis de cambio climático |
| [`Netflix-data-analysis`](https://github.com/xSempiternus/Netflix-data-analysis) | Análisis exploratorio de datos |
| [`voicecloning-linux`](https://github.com/xSempiternus/voicecloning-linux) | Clonación de voz en Linux |
| [`portafolio`](https://github.com/xSempiternus/portafolio) | Mi portafolio web |

</details>

<img src="assets/divider.svg" width="100%" alt="">

<div align="center">

**¿Hablamos?** &nbsp;·&nbsp; [LinkedIn](https://linkedin.com/in/nicolas-richardson-rojas) &nbsp;·&nbsp; [fidelya.cl](https://fidelya.cl) &nbsp;·&nbsp; [GitHub](https://github.com/xSempiternus) &nbsp;·&nbsp; [Hugging Face](https://huggingface.co/xSempiternus)

<sub>Escrito con señal, no con ruido.</sub>

</div>
