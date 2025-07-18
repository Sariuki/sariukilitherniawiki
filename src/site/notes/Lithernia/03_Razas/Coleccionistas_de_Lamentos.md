---
{"dg-publish":true,"permalink":"/lithernia/03-razas/coleccionistas-de-lamentos/","title":"Coleccionistas de lamentos","tags":["lithernia","criatura","no-muerto"]}
---

# Coleccionistas de lamentos

### Tabla de Identificación

| Atributo | Descripción |
| :--- | :--- |
| **Tipo de Criatura** | No muerto (Espectral) |
| **Alineamiento Típico** | Neutral Maligno |
| **Deidad Patrona** | [[Lithernia/09_Personajes/01_Dioses/Kromagul\|Kromagul]], Dios del Dolor |
| **Facción Principal** | Clan [[Lithernia/09_Personajes/01_Dioses/Kromagul\|Kromagul]] |
| **Nivel de Desafío** | 6 |
| **Rol Táctico** | Cosechador de Sufrimiento, Controlador, Hostigador Mágico |
| **Entorno Común** | Ruinas, campos de batalla, zonas de tragedia ([[Lithernia/02_Reinos/Mor'dhul\|Mor'dhul]]) |

### Tabla de Conocimiento (Prueba de Habilidad)

| CD | Habilidad | Conocimiento Revelado |
| :--- | :--- | :--- |
| **10** | Religión | Identifica a la criatura como un no-muerto espectral, un espíritu torturado sirviente de una deidad del dolor. Revela su vulnerabilidad al daño radiante. |
| **15** | Arcanos o Religión | Conoce sus resistencias e inmunidades clave. Sabe que su toque drena la fuerza vital y que su `Aura de Pesar` suprime la curación cercana. |
| **20** | Historia o Arcanos | Recuerda [[Lithernia/09_Personajes/Leyendas\|Leyendas]] que los vinculan específicamente a [[Lithernia/09_Personajes/01_Dioses/Kromagul\|Kromagul]] y [[Lithernia/02_Reinos/Mor'dhul\|Mor'dhul]]. Sabe que son creados en lugares de sufrimiento extremo para "cosechar" agonía, y conoce el devastador efecto de su habilidad `Cosechar Lamento`. |

### Tácticas y Comportamiento

| Estrategia | Descripción |
| :--- | :--- |
| **Prioridad** | Aislar y atormentar objetivos vulnerables, especialmente sanadores y lanzadores de [[Lithernia/06_Magia/Conjuros\|Conjuros]] con baja puntuación de Sabiduría. |
| **Apertura de Combate** | Utilizar `Cosechar Lamento` para infligir miedo, dispersar al grupo y establecer control sobre el campo de batalla. |
| **Posicionamiento** | Mantenerse en vuelo, fuera del alcance de ataques cuerpo a cuerpo. Usar `Movimiento Incorpóreo` para atravesar obstáculos, muros y flanquear a los enemigos. |
| **Sinergias** | La habilidad `Aura de Pesar` anula la sanación, volviendo más efectivo el daño sostenido de aliados (como guerreros [[Lithernia/03_Razas/Hobgoblins\|Hobgoblins]] o brutos Semiogros). Se beneficia de la muerte de cualquier criatura cercana con `Devorador de Angustia`. |
| **Debilidades** | El daño radiante es su principal vulnerabilidad. Su `Aura de Pesar` requiere que se acerque a 10 pies de sus objetivos, exponiéndolo a ataques. |

### Ganchos de Encuentro

| d6 | Situación del Encuentro |
|:--:|---|
| **1** | Un par de Coleccionistas guarda una ruina de la era pre-[[Lithernia/09_Personajes/01_Dioses/Lilium\|Lilium]], protegiendo un artefacto que resuena con un inmenso dolor. |
| **2** | Atormentan una aldea afligida por una plaga, alimentándose del pesar colectivo y evitando que los clérigos puedan sanar a los enfermos. |
| **3** | Convocados por un ritual del Clan [[Lithernia/09_Personajes/01_Dioses/Kromagul\|Kromagul]] en la ciudad de Fuempillos para torturar a un prisionero importante hasta quebrantar su espíritu. |
| **4** | Sirven como escolta de élite a un [[Lithernia/04_Clases/Sacerdote\|Sacerdote]] de alto rango de [[Lithernia/09_Personajes/01_Dioses/Kromagul\|Kromagul]], manifestándose desde su sombra para atacar. |
| **5** | Emergen de los cuerpos de dos generales caídos en un campo de batalla reciente, como el Bosque de las Lágrimas. |
| **6** | Un Coleccionista acecha a un aventurero que porta un objeto ligado a una gran tragedia, atraído por el eco de sufrimiento del artefacto. |

### Tesoro y Recolección

| Componente | CD de Recolección | Usos Potenciales |
| :--- | :--- | :--- |
| **Esencia Espectral** | 15 (Inteligencia, Arcanos) | Un ingrediente alquímico para la creación de pociones de *Invisibilidad* o venenos que infligen daño psíquico. |
| **Lamento Cristalizado** | El DM determina (raro) | Un pequeño cristal oscuro que pulsa con dolor. Puede ser aplastado como una acción para forzar a una criatura a 30 pies a superar una salvación de Sabiduría CD 15 o quedar asustada por 1 minuto. |

```statblock
name: Coleccionista de Lamentos
size: Mediano
type: No muerto
alignment: Neutral Maligno
ac: 15
hp: 78 (12d8 + 24)
speed: 0 ft., Vuelo 40 ft. (flotar)
stats: [10, 16, 14, 12, 17, 18]
saves:
  - Sab: +6
  - Car: +7
skills:
  - Percepción: +6
  - Sigilo: +6
  - Intimidación: +7
damage_vulnerabilities: Radiante
damage_resistances: Ácido, Frío, Rayo, Trueno; Contundente, Perforante y Cortante de ataques no mágicos
damage_immunities: Necrótico, Veneno, Psíquico
condition_immunities: Hechizado, Agotamiento, Asustado, Agarrado, Paralizado, Petrificado, Envenenado, Tumbado, Contenido
senses: Visión en la oscuridad 120 ft., Percepción Pasiva 16
languages: Entiende los idiomas que conocía en vida pero no puede hablar, Telepatía 120 ft.
cr: 6
traits:
  - name: Aura de Pesar
    desc: "Al comienzo de su turno, cada criatura a elección del Coleccionista que se encuentre a 10 pies de él debe superar una tirada de salvación de Sabiduría CD 15 o no podrá recuperar puntos de golpe hasta el comienzo del próximo turno del Coleccionista. Una criatura que tenga éxito en la salvación es inmune a esta aura durante 24 horas."
  - name: Movimiento Incorpóreo
    desc: "El Coleccionista puede moverse a través de otras criaturas y objetos como si fueran terreno difícil. Recibe 5 (1d10) de daño de fuerza si termina su turno dentro de un objeto."
  - name: Devorador de Angustia
    desc: "Cuando una criatura a 30 pies o menos del Coleccionista es reducida a 0 puntos de golpe, el Coleccionista gana 10 (3d6) puntos de golpe temporales."
actions:
  - name: Toque Absorbente
    desc: "Ataque de conjuro cuerpo a cuerpo: +7 a impactar, alcance 5 ft., un objetivo. Impacto: 22 (4d8 + 4) de daño necrótico. El objetivo debe superar una tirada de salvación de Constitución CD 15 o su máximo de puntos de golpe se reducirá en una cantidad igual al daño recibido. Esta reducción dura hasta que la criatura finaliza un descanso prolongado."
  - name: Cosechar Lamento (Recarga 5-6)
    desc: "El Coleccionista se enfoca en una criatura que pueda ver a 60 pies de él. El objetivo debe realizar una tirada de salvación de Sabiduría CD 15. Si falla, recibe 27 (6d8) de daño psíquico y queda asustado durante 1 minuto. Si tiene éxito, recibe la mitad del daño y no queda asustado. Una criatura asustada puede repetir la tirada de salvación al final de cada uno de sus turnos, terminando el efecto sobre sí misma si tiene éxito."
