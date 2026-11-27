<h1 align="center">Hola, soy Matías Mesonero 👋</h1>
<h3 align="center">Desarrollador de videojuegos indie · Artista 3D en Blender</h3>

<p align="center">
  📍 Punta Alta, Buenos Aires, Argentina · Disponible presencial (Bahía Blanca y zona) o remoto
</p>

<p align="center">
  <a href="mailto:matiasfernandomesonero@gmail.com"><img src="https://img.shields.io/badge/Email-contacto-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

---

## 🧭 Sobre mí

Vengo del oficio: trabajo en la **Armada Argentina** en el taller de gas y plomería, antes en albañilería, con guardias rotativas. Ese recorrido me dio algo que se traslada directo al desarrollo: **disciplina, trabajo con normas y procedimientos, y terminar lo que empiezo**.

En paralelo, de forma autodidacta, desarrollo videojuegos y escenas 3D con una identidad muy clara: **estética argentina auténtica** — folklore, historia, barrio y realismo social.

Trabajo como **desarrollador solista**: diseño, programo, armo pipelines de arte y documento cada proyecto. Uso herramientas de IA como parte del flujo (asistencia en código, generación de arte y audio) y me encargo de dirigir, integrar, probar y pulir el resultado.

---

## 🛠️ Herramientas

<p>
  <img src="https://img.shields.io/badge/Godot_4-478CBF?style=flat-square&logo=godotengine&logoColor=white"/>
  <img src="https://img.shields.io/badge/GDScript-355570?style=flat-square&logo=godotengine&logoColor=white"/>
  <img src="https://img.shields.io/badge/Blender-E87D0D?style=flat-square&logo=blender&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pillow_(PIL)-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenStreetMap-7EBC6F?style=flat-square&logo=openstreetmap&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white"/>
  <img src="https://img.shields.io/badge/IA_generativa-6E40C9?style=flat-square"/>
</p>

| Área | Qué hago |
|---|---|
| **Programación de juegos** | Godot 4.x / GDScript, lógica de juego desacoplada de la interfaz, IA de oponentes, sistemas de diálogo y reputación |
| **Testing y validación** | Suites de tests automáticos, Godot *headless* + Xvfb para validar escenas y sacar capturas sin abrir el editor, herramientas propias de auditoría |
| **3D y arte técnico** | Blender (EEVEE, iluminación, volumétricas, simulación de tela), scripting en Python, renders de capas parallax para 2D |
| **Pipelines** | Reconstrucción de calles reales con OpenStreetMap + blosm, generación de assets *placeholder* con Pillow, flujos de arte con IA |
| **Diseño y documentación** | Biblias de diseño (GDD), cronologías, elencos, documentos técnicos de producción |

---

## 🎮 Proyectos destacados

> El código fuente de mis juegos comerciales es privado. Acá muestro capturas, videos y decisiones técnicas.

### 🃏 Mano Brava — Truco por las provincias argentinas *(en desarrollo activo)*
Juego de cartas en **Godot 4.6**: recorrés las provincias jugando al Truco contra rivales inspirados en leyendas de cada región (el Pombero, la Luz Mala, el Coquena…), y cada mesa tiene una mecánica propia ligada al rival.
- Motor de Truco **desacoplado** con reglas completas, motor de probabilidades y toma de decisiones de la IA, cubierto por **189 tests**
- Sistema de diálogo con dos modos de presentación y *banter* que alimenta un sistema de **reputación** en vivo
- **25 escenas** de provincia verificadas con una herramienta de auditoría propia (`auditar_mesas.gd`)
- Curva de dificultad por región, efectos de partículas (humo, vapor) y transiciones de mapa con zoom + viñeta

<!-- <img src="img/mano-brava.png" width="640"/> -->

### 🌲 Chronicles of the Forest — Action RPG 3D *(en desarrollo)*
RPG de exploración en **Godot 4** con misiones, diálogos y combate en tiempo real. Iterado en más de 25 versiones.
- Esquive, habilidad especial por héroe, niveles, botín y pociones
- Pueblo con NPCs, **ciclo día/noche**, arena de combate (pensada para PvP) y Templo del Eclipse
- Música, efectos de impacto (sacudida de cámara, destellos, partículas) y guardado de partida

### 🏙️ La Ciudad Que Te Olvidó — Metroidvania 2.5D *(preproducción)*
Metroidvania para **Steam** en Godot 4 + Blender. Biblia de diseño propia como canon, con cronología, elenco y documentos técnicos; arte guiado por una imagen ancla de estilo.

### 🌿 La Leyenda del Pombero — Plataformas 2D
Plataformero en Godot 4 basado en folklore argentino y paraguayo.
- 3 niveles con sistema de coleccionables (*Memorias*) y checkpoints
- Parallax procedural con 10 modos y contorno *cartoon* aplicado en tiempo de ejecución
- Separación de plataformas validada contra la física del personaje; validación completa del motor en modo *headless*

### 🔥 Luz Mala — Action RPG 2D *(prototipo)*
Un gaucho defendiendo su tierra de criaturas del folklore en cinco regiones. GDD completo, documento de pipeline de producción, menú y primera escena jugable con combate WASD + apuntado con mouse.

---

## 🎨 Blender

- **Calle argentina de noche** — Lada, adoquines y farolas con parpadeo realista, luna procedural, volumétricas EEVEE y secuencia cinemática de 1 minuto con tres cámaras
- **Patio_1955** — patio criollo con pérgola, piso de baldosas, pasto procedural, radio y ropa tendida con **simulación de tela**, luz de atardecer
- **Punta Alta en 3D** — red de calles real reconstruida desde OpenStreetMap con estilo *toon*, como referencia de mundo
- Personajes chibi armados por script en Python; rig *cut-out* de personajes 2D con armature

<!-- <img src="img/calle-noche.png" width="420"/> <img src="img/patio-1955.png" width="420"/> -->

---


<p align="center"><i>"Juegos con olor a barrio, mate y leyenda."</i></p>
