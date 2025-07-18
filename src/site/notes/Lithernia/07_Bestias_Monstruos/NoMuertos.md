---
{"dg-publish":true,"permalink":"/lithernia/07-bestias-monstruos/no-muertos/","title":"Nomuertos","tags":["lithernia","bestiario","nomuerto"]}
---

# Nomuertos

### Perfil de Categoría

| Atributo | Descripción |
| :--- | :--- |
| **Tipo de Criatura** | No muerto |
| **Alineamiento Típico** | Cualquiera Maligno |
| **Fuente de Origen** | Necromancia, Maldiciones, Ecos del Cataclismo del [[Lithernia/09_Personajes/01_Dioses/Lilium\|Lilium]] |
| **Entorno Común** | [[Lithernia/02_Reinos/Mor'dhul\|Mor'dhul]], Ruinas pre-[[Lithernia/09_Personajes/01_Dioses/Lilium\|Lilium]], Campos de batalla, Zonas de Velo Roto |
| **Vulnerabilidades Comunes** | Radiante, Fuego (contextual) |
| **Resistencias Comunes** | Necrótico, Veneno |
| **Inmunidades Comunes** | Envenenado, Agotamiento |
| **Sentidos Típicos** | Visión en la Oscuridad |
| **Tácticas Generales** | Abrumar en número, Drenaje de vida, Infundir miedo, Explotar la oscuridad. |

### Tabla de Conocimiento (Prueba de Habilidad)

| CD | Habilidad | Conocimiento Revelado |
| :--- | :--- | :--- |
| **10** | Religión | Identifica a la criatura como un no-muerto. Conoce su vulnerabilidad general al daño radiante y a los efectos de Expulsar No Muertos. |
| **15** | Arcanos | Reconoce el origen de la criatura: si es un constructo nigromántico (como un zombi del Clan Whisper) o un espíritu torturado (un fantasma de una batalla del [[Lithernia/09_Personajes/01_Dioses/Lilium\|Lilium]]). |
| **18** | Historia | Recuerda que enclaves en [[Lithernia/02_Reinos/Mor'dhul\|Mor'dhul]], como Chéga, los utilizan como mano de obra y ejército. Conoce la existencia de los "Eternos", la guardia no-muerta de la Ciudadela de obsidiana. |
| **20** | Religión / Arcanos | Sabe de la existencia de nomuertos únicos del [[Lithernia/09_Personajes/01_Dioses/Lilium\|Lilium]], como los Agores del Fulgor, y entiende que la profanación de ciertos lugares sagrados puede generarlos espontáneamente. |

### Tipología y Rol Táctico

| Tipo de No Muerto | Rol Táctico Primario | Amenaza Mecánica Clave |
| :--- | :--- | :--- |
| **Zombis / Esqueletos** | Tropa de Choque, Carne de Cañón | Superioridad numérica, Agarre, ataques en masa. |
| **Ghouls / Carroñeros** | Hostigador, Flanqueador | Mordisco paralizante, Enfermedades, alta movilidad. |
| **Fantasmas / Espectros** | Controlador, Asesino de Magos | Incorporeidad, Posesión, Drenaje de vida y características. |
| **Sombras** | Acechador, Debilitador | Sigilo en la oscuridad, Drenaje de Fuerza. |
| **Liche / [[Lithernia/04_Clases/Nigromante\|Nigromante]]** | Líder, Lanzador de [[Lithernia/06_Magia/Conjuros\|Conjuros]] | [[Lithernia/06_Magia/Conjuros\|Conjuros]] de área (Nigromancia), Control de esbirros, Contrahechizo. |
| **Vampiros** | Élite, Duelista | Agarre, Encanto, Drenaje de sangre, Regeneración. |
| **Coleccionistas de lamentos** | Controlador Psicológico | Supresión de curación, Daño psíquico, Miedo. |

### Reglas de Entorno: Tierras de las Sombras

En áreas de alta corrupción necrótica (cementerios profanados, campos de batalla malditos), se aplican las siguientes reglas:

| Regla | Efecto Mecánico |
| :--- | :--- |
| **Penumbra Constante** | El área está perpetuamente en luz tenue. La luz solar directa se considera luz tenue. |
| **Corrupción Necrótica** | Todos los [[Lithernia/06_Magia/Conjuros\|Conjuros]] y efectos que restauran puntos de golpe recuperan la mitad de la cantidad normal. Las criaturas que no sean no-muertos no pueden gastar Dados de Golpe durante un descanso corto. |
| **Llamada de la Tumba** | Al finalizar un descanso largo, una criatura viva debe superar una tirada de salvación de Sabiduría (CD 10) o ganar un nivel de agotamiento. |
| **Refuerzos Inesperados** | Cuando un no-muerto es destruido, hay un 25% de probabilidad de que 1d4 **Zombis** o **Esqueletos** emerjan de la tierra en un radio de 15 pies al comienzo de la siguiente ronda. |

### PNJ/Monstruo de Ejemplo

```statblock
name: Agor del Fulgor
size: Mediano
type: no muerto
alignment: caótico neutral
ac: 15
hp: 97 (13d8 + 39)
speed: 0 ft., Vuelo 50 ft. (flotar)
stats: [7, 18, 16, 14, 12, 18]
saves:
  - Dex: +7
  - Car: +7
skills:
  - Percepción: +4
  - Sigilo: +7
damage_vulnerabilities: Frío
damage_resistances: Ácido, Rayo, Trueno; Contundente, Perforante y Cortante de ataques no mágicos
damage_immunities: Fuego, Necrótico, Veneno
condition_immunities: Hechizado, Agotamiento, Asustado, Agarrado, Paralizado, Petrificado, Envenenado, Tumbado, Contenido
senses: Visión en la oscuridad 120 ft., Percepción Pasiva 14
languages: Ignan, entiende Común pero no puede hablar
cr: 8
traits:
  - name: Movimiento Incorpóreo
    desc: "El agor puede moverse a través de otras criaturas y objetos como si fueran terreno difícil. Recibe 5 (1d10) de daño de fuerza si termina su turno dentro de un objeto."
  - name: Iluminación Espectral
    desc: "El agor emite luz brillante en un radio de 20 pies y luz tenue 20 pies más allá. Esta luz es mágica y de color anaranjado, como las llamas del Lilium."
  - name: Muerte Ardiente
    desc: "Cuando el agor es reducido a 0 puntos de golpe, explota en una llamarada. Cada criatura en un radio de 10 pies debe realizar una tirada de salvación de Destreza CD 15, recibiendo 14 (4d6) de daño por fuego y 14 (4d6) de daño necrótico si falla la tirada, o la mitad del daño si tiene éxito."
actions:
  - name: Toque Abrasador
    desc: "Ataque de conjuro cuerpo a cuerpo: +7 a impactar, alcance 5 ft., una criatura. Impacto: 22 (4d8 + 4) de daño por fuego. Si el objetivo es una criatura o un objeto inflamable, se prende fuego. Hasta que una criatura use su acción para apagar las llamas, el objetivo recibe 5 (1d10) de daño por fuego al comienzo de cada uno de sus turnos."
  - name: Mirada del Lilium (Recarga 5-6)
    desc: "El agor se enfoca en una criatura que pueda ver a 60 pies. El objetivo debe superar una tirada de salvación de Sabiduría CD 15 o quedará paralizado durante 1 minuto. Mientras está paralizado de esta manera, el objetivo es atormentado por visiones del Cataclismo del Lilium. El objetivo puede repetir la tirada de salvación al final de cada uno de sus turnos, terminando el efecto si tiene éxito."
