<div align="center">

<img src="assets/nous-web.gif" alt="Intro del sitio de Nous Diseño: un monito con boina corre, salta un portal y escribe «Nous Diseño» con un pincel" width="640">

<sub>La intro de la página de <b>Nous Diseño</b>: un monito con boina que escribe el nombre del estudio con un pincel. La dibujé en Canvas, sin librerías.</sub>

# Nicolás Richardson

**Ingeniero físico. Mido cosas con visión por computador y las cuento con diseño web.**

[B&N Solutions](https://www.bnsolutions.cl) · [Fidelya](https://fidelya.cl) · [LinkedIn](https://linkedin.com/in/nicolas-richardson-rojas) · [Hugging Face](https://huggingface.co/xSempiternus)

</div>

---

Soy ingeniero físico (Universidad Andrés Bello). Entreno modelos de visión y de riesgo, y también hago la parte que se ve: sitios, animaciones y herramientas. Co-fundé **[Fidelya](https://fidelya.cl)**, donde soy CSO; trabajo en visión computacional y ML en **[B&N Solutions](https://www.bnsolutions.cl)** y como consultor de datos en **Management Solutions**.

🏆 En noviembre de 2026 gané el **NASA International Space Apps Challenge** con [NOVA](https://github.com/4mser/nova), un médico de a bordo para astronautas.

## Lo que hago

<table>
<tr>
<td width="50%" valign="top">

### 🔬 Visión por computador y modelos

- **Minería:** segmentar el pretil de seguridad de un botadero y vigilar la distancia entre equipos.
- **Asistencia:** reconocimiento facial en escuelas de fútbol.
- **Infraestructura:** filtraciones en túneles con YOLO sobre cámaras de seguridad.
- **Salud:** parpadeo y fatiga con la cámara del teléfono.
- **Banca:** validación de modelos de riesgo de crédito.

</td>
<td width="50%" valign="top">

### 🎨 Web, animación y producto

- **Sitios y animación** para estudios de diseño, como Nous Diseño.
- **Fidelya:** fidelización con IA para locales gastronómicos.
- **Videos** de producto y divulgación con AMBAR Studio.
- **Mascotas y escenas 3D** en Blender.
- **Divulgación científica** con simulaciones interactivas.

</td>
</tr>
</table>

## Proyectos

<div align="center">
<img src="assets/visor-proyectos.svg" alt="Visor que recorre mis proyectos: Nous Diseño, BermGuard, FACUP, NOVA, filtraciones en túneles y Fidelya" width="760">
</div>

<br>

- **Nous Diseño** · sitio web con la intro animada del monito (la de arriba).
- **[BermGuard](https://github.com/xSempiternus/BermGuard)** · pretil y proximidad entre equipos en minería. Docker. Videos generados con IA.
- **[FACUP Face ID](https://github.com/xSempiternus/Facial-Recognition-FACUP)** · asistencia en escuelas de fútbol, con datos de prueba.
- **[NOVA](https://github.com/4mser/nova)** · ganador NASA Space Apps 2026. Mi parte: salud ocular, más abajo.
- **[Filtraciones en túneles](https://www.bnsolutions.cl/filtraciones-tuneles)** · YOLO sobre video real. Vehículos difuminados y señalética recortada.
- **[Fidelya](https://fidelya.cl)** · carta con QR, club de puntos, app para el equipo de sala y AURA.

> **FACUP** y **BermGuard** son donde más medí. En BermGuard hay cifras con intervalos de confianza, un umbral de operación explícito y decisiones corregidas con registro (ADR) cuando una medición mejor contradijo una anterior.

## Con más detalle

<details>
<summary><b>Filtraciones en túneles: YOLO sobre cámaras de seguridad</b></summary>

<br>

Los túneles viales urbanos se filtran, y hoy se inspeccionan a ojo. Si ya hay cámaras grabando las 24 horas, ¿por qué no enseñarles a mirar también las filtraciones? Entrené un detector YOLO con ejemplos etiquetados a mano, en tres niveles de severidad (leve, severa y crítica), y lo corrí sobre video real de cuatro tramos, uno de cada cinco cuadros. El resultado es una lista ordenable con el minuto, la posición, la severidad y la confianza de cada detección.

<img src="assets/tuneles-severidad.svg" alt="Detecciones por tramo según severidad" width="420">

- **76%** de las detecciones son humedad leve, **23%** severas y **menos del 1%** críticas.
- Es un prototipo de investigación: las detecciones son brutas y **aún no se validan contra un conteo humano**, así que no declaro una precisión. Una misma filtración puede aparecer en varios cuadros.
- Artículo de divulgación: [Detección de filtraciones en túneles con YOLO](https://www.bnsolutions.cl/filtraciones-tuneles).

</details>

<details>
<summary><b>Fidelya: lo que diseñé y construí como CSO</b></summary>

<br>

- **AURA Analytics:** un sistema MCP sobre LLMs locales (Ollama) que detecta clientes en riesgo de abandono y sugiere campañas.
- **Chatbot de postventa con RAG** para los dueños de locales.
- **Content Studio:** un orquestador que combina un LLM y una API de imágenes para producir reels y publicidad con el estilo visual de la marca.
- **Módulo de validación y QA** para monitorear sesiones y errores, y un generador de propuestas comerciales por rubro.
- **Mascota 3D en Blender** y videos promocionales con AMBAR Studio.

</details>

<details>
<summary><b>NOVA: salud ocular con visión por computador</b></summary>

<br>

Diseñé el módulo que mira los ojos de la tripulación con la cámara del teléfono. Parte del Face Landmarker de Google (MediaPipe, 478 puntos con iris) y mide:

- la distancia margen-reflejo del párpado superior e inferior (MRD1 y MRD2, normalizada por el diámetro del iris),
- cuántas veces y por cuánto tiempo parpadea la persona (parpadeo y PERCLOS),
- todo contra su propia línea base, y con abstención cuando la calidad de la imagen no alcanza.

Corre en CPU, con una mediana de ~8 ms por cuadro. Ahora lo estoy entrenando para detectar bostezos; esa parte es exploratoria. NOVA no es un dispositivo médico ni diagnostica: la salida es una alerta de seguimiento. El código está en un repositorio privado.

<img src="assets/nova-ocular-pasos.png" alt="De la cámara a la alerta, en 4 pasos" width="100%">
<img src="assets/nova-ocular-mediciones.png" alt="Cuatro mediciones y qué tan sólidas son" width="100%">

</details>

<details>
<summary><b>Divulgación: «La flecha del tiempo»</b></summary>

<br>

Tengo cuadernos de divulgación en preparación, aún sin publicar. Este es uno, con tres experimentos interactivos. En el primero, un gas simulado molécula por molécula llena un frasco y, al invertir el tiempo, cada molécula recorre su camino al revés y el gas vuelve al cuello, mientras la curva de entropía sube y baja.

<img src="assets/entropia-frasco.gif" alt="Experimento del frasco: el gas se esparce, se invierte el tiempo y la entropía baja" width="70%">

<sub>Borrador · simulación basada en <a href="https://github.com/4mser/bn-lab-simulations">BN Lab Simulations</a> (MIT)</sub>

</details>

<details>
<summary><b>BermGuard: el detector propio</b></summary>

<br>

<img src="assets/bermguard-detector-propio.png" alt="BermGuard: el detector propio separa al CAEX y al bulldozer en dos cajas" width="389">

<sub>Dos máquinas, dos cajas. El modelo COCO las juntaba en una.</sub>

</details>

<details>
<summary><b>Trayectoria</b></summary>

<br>

| | |
|---|---|
| **2023** | Práctica en el Instituto Milenio SAPHIR: detector de partículas alpha con fibras ópticas |
| **2024** | Ingeniero de ML en VASCOLAB (YOLO para detectar filtraciones en túneles) y egreso de Ingeniería Física, UNAB |
| **Oct 2025** | Co-fundador y CSO de Fidelya; consultor de datos en riesgo de crédito |
| **2026** | Visión computacional y ML en B&N Solutions |
| **Nov 2026** | 🏆 Ganador del NASA International Space Apps Challenge con NOVA |

</details>

<details>
<summary><b>Stack y laboratorio</b></summary>

<br>

`Python` `PyTorch` `OpenCV` `Hugging Face` `TensorFlow` `FastAPI` `Docker` `Next.js` `NestJS` `MongoDB` `Rust` `Blender` `Canvas`

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

---

<div align="center">

**¿Hablamos?** · [B&N Solutions](https://www.bnsolutions.cl) · [LinkedIn](https://linkedin.com/in/nicolas-richardson-rojas) · [fidelya.cl](https://fidelya.cl) · [Hugging Face](https://huggingface.co/xSempiternus)

</div>
