# 🏷️ Guía Maestra de Etiquetas y Gráfico

Esta nota sirve como diccionario oficial de la campaña "Más Allá de Agujahelada". Copia estas etiquetas exactas en el `frontmatter` (Propiedades) de tus notas para mantener la bóveda perfectamente enlazada.

---

## 1. 🗂️ Sistema de Etiquetas (Tags)

### 🎭 Personajes y Entidades
* `#pj` : Para los personajes de los jugadores.
* `#npc` : Para cualquier personaje no jugador.
* `#monstruo` : Para bloques de estadísticas y enemigos genéricos o jefes (ej. Cryovain).
* `#deidad` : Para dioses o entidades superiores (Talos, Myrkul, Tymora).

### 🌍 Ubicaciones (Sistema Anidado de 3 Niveles)
* `#ubicacion/asentamiento/phandalin` : Para todo lo que esté en el pueblo.
* `#ubicacion/asentamiento/neverwinter` : Para la gran ciudad de Lord Neverember.
* `#ubicacion/asentamiento/leilon` : Para la ciudad en reconstrucción (niveles 7-13).
* `#ubicacion/mazmorra/nombre_mazmorra` : Ej. `/cueva_del_oleaje` o `/bastion_tresendar`.
* `#ubicacion/region/nombre_region` : Ej. `/pantano_hombres_muertos` o `/montañas_espada`.

### 🛡️ Facciones y Afiliaciones
* `#faccion/buscarrocas` : El Consorcio Minero Buscarrocas (El clan principal).
* `#faccion/zandro` : Operación Zandro Buscarrocas (Zorzula's Rest y sus mineros).
* `#faccion/dariksson` : El Clan Enano Dariksson (Karlon, Barlo, mecenas de Ágata).
* `#faccion/talos` : El Culto del Señor de las Tormentas (Anacoretas, Fheralai).
* `#faccion/myrkul` : El Culto de la Muerte (Ularan Mortus, nigromantes, asesino de Vértigo).
* `#faccion/culto_dragon` : Adoradores de dragones (Muerte de Ébano, Claugiyliamatar).
* `#faccion/zhentarim` : La Red Negra (Halia Thornton, mafias, mercado negro).
* `#faccion/alianza` o `#faccion/invernio` : Tropas oficiales y políticos (Sildar, Alana, el Noble de Invernio).
* `#faccion/mintarn` : Mercenarios de Mintarn (Eira, Ulric, Elric).
* `#faccion/circo` : El Circo de Sasha Callister.
* `#faccion/saqueadores` : Los Saqueadores de Piedra Fría.
* `#faccion/ninguna` : Civiles independientes (granjeros, artesanos, etc.).

### 📜 Trama y Misiones
* `#mision/activa` : Misiones en el tablón o en curso.
* `#mision/completada` : Para archivarlas sin borrarlas.
* `#lore` : Historia antigua, secretos, el Pacto de Phandelver o textos antiguos.
* `#campaña/doip` : Exclusivo para *El Dragón del Pico Agujahelada*.
* `#campaña/leilon` : Para los 3 módulos secuela (Ira, Despertar y Contención).

### 💎 Botín y Mecánicas
* `#item/magico` : Armas y artefactos importantes.
* `#item/mundano` : Objetos clave de misión (cartas, llaves, diarios).
* `#reglas` : Notas sobre mecánicas 2014 vs 2024, estados o reglas caseras.

### 📝 Gestión de Partida (Meta-DM)
* `#sesion` : Para los resúmenes de partida (ej. Sesión 01). Conecta toda la historia.
* `#dm_todo` : **¡Pendiente de preparar!** Cosas que tienes que rellenar, balancear o pensar antes de la siguiente partida.
* `#rumor` : Ganchos rápidos listos para soltar en tabernas.

### ⚔️ Encuentros y Peligros
* `#encuentro` : Eventos de viaje o escaramuzas aisladas ("Emboscada en el Camino").
* `#trampa` o `#puzzle` : Mecánicas de desafío no centradas en combate directo.

---

## 2. 🕸️ Configuración de la Vista Gráfica (Grupos y Colores)

> **⚠️ IMPORTANTE:** Obsidian procesa los grupos de **arriba hacia abajo**. El orden es crucial. Por ejemplo, un *#dm_todo* debe brillar en rosa fucsia por encima de cualquier otra cosa para que lo veas al abrir el programa. 

Crea los grupos con las siguientes Búsquedas y asígnales estos colores (puedes copiar el código Hexadecimal en el selector de color de Obsidian). Mantén **este orden exacto**:

| **Orden** | **Búsqueda (Copia esto exacto)**  | **Función**               | **Color / Tono**  | **Código HEX** |
| --------- | --------------------------------- | ------------------------- | ----------------- | -------------- |
| **1**     | `tag:#dm_todo`                    | **¡Atención DM!**         | 🌺 Rosa Neón      | `#FF00FF`      |
| **2**     | `path:"02_Los Jugadores"`         | **Los Héroes**            | 🔴 Rojo Intenso   | `#FF3333`      |
| **3**     | `tag:#sesion`                     | **Línea Temporal**        | ⚪ Blanco/Gris    | `#F2F2F2`      |
| **4**     | `tag:#faccion/buscarrocas`        | **Consorcio Buscarrocas** | 🟠 Naranja Oro    | `#FFAA00`      |
| **5**     | `tag:#faccion/zandro`             | **Operación Zandro**      | 🌋 Cobre Oxidado  | `#CC5500`      |
| **6**     | `tag:#faccion/dariksson`          | **Clan Dariksson**        | 🟤 Marrón Tierra  | `#8B4513`      |
| **7**     | `tag:#faccion/circo`              | **El Circo de Sasha**     | 🎪 Morado Ciruela | `#800080`      |
| **8**     | `tag:#faccion/mintarn`            | **Pasado de Arthur**      | 🛡️ Gris Acero     | `#708090`      |
| **9**     | `tag:#faccion/saqueadores`        | **Pasado de Garilius**    | ❄️ Azul Hielo     | `#ADD8E6`      |
| **10**    | `tag:#faccion/talos`              | **Villanos (DoIP)**       | ⚡ Amarillo Rayo  | `#FFEA00`      |
| **11**    | `tag:#faccion/myrkul`             | **Villanos (Leilon)**     | 💀 Hueso Pálido   | `#D3D3CA`      |
| **12**    | `tag:#faccion/culto_dragon`       | **Peligro Dracónico**     | 🌲 Verde Oscuro   | `#1A4314`      |
| **13**    | `tag:#faccion/zhentarim`          | **Red Negra**             | ⚫ Negro/Carbón   | `#333333`      |
| **14**    | `tag:#faccion/alianza`            | **Ley de Invernio**       | 🔵 Azul Real      | `#0033CC`      |
| **15**    | `tag:#encuentro` OR `tag:#trampa` | **Peligro Rápido**        | 🩸 Carmesí        | `#990000`      |
| **16**    | `tag:#monstruo`                   | **Enemigos Ficha**        | 🟣 Morado Jefe    | `#9933FF`      |
| **17**    | `tag:#mision`                     | **Tramas**                | 🧊 Azul Cian      | `#00E5FF`      |
| **18**    | `tag:#item`                       | **Tesoros**               | 🟡 Oro Brillante  | `#FFD700`      |
| **19**    | `tag:#ubicacion`                  | **Mundo Físico**          | 🟢 Verde Bosque   | `#33CC33`      |
| **20**    | `tag:#npc`                        | **Población**             | 🟦 Azul Estándar  | `#3388FF`      |
| **21**    | `tag:#lore` OR `tag:#rumor`       | **Información**           | 🟤 Pergamino      | `#CD853F`      |
| **22**    | `tag:#reglas`                     | **Mecánicas**             | 🧠 Rosa Oscuro    | `#C2185B`      |
### 🛠️ Filtros Esenciales del Gráfico
Para que tu red parezca un panel de detective y no un basurero digital, ve a la pestaña "Filtros" de la vista gráfica y asegúrate de configurar esto:
* **Buscar:** `-path:"00_Meta y Plantillas"` *(Oculta tus plantillas vacías para que no generen conexiones falsas).*
* **Archivos adjuntos:** ❌ Desmarcado *(Evita que las imágenes .png del mapa y tokens saturen la red).*
* **Etiquetas:** ❌ Desmarcado *(Recomendado: Oculta el nodo de la etiqueta en sí, de forma que solo veas las notas conectadas entre ellas, no todas enganchadas a un nodo gigante llamado "#npc").*