---
{"dg-publish":true,"permalink":"/lithernia/03-razas/ciudadela-de-obsidiana/","title":"Ciudadela de obsidiana","tags":["lithernia","ciudad","Mor'dhul"]}
---

# Ciudadela de obsidiana

### Perfil del Asentamiento

| Característica | Descripción |
| :--- | :--- |
| **Tipo de Asentamiento** | Capital de Reino, Fortaleza |
| **Reino** | [[Lithernia/02_Reinos/Mor'dhul\|Mor'dhul]] |
| **Gobernante** | Rey-Dios Sel'thirak (Legal Maligno) |
| **Población** | ~150,000 ([[Lithernia/03_Razas/Tieflings\|Tieflings]], [[Lithernia/03_Razas/Orcos\|Orcos]], [[Lithernia/03_Razas/Hobgoblins\|Hobgoblins]], [[Lithernia/03_Razas/Goblins\|Goblins]], Esclavos) |
| **Gobierno** | Teocracia Autoritaria |
| **Defensas** | Murallas de obsidiana (CA 22; 300 PV por sección de 10 pies), Legiones de [[Lithernia/03_Razas/Orcos\|Orcos]], Guardia de "Eternos", Magia de Abjuración y Adivinación |
| **Nivel de Peligro** | Mortal (CR 15+) |
| **Facciones Clave** | Clan Sel'thirak (Gobernante), Clan [[Lithernia/09_Personajes/01_Dioses/Thyrgram\|Thyrgram]] (Militar), Círculo de Aethel (Conspirador), Células Rebeldes (Ocultas) |
| **Comercio** | Mercado negro (componentes de magia oscura, venenos, información prohibida), comercio de esclavos y armamento. |

### Tabla de Conocimiento (Prueba de Habilidad)

| CD | Habilidad | Conocimiento Revelado |
| :--- | :--- | :--- |
| **10** | Historia / Saber Popular | La Ciudadela es la capital de [[Lithernia/02_Reinos/Mor'dhul\|Mor'dhul]], gobernada con puño de hierro por el Rey-Dios Sel'thirak. Es un lugar de opresión y peligro. |
| **15** | Investigación / Religión | Se conoce la existencia de la guardia de élite no-muerta ("Los Eternos"), la paranoia generalizada y la prohibición estricta de cualquier mención a la profecía del Primer Rey. |
| **18** | Perspicacia / Sigilo | Se revela la existencia de facciones conspiradoras como la de Lord Aethel, la ubicación general de mercados negros, y la presencia de espías en cada esquina. |
| **20** | Arcanos / Historia | Se sabe que la ciudad está construida sobre una cicatriz del Cataclismo del [[Lithernia/09_Personajes/01_Dioses/Lilium\|Lilium]], lo que provoca pesadillas y atrae a entidades extrañas. Se conocen rumores sobre las catacumbas bajo la ciudadela. |

### Reglas de Entorno

| Regla | Efecto Mecánico |
| :--- | :--- |
| **Aura de Paranoia** | Al interactuar con una figura de autoridad por primera vez en el día, el personaje debe superar una tirada de salvación de Sabiduría (CD 15) o sufrirá desventaja en todas las pruebas de Carisma (Engaño, Persuasión) que no estén alineadas con la voluntad del régimen durante 24 horas. |
| **Ecos del [[Lithernia/09_Personajes/01_Dioses/Lilium\|Lilium]]** | Al realizar un descanso largo dentro de la Ciudadela, tira un d20. Con un 1, el personaje es atormentado por pesadillas del fuego eterno, no obtiene los beneficios del descanso y gana un nivel de agotamiento. |
| **Ley de Sel'thirak** | Cualquier mención de la Profecía del Retorno del Primer Rey es alta traición y conlleva la ejecución pública. La magia no autorizada por el régimen atrae la atención inmediata de la guardia. |
| **Vigilancia Constante** | Las pruebas de Destreza (Sigilo) para moverse sin ser visto dentro de los muros de la ciudad se realizan con desventaja debido a las patrullas de los Eternos y los espías mágicos. |

### PNJs y Monstruos Notables

```statblock
name: Eterno (Guardia de la Ciudadela)
size: Mediano
type: No muerto
alignment: Legal Maligno
ac: 16 (Armadura de placas)
hp: 93 (11d8 + 44)
speed: 30 ft.
stats: [18, 11, 18, 10, 12, 9]
damage_immunities: Veneno, Necrótico
condition_immunities: Asustado, Hechizado, Agotamiento, Envenenado
senses: Visión en la oscuridad 60 ft., Percepción Pasiva 11
languages: Entiende Común y Mórdhûlico pero no puede hablar
cr: 5
traits:
  - name: Lealtad Inmortal
    desc: "El Eterno tiene ventaja en las tiradas de salvación contra efectos que intenten expulsar no muertos."
  - name: Resistencia Mágica
    desc: "El Eterno tiene ventaja en las tiradas de salvación contra conjuros y otros efectos mágicos."
actions:
  - name: Multiataque
    desc: "El Eterno realiza dos ataques con su Alabarda de Obsidiana."
  - name: Alabarda de Obsidiana
    desc: "Ataque de arma cuerpo a cuerpo: +7 a impactar, alcance 10 ft., un objetivo. Impacto: 9 (1d10 + 4) de daño cortante más 4 (1d8) de daño necrótico."
  - name: Mirada Desalmada (Recarga 6)
    desc: "El Eterno se enfoca en una criatura que pueda ver a 30 pies. El objetivo debe superar una tirada de salvación de Sabiduría CD 13 o quedará asustado durante 1 minuto. El objetivo puede repetir la tirada de salvación al final de cada uno de sus turnos, terminando el efecto si tiene éxito."

```statblock
name: Lady Xandria "La Susurrante"
size: Mediana
type: Humanoide (Tiefling)
alignment: Legal Maligno
ac: 15 (Túnicas de la Consejera)
hp: 110 (20d8 + 20)
speed: 30 ft.
stats: [10, 16, 12, 19, 14, 20]
saves:
  - Int: +8
  - Car: +9
skills:
  - Engaño: +13
  - Perspicacia: +10
  - Persuasión: +9
  - Sigilo: +7
damage_resistances: Fuego
senses: Visión en la oscuridad 60 ft., Percepción Pasiva 12
languages: Común, Infernal, Mórdhûlico, Élfico
cr: 13
traits:
  - name: Lanzamiento de Conjuros
    desc: "Xandria es una lanzadora de conjuros de nivel 18. Su aptitud mágica es el Carisma (CD de salvación de conjuros 17, +9 a impactar con ataques de conjuro). Conoce los siguientes conjuros de hechicero:\n\nTrucos (a voluntad): *Ilusión menor, Mano de mago, Mensaje, Prestidigitación, Rayo de escarcha*\nNivel 1 (4 espacios): *Disfrazarse, Hechizar persona, Escudo*\nNivel 2 (3 espacios): *Detectar pensamientos, Inmovilizar persona, Sugestión*\nNivel 3 (3 espacios): *Contraconjuro, Disipar magia, Miedo*\nNivel 4 (3 espacios): *Confusión, Puerta dimensional, Invisibilidad mayor*\nNivel 5 (3 espacios): *Dominar persona, Modificar recuerdo, Muro de fuerza*\nNivel 6 (1 espacio): *Sugestión en masa*\nNivel 7 (1 espacio): *Teleportar*\nNivel 8 (1 espacio): *Dominar monstruo*\nNivel 9 (1 espacio): *Palabra de poder: matar*"
  - name: Mente Inescrutable
    desc: "Xandria es inmune a cualquier efecto que intente sentir sus emociones o leer sus pensamientos, así como a cualquier tirada de salvación de Sabiduría (Perspicacia). La magia no puede determinar si está mintiendo."
actions:
  - name: Daga Psiónica
    desc: "Ataque de arma cuerpo a cuerpo: +7 a impactar, alcance 5 ft., un objetivo. Impacto: 5 (1d4 + 3) de daño perforante más 13 (3d8) de daño psíquico."
reactions:
  - name: Velo de Secretos
    desc: "Cuando es objetivo de un conjuro de encantamiento o adivinación, Xandria puede usar su reacción para forzar al lanzador a realizar una tirada de salvación de Sabiduría CD 17. Si falla, el conjuro no tiene efecto sobre Xandria y el lanzador sufre 11 (2d10) de daño psíquico."

```statblock
name: Lord Volrath "La Mano Negra"
size: Mediano
type: Humanoide (Orco)
alignment: Legal Maligno
ac: 20 (Armadura de placas de obsidiana, escudo)
hp: 187 (22d8 + 88)
speed: 30 ft.
stats: [20, 12, 18, 14, 15, 16]
saves:
  - Fue: +10
  - Con: +9
skills:
  - Atletismo: +10
  - Intimidación: +8
  - Percepción: +7
senses: Visión en la oscuridad 60 ft., Percepción Pasiva 17
languages: Común, Orco, Mórdhûlico
cr: 14
traits:
  - name: Amenaza Implacable
    desc: "Si Volrath es reducido a 0 puntos de golpe pero no muere directamente, puede elegir quedar con 1 punto de golpe en su lugar. No puede usar este rasgo de nuevo hasta que finalice un descanso largo."
  - name: Táctico de Batalla
    desc: "Volrath puede usar la acción de Ayudar como una acción adicional."
  - name: Ataques Salvajes
    desc: "Cuando Volrath obtiene un golpe crítico con un ataque con arma cuerpo a cuerpo, puede tirar uno de los dados de daño del arma una vez más y añadirlo al daño extra del golpe crítico."
actions:
  - name: Multiataque
    desc: "Volrath realiza tres ataques con su Hacha de Guerra de Obsidiana."
  - name: Hacha de Guerra de Obsidiana
    desc: "Ataque de arma cuerpo a cuerpo: +10 a impactar, alcance 5 ft., un objetivo. Impacto: 9 (1d8 + 5) de daño cortante, o 10 (1d10 + 5) si se usa a dos manos, más 7 (2d6) de daño por fuego."
  - name: Grito de Liderazgo (Recarga 5-6)
    desc: "Volrath emite un grito de guerra. Durante 1 minuto, todos los aliados a 30 pies de él que puedan oírle infligen 1d4 de daño adicional con sus ataques de arma y tienen ventaja en las tiradas de salvación contra ser asustados."

### Ganchos de Aventura

| Misión | Facción Involucrada | Objetivo de la Misión | Pruebas Clave Sugeridas (CD) | Complicación Potencial |
| :--- | :--- | :--- | :--- | :--- |
| **El Susurro Prohibido** | Rebeldes del Primer Rey | Extraer a un sabio prisionero que conoce la ubicación de una de las Lanzas Celestiales. | Sigilo (20), Engaño (18), Investigación (16) | El sabio está siendo interrogado personalmente por Lady Xandria. |
| **Sabotaje en la Armería** | Agentes de Eldrador | Destruir un lote de armas de obsidiana antes de que equipen al ejército de Volrath. | Hurto (17), Sigilo (19), Herramientas de Ladrón (18) | Lord Volrath supervisa la armería esa noche. |
| **La Traición de Aethel** | Lord Volrath (en secreto) | Conseguir pruebas de la conspiración de Lord Aethel para presentarlas al rey. | Persuasión (17), Investigación (20), Percepción (18) | Los agentes de Aethel tienden una emboscada; las pruebas están codificadas mágicamente. |
| **Robar el Corazón del Lilium** | Lord Aethel | Infiltrarse en las catacumbas bajo la ciudadela y robar un fragmento de Lilium cristalizado. | Supervivencia (16), Arcanos (19), Atletismo (17) | El fragmento está protegido por Ecos del Lilium y un guardián elemental de fuego. |