```text
[boot] franco.zimmermann v2026.10
[ ok ] base ......... Madrid, ES
[ ok ] carrera ...... Ing. Informática · UEM
[ ok ] estudio ...... Zimmy · zimmy.eu
[ ok ] idiomas ...... es (nativo) · en (B2)
[ ok ] modelos ...... llama3.2 · qwen2.5 · nomic-embed
[ ok ] sensores ..... DHT22 · HC-SR04 · LDR · MQ-2
[warn] objetivo ..... IA aplicada + ciberseguridad
> listo. escribe "proyectos"_
```

Me gusta que las cosas **funcionen fuera de la diapositiva**: un LLM que responda con fuentes sin mandar tus datos a ningún servidor, una maqueta que mida gas y temperatura de verdad, una app que lea un ticket arrugado.

Todo lo que construyo lo reúno en **[Zimmy](https://zimmy.eu)**, mi estudio de tecnología: cada proyecto tiene su página con capturas, demos y lo que fui aprendiendo por el camino.

En abril de 2026 crucé a Suiza con la UEM para el **XVIII IT Seminar** (HES-SO Valais-Wallis) y dimos en equipo un taller de **RAG** a estudiantes y profesores de otros países. De ahí salió buena parte de lo que hay abajo.

---

### `> proyectos`

**[Obexis](https://zimmy.eu/#obexis)** — *mirar el enlace antes de morder.*

El proyecto en el que estoy centrado ahora: un sistema que te avisa de si un enlace es una estafa antes de que lo abras, aunque nadie lo haya denunciado todavía. Está en desarrollo; iré contando más a medida que avance.
`Python` `Machine learning` `Ciberseguridad`

**[Buzón de reportes](https://zimmy.eu/reportar/)** — *¿te llegó un SMS raro? Mándalo.*

Web pública para enviar SMS, correos y códigos QR sospechosos. Los datos personales se borran en tu navegador antes de enviar, no pide cuenta y cada envío tiene un código para borrarlo. Con ello se arma la primera colección abierta de estafas por SMS en español.
`JavaScript` `Cloudflare Pages` `D1` `R2` `Turnstile`

**[Zynthra-AI](https://github.com/FrancoZimm/Zynthra-AI)** — *un ChatGPT para estudiar que no te hace los deberes.*

RAG 100 % local que cita la fuente de cada respuesta y detecta cuándo le estás pidiendo que copie: ahí cambia a tutor socrático y te hace preguntas en vez de darte el ensayo.
`Python` `FastAPI` `React` `Ollama` `MongoDB`

**[REN](https://github.com/FrancoZimm/Proyect_RAG_Rena)** — *el asistente que llevamos a Suiza.*

Le pasas PDFs, fotos o un audio; los convierte a texto (OCR / Whisper), los indexa y responde con evidencia. Si no encuentra nada en tus documentos, busca en la web en lugar de inventárselo.
`Python` `Streamlit` `Ollama` `EasyOCR` `faster-whisper`

**[Tiquetario](https://github.com/FrancoZimm/tiquetario)** — *tus gastos, desde la foto del ticket.*

PWA instalable que lee el ticket en el propio móvil (Tesseract.js), saca el total y lo guarda por etiquetas, con presupuesto mensual, estadísticas y exportación a CSV y PDF. Sin cuentas y sin enviar las fotos a ningún sitio. [Pruébala aquí](https://francozimm.github.io/tiquetario/).
`JavaScript` `PWA` `Tesseract.js` `IndexedDB`

**[AureaTech](https://github.com/FrancoZimm/aureatech-smart-zone)** — *un barrio en miniatura que se vigila solo.*

Maqueta IoT con ESP32: las farolas se encienden al paso de la gente y de noche, y una ESP32-CAM controla el acceso de vehículos. Me encargué del reconocimiento de matrículas con un modelo YOLO entrenado para ello. Proyecto en equipo de 4.
`ESP32` `ESP32-CAM` `YOLO` `Python` `Flet` `MariaDB`

**[Coche RC con ESP32](https://github.com/FrancoZimm/esp32-rc-car)** — *se maneja desde el móvil y frena solo antes de chocar.*

Dos motores con L298N, control por Bluetooth desde una app de MIT App Inventor o un mando externo, un mando con M5Stack por WiFi + MQTT, y un HC-SR04 que baja la velocidad y bloquea el avance si hay algo delante. Proyecto en equipo de 3.
`ESP32` `M5Stack` `MQTT` `Bluetooth` `App Inventor` `C++`

**[Order Manager](https://github.com/FrancoZimm/order-manager-java)** — *gestión de pedidos de escritorio, en euros o dólares.*

App Java Swing con arquitectura MVC: CRUD de pedidos con persistencia JSON, tipo de cambio en tiempo real, pruebas con JUnit 5 y CI con GitHub Actions.
`Java` `Swing` `Maven` `JUnit 5` `GitHub Actions`

---

### `> stack`

<p>
  <img src="https://skillicons.dev/icons?i=java,python,cpp,js,html,css,react,fastapi,mysql,mongodb,arduino,cloudflare,git,github,idea,vscode,matlab&perline=9" alt="stack" />
</p>

| Área | Tecnologías |
|---|---|
| **Lenguajes** | Java · Python · C++ · JavaScript |
| **IA** | LLMs · RAG · embeddings · Ollama · machine learning |
| **Seguridad** | detección de phishing · anonimización de datos · Cloudflare Zero Trust |
| **Web** | HTML · CSS · PWA · FastAPI · React · Cloudflare Pages · GitHub Pages · Selenium |
| **Datos** | SQL · MySQL · MariaDB · MongoDB · Cloudflare D1 |
| **Hardware / IoT** | ESP32 · Arduino · Microchip Studio (ensamblador) |
| **Redes** | configuración y gestión de redes |
| **Herramientas** | Git · GitHub · IntelliJ IDEA · Visual Studio · MATLAB · PlantUML · Trello · Canva |

---

### `> certificaciones`

```text
2025  Inteligencia Artificial (intermedio) ... UEM
2025  Introducción al IoT .................... Cisco
      Introducción a IBM Z ................... IBM
2024  MATLAB Onramp + Mat. simbólicas ........ MathWorks
2023  Inglés B2 .............................. CUI, Argentina
```

---

### `> cómo trabajo`

Uso asistentes de IA como copiloto: para generar boilerplate, revisar código y documentar. Las ideas, la arquitectura, las pruebas y que todo funcione de punta a punta son cosa mía. Cada repo indica dónde me apoyé en ellos.

---

### `> contacto`

[zimmy.eu](https://zimmy.eu) · [LinkedIn](https://www.linkedin.com/in/franco-zimmermann-468116355) · [zmmr.fran@gmail.com](mailto:zmmr.fran@gmail.com) · Madrid, España

Si te interesa la IA local, el IoT o tienes una idea rara que quieras montar con un ESP32, escríbeme.
