<div align="center">

<img src="assets/banner.svg" alt="Nicolás Richardson · xSempiternus" width="100%">

<img src="assets/marquee.svg" alt="Tecnologías: Python, PyTorch, OpenCV, Hugging Face, TensorFlow, FastAPI, Docker, Next.js, Rust y más" width="100%">

**Física aplicada a productos que se pueden medir: visión por computador, modelos de riesgo y software que llega a producción.**

</div>

<img src="assets/divider.svg" width="100%" alt="">

## Qué hago

Soy ingeniero físico (Universidad Andrés Bello). Me muevo entre tres mundos: **modelar** (ML, visión, estadística), **validar** (riesgo de crédito en banca) y **construir** (backend, web y herramientas). Co-fundé **[Fidelya](https://fidelya.cl)**, donde soy CSO; trabajo en visión computacional y ML en **[B&N Solutions](https://www.bnsolutions.cl)**, una consultora tecnológica, y como consultor de financiero en **Management Solutions**.

| | |
|---|---|
| 🔬 **Ciencia** | Visión por computador y ML aplicados a minería, asistencia y salud |
| 🏆 **Premio** | Ganador del **NASA International Space Apps Challenge 2026** con [NOVA](https://github.com/4mser/nova), un médico de a bordo para astronautas |
| 🏗️ **Infraestructura** | Visión por computador para inspeccionar túneles: detección de filtraciones con YOLO |
| 🏦 **Riesgo** | Validación de modelos de riesgo de crédito como consultor |
| 🚀 **Producto** | Fidelya: fidelización y retención con IA para locales físicos |

<img src="assets/divider.svg" width="100%" alt="">

## Proyectos

<table>
<tr>
<td width="50%"><a href="https://github.com/xSempiternus/BermGuard"><img src="assets/card-bermguard.svg" alt="BermGuard AI" width="420"></a></td>
<td width="50%"><a href="https://github.com/xSempiternus/Facial-Recognition-FACUP"><img src="assets/card-facup.svg" alt="FACUP Face ID" width="420"></a></td>
</tr>
<tr>
<td width="50%"><a href="https://www.bnsolutions.cl/filtraciones-tuneles"><img src="assets/card-tuneles.svg" alt="Filtraciones en túneles con YOLO" width="420"></a></td>
<td width="50%"><a href="https://github.com/4mser/nova"><img src="assets/card-nova.svg" alt="NOVA, ganador NASA Space Apps 2026" width="420"></a></td>
</tr>
<tr>
<td width="50%"><a href="https://fidelya.cl"><img src="assets/card-fidelya.svg" alt="Fidelya" width="420"></a></td>
<td width="50%"><a href="https://github.com/xSempiternus/widget-git"><img src="assets/card-brew.svg" alt="Brew" width="420"></a></td>
</tr>
</table>

> **FACUP Face ID** y **BermGuard** son los proyectos donde más medí. FACUP: 97.5% de acierto sin una sola falsa identificación en 735 verificaciones, comparando 4 modelos y 3 detectores. **BermGuard** destaca por cómo está medido: cifras con intervalos de confianza, umbral de operación explícito y decisiones corregidas con registro (ADR) cuando una medición mejor contradijo una anterior.

<img src="assets/divider.svg" width="100%" alt="">

## Filtraciones en túneles: YOLO sobre cámaras de seguridad

Los túneles viales urbanos se filtran, y hoy se inspeccionan a ojo. Si el túnel ya tiene cámaras grabando las 24 horas, ¿por qué no enseñarles a mirar también las filtraciones? Entrené un detector YOLO con ejemplos etiquetados a mano, en tres niveles de severidad (leve, severa y crítica), y lo corrí sobre video real de cuatro tramos de túnel, uno de cada cinco cuadros. El resultado ya no es horas de video: es una lista ordenable con el minuto, la posición, la severidad y la confianza de cada detección.

<table>
<tr>
<td width="55%" align="center"><img src="assets/tuneles-deteccion.gif" alt="El modelo marca filtraciones sobre video de un túnel" width="100%"><br><sub>Detección sobre video real (vehículos difuminados y señalética recortada)</sub></td>
<td width="45%" align="center"><img src="assets/tuneles-severidad.svg" alt="Detecciones por tramo según severidad" width="420"><br><sub>4.252 detecciones brutas en 4 tramos</sub></td>
</tr>
</table>

- **76%** de las detecciones son humedad leve, **23%** severas y **menos del 1%** críticas: el filtro automático deja a la vista lo que un equipo de mantención debería revisar primero.
- Es un prototipo de investigación: las detecciones son brutas y **aún no se validan contra un conteo humano**, así que no declaro una precisión. Una misma filtración puede aparecer en varios cuadros.
- Lo escribí como artículo de divulgación en B&N Solutions: [Detección de filtraciones en túneles con YOLO](https://www.bnsolutions.cl/filtraciones-tuneles).

<img src="assets/divider.svg" width="100%" alt="">

## Fidelya: fidelización e inteligencia de clientes

Co-fundé **[Fidelya](https://fidelya.cl)** y soy su CSO. Es una plataforma para locales gastronómicos: carta con QR, pedido desde la mesa, club de puntos, app para el equipo de sala y **AURA**, que recomienda a cada cliente lo que le gusta y trae de vuelta a los que dejaron de venir.

<table>
<tr>
<td width="32%" align="center" valign="top"><img src="assets/fidelya-app.gif" alt="App de meseros de Fidelya: mesas, llamado del cliente y perfil del socio" width="280"><br><sub>App de meseros (<a href="https://fidelya.cl">fidelya.cl</a>)</sub></td>
<td width="68%" valign="top">

**Lo que diseñé y construí como CSO**

- **AURA Analytics:** un sistema MCP sobre LLMs locales (Ollama) que detecta clientes en riesgo de abandono y sugiere campañas.
- **Chatbot de postventa con RAG** para los dueños de locales.
- **Content Studio:** un orquestador que combina un LLM y una API de imágenes para producir reels y publicidad con el estilo visual de la marca.
- **Módulo de validación y QA** para monitorear sesiones y errores, y un generador de propuestas comerciales por rubro.
- **Mascota 3D en Blender** y videos promocionales con AMBAR Studio.

</td>
</tr>
</table>

<img src="assets/divider.svg" width="100%" alt="">

## En acción

<table>
<tr>
<td width="50%" align="center"><img src="assets/bermguard-hero.gif" alt="BermGuard: pretil y proximidad entre equipos en un botadero" width="100%"><br><sub><b>BermGuard</b> · pretil y proximidad entre equipos (videos generados con IA)</sub></td>
<td width="50%" align="center"><img src="assets/facup-demo.gif" alt="FACUP: panel del staff con datos de prueba" width="100%"><br><sub><b>FACUP</b> · panel del staff (sede demo, datos de prueba)</sub></td>
</tr>
<tr>
<td width="50%" align="center"><img src="assets/nova-ar-cpr.gif" alt="NOVA: guía de RCP con realidad aumentada" width="100%"><br><sub><b>NOVA</b> · guía de RCP con realidad aumentada</sub></td>
<td width="50%" align="center"><img src="assets/bermguard-detector-propio.png" alt="BermGuard: el detector propio separa al CAEX y al bulldozer en dos cajas" width="389"><br><sub><b>BermGuard</b> · detector propio: dos máquinas, dos cajas (el modelo COCO las juntaba en una)</sub></td>
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
| **2024** | Ingeniero de ML en VASCOLAB (YOLO para detectar filtraciones en túneles) y egreso de Ingeniería Física, UNAB |
| **Oct 2025** | Co-fundador y CSO de Fidelya; consultor de datos en riesgo de crédito |
| **2026** | Visión computacional y ML en B&N Solutions |
| **Nov 2026** | 🏆 Ganador del NASA International Space Apps Challenge con NOVA |

<img src="assets/divider.svg" width="100%" alt="">

## Divulgación

Publiqué un artículo en [B&N Solutions](https://www.bnsolutions.cl/filtraciones-tuneles) sobre la detección de filtraciones en túneles. Tengo otros cuadernos de divulgación en preparación, aún sin publicar. Este es uno: **la flecha del tiempo**, con tres experimentos interactivos. En el primero, un gas simulado molécula por molécula llena un frasco y, al invertir el tiempo, cada molécula recorre su camino al revés y el gas vuelve al cuello, mientras la curva de entropía sube y baja.

<div align="center">
<img src="assets/entropia-frasco.gif" alt="Experimento del frasco: el gas se esparce, se invierte el tiempo y la entropía baja" width="70%">
<br><sub>Borrador del cuaderno «La flecha del tiempo» · simulación basada en <a href="https://github.com/4mser/bn-lab-simulations">BN Lab Simulations</a> (MIT)</sub>
</div>

<img src="assets/divider.svg" width="100%" alt="">

## Stack

<div align="center">
<img src="assets/stack.svg" alt="Stack: ciencia, modelos e IA, backend y producto" width="100%">
</div>

## Cómo encaja todo

```mermaid
flowchart LR
    F["Física y estadística"] --> M["Modelos<br/>ML · visión · riesgo"]
    M --> B["BermGuard<br/>minería"]
    M --> A["FACUP Face ID<br/>asistencia"]
    M --> D["Fidelya · AURA<br/>retención"]
    M --> N["NOVA<br/>salud a bordo"]
    M --> E["Túneles<br/>inspección"]
    T["Backend y herramientas<br/>FastAPI · Next.js · Docker"] --> B
    T --> A
    T --> D
    T --> N
    T --> E
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

**¿Hablamos?** &nbsp;·&nbsp; [B&N Solutions](https://www.bnsolutions.cl) &nbsp;·&nbsp; [LinkedIn](https://linkedin.com/in/nicolas-richardson-rojas) &nbsp;·&nbsp; [fidelya.cl](https://fidelya.cl) &nbsp;·&nbsp; [GitHub](https://github.com/xSempiternus) &nbsp;·&nbsp; [Hugging Face](https://huggingface.co/xSempiternus)

<sub>Escrito con señal, no con ruido.</sub>

</div>
