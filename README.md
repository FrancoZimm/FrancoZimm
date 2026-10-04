```text
[boot] franco.zimmermann v2026.10
[ ok ] base ......... Madrid, ES
[ ok ] carrera ...... Ing. Informática · UEM
[ ok ] idiomas ...... es (nativo) · en (B2)
[ ok ] modelos ...... llama3.2 · qwen2.5 · nomic-embed
[ ok ] sensores ..... DHT22 · HC-SR04 · LDR · MQ-2
[warn] objetivo ..... IA aplicada + ciberseguridad
> listo. escribe "proyectos"_
```

Me gusta que las cosas **funcionen fuera de la diapositiva**: un LLM que responda con fuentes sin mandar tus datos a ningún servidor, una maqueta que mida gas y temperatura de verdad, una app que lea un ticket arrugado.

En abril de 2026 crucé a Suiza con la UEM para el **XVIII IT Seminar** (HES-SO Valais-Wallis) y dimos en equipo un taller de **RAG** a estudiantes y profesores de otros países. De ahí salió buena parte de lo que hay abajo.

---

### `> proyectos`

**[Zynthra-AI](https://github.com/FrancoZimm/Zynthra-AI)** — *un ChatGPT para estudiar que no te hace los deberes.*

RAG 100 % local que cita la fuente de cada respuesta y detecta cuándo le estás pidiendo que copie: ahí cambia a tutor socrático y te hace preguntas en vez de darte el ensayo.
`Python` `FastAPI` `React` `Ollama` `MongoDB`

**[RENATA (REN)](https://github.com/FrancoZimm/Proyect_RAG_Rena)** — *el asistente que llevamos a Suiza.*

Le pasas PDFs, fotos o un audio; los convierte a texto (OCR / Whisper), los indexa y responde con evidencia. Si no encuentra nada en tus documentos, busca en la web en lugar de inventárselo.
`Python` `Streamlit` `Ollama` `EasyOCR` `faster-whisper`

**[AureaTech](https://github.com/FrancoZimm/aureatech-smart-zone)** — *un barrio en miniatura que se vigila solo.*

Maqueta IoT con ESP32: las farolas se encienden al paso de la gente y de noche, y una ESP32-CAM controla el acceso de vehículos. Me encargué del reconocimiento de matrículas con un modelo YOLO entrenado para ello. Proyecto en equipo de 4.
`ESP32` `ESP32-CAM` `YOLO` `Python` `Flet` `MariaDB`

**Tiquetario** — *tus gastos, desde la foto del ticket.*

PWA instalable en Android que hace OCR en el propio móvil (Tesseract.js), saca total, IVA y productos, y te dice en qué comercio y categoría se te va el dinero.
`JavaScript` `PWA` `Tesseract.js`

**[Coche RC con ESP32](https://github.com/FrancoZimm/esp32-rc-car)** — *se maneja desde el móvil y frena solo antes de chocar.*

Dos motores con L298N, control por Bluetooth desde una app de MIT App Inventor o un mando externo, y un HC-SR04 que baja la velocidad y bloquea el avance si hay algo delante.
`ESP32` `Arduino` `C++` `Bluetooth` `App Inventor`

**[Order Manager](https://github.com/FrancoZimm/order-manager-java)** — *gestión de pedidos de escritorio, en euros o dólares.*

App Java Swing con arquitectura MVC: CRUD de pedidos con persistencia JSON, tipo de cambio en tiempo real, pruebas con JUnit 5 y CI con GitHub Actions.
`Java` `Swing` `Maven` `JUnit 5` `GitHub Actions`

---

### `> stack`

<p>
  <img src="https://skillicons.dev/icons?i=java,python,cpp,js,html,css,react,fastapi,mysql,mongodb,arduino,git,github,idea,vscode,matlab&perline=8" alt="stack" />
</p>

| | |
|---|---|
| **Lenguajes** | Java · Python · C++ · JavaScript |
| **IA** | LLMs · RAG · embeddings · Ollama |
| **Web** | HTML · CSS · PWA · FastAPI · React · Netlify · Selenium |
| **Datos** | SQL · MySQL · MariaDB · MongoDB |
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

[LinkedIn](https://www.linkedin.com/in/franco-zimmermann-468116355) · [zmmr.fran@gmail.com](mailto:zmmr.fran@gmail.com) · Madrid, España

Si te interesa la IA local, el IoT o tienes una idea rara que quieras montar con un ESP32, escríbeme.
