---
{"dg-publish":true,"permalink":"/lithernia/07-bestias-monstruos/otros-monstruos/","title":"Otros Monstruos","tags":["lithernia","bestiario","monstruo"]}
---

# Otrosmonstruos

### Furia Lilium

| Atributo | Descripción |
| :--- | :--- |
| **Tipo de Criatura** | Elemental |
| **Alineamiento Típico** | Caótico Maligno |
| **Origen** | Cataclismo del [[Lithernia/09_Personajes/01_Dioses/Lilium\|Lilium]] |
| **Rol Táctico** | Hostigador, Daño de Área (Fuego, Necrótico) |
| **Nivel de Desafío** | 5 |
| **Entorno Común** | Ruinas pre-[[Lithernia/09_Personajes/01_Dioses/Lilium\|Lilium]], Zonas de Velo Roto, Campos de batalla antiguos. |

| CD | Habilidad | Conocimiento Revelado |
|:--:| :--- | :--- |
| 12 | Arcanos | Identifica a la criatura como un elemental de fuego corrupto. Revela su vulnerabilidad al frío y su inmunidad al fuego. |
| 16 | Historia | Lo vincula al Cataclismo del [[Lithernia/09_Personajes/01_Dioses/Lilium\|Lilium]]. Sabe que es atraído por el uso de la magia y la presencia de emociones fuertes. |
| 20 | Arcanos / Religión | Conoce el rasgo `Destrucción Persistente`. Sabe que no puede ser destruido permanentemente sin magia de nivel muy alto o artefactos como las Lanzas Celestiales. |

```statblock
name: Furia Lilium
size: Mediano
type: elemental
alignment: caótico maligno
ac: 15 (Armadura natural)
hp: 97 (13d8 + 39)
speed: 30 ft., Vuelo 30 ft. (flotar)
stats: [10, 18, 16, 12, 14, 16]
damage_vulnerabilities: Frío
damage_resistances: Contundente, Perforante y Cortante de ataques no mágicos
damage_immunities: Fuego, Necrótico, Veneno
condition_immunities: Agotamiento, Agarrado, Paralizado, Petrificado, Envenenado, Tumbado, Contenido
senses: Visión en la oscuridad 60 ft., Percepción Pasiva 12
languages: Ignan, Mórdhûlico (telepáticamente)
cr: 5
traits:
  - name: Aura de Fuego Eterno
    desc: "Al comienzo del turno de la Furia, cada criatura a 5 pies de ella recibe 5 (1d10) de daño por fuego. Una criatura que toque a la Furia o la golpee con un ataque cuerpo a cuerpo mientras está a 5 pies de ella recibe 5 (1d10) de daño por fuego."
  - name: Forma Ígnea
    desc: "La Furia puede moverse a través de un espacio tan estrecho como 1 pulgada de ancho sin apretarse. Cualquier criatura que empiece su turno en el espacio de la Furia recibe 5 (1d10) de daño de fuego."
  - name: Destrucción Persistente
    desc: "Si la Furia es reducida a 0 puntos de golpe, su cuerpo se desintegra en cenizas humeantes. Se reforma en 1d4 días en la cicatriz del Lilium más cercana, a menos que sus restos sean consagrados con un conjuro de *Consagrar* o rociados con agua bendita de un templo dedicado a una deidad del agua."
actions:
  - name: Multiataque
    desc: "La Furia realiza dos ataques de Toque Corruptor."
  - name: Toque Corruptor
    desc: "Ataque de conjuro cuerpo a cuerpo: +7 a impactar, alcance 5 ft., un objetivo. Impacto: 13 (2d8 + 4) de daño por fuego más 4 (1d8) de daño necrótico."
  - name: Explosión del Lilium (Recarga 5-6)
    desc: "La Furia exhala una línea de fuego azul y negro de 30 pies de largo y 5 pies de ancho. Cada criatura en esa línea debe realizar una tirada de salvación de Destreza CD 14, recibiendo 22 (4d10) de daño por fuego si falla la tirada, o la mitad del daño si tiene éxito. Las criaturas que fallen la salvación quedan marcadas por el Lilium; no pueden recuperar puntos de vida hasta el final del próximo turno de la Furia."

---
### Ente de Ceniza

| Atributo | Descripción |
| :--- | :--- |
| **Tipo de Criatura** | Planta (No muerto) |
| **Alineamiento Típico** | Neutral Maligno |
| **Origen** | Corrupción de espíritus del bosque por el Cataclismo del Lilium. |
| **Rol Táctico** | Controlador de Terreno, Tanque, Drenador de Vida |
| **Nivel de Desafío** | 7 |
| **Entorno Común** | Bosque de las Lágrimas, bosques corruptos en las fronteras de Mor'dhul. |

```statblock
name: Ente de Ceniza
size: Grande
type: planta (no muerto)
alignment: neutral maligno
ac: 16 (Armadura natural)
hp: 138 (12d10 + 72)
speed: 20 ft.
stats: [20, 8, 22, 10, 14, 9]
damage_vulnerabilities: Radiante
damage_resistances: Contundente, Perforante
damage_immunities: Necrótico, Veneno
condition_immunities: Asustado, Envenenado, Cegado, Ensordecido
senses: Visión ciega 60 ft., Percepción Pasiva 12
languages: Silvano (distorsionado)
cr: 7
traits:
  - name: Apariencia Falsa
    desc: "Mientras el ente permanece inmóvil, es indistinguible de un árbol muerto y cubierto de cenizas."
  - name: Terreno Corrupto
    desc: "El suelo en un radio de 30 pies alrededor del ente es terreno difícil para cualquier criatura que no sea un no-muerto o una planta. Cualquier criatura que comience su turno en esta área recibe 3 (1d6) de daño necrótico."
  - name: Absorber Vitalidad
    desc: "Cuando el ente inflige daño con su ataque de Golpetazo, recupera una cantidad de puntos de golpe igual a la mitad del daño necrótico infligido."
actions:
  - name: Multiataque
    desc: "El ente realiza dos ataques de Golpetazo."
  - name: Golpetazo
    desc: "Ataque de arma cuerpo a cuerpo: +8 a impactar, alcance 10 ft., un objetivo. Impacto: 14 (2d8 + 5) de daño contundente más 9 (2d8) de daño necrótico. Si el objetivo es una criatura, debe superar una tirada de salvación de Constitución CD 16 o su velocidad se reduce a la mitad hasta el final de su próximo turno."
  - name: Lluvia de Cenizas (Recarga 6)
    desc: "El ente exhala una nube de cenizas sofocantes en un radio de 20 pies. Cada criatura en esa área debe realizar una tirada de salvación de Constitución CD 16. Si falla, queda cegada y no puede respirar durante 1 minuto. Una criatura puede repetir la tirada de salvación al final de cada uno de sus turnos, terminando el efecto si tiene éxito."

---
### Tabla Resumen de Otros Monstruos

| Monstruo | Tipo | ND | Habilidades Mecánicas Clave |
| :--- | :--- | :---: | :--- |
| **Sombras Lúgubres** | No muerto | 2 | `Movimiento Incorpóreo`, `Drenaje de Fuerza`, `Ocultarse en las Sombras` (Acción adicional). Vulnerabilidad a la luz solar. |
| **Nereida Ensombrecida**| Feérico | 4 | `Anfibio`, `Canto Aturdidor` (CD Sabiduría), `Abrazo Ahogador` (Agarra y ahoga). `Invisibilidad en Agua Turbia`. |
| **Garras Espectrales** | Monstruosidad | 3 | `Paso Espectral` (Acción adicional para volverse incorpóreo hasta el final del turno), `Ataque Furtivo` (2d6), `Garras Etéreas` (ignora armadura no mágica). |
| **Rojos de Ceniza** | Enjambre de Bestias | 1 | `Enjambre`, `Mordiscos de Ceniza` (daño perforante y de fuego), `Resistencia a condiciones` (agarrado, tumbado, etc.). |
| **Espectros del Vacío** | Aberración | 6 | `Movimiento Incorpóreo`, `Toque Drenador` (psíquico), `Mirada Confusa` (CD Sabiduría o conjuro *Confusión*). `Resistencia Mágica`. |
| **Ombroles** | Aberración | 5 | `Alimentarse de Maná` (drena espacios de conjuro/Puntos de Maná con un toque), `Forma de Sombra`. Inmune a Conjuros de nivel 2 o inferior. |
| **Caídos del Lilium** | No muerto | 3 | `Armas Ardientes` (+1d6 daño de fuego), `Furia Imparable` (no puede ser asustado), `Resistencia Implacable` (como los Semiorcos). |
| **Surgidos del Requiem** | No muerto | 4 | `Toque del Olvido` (el objetivo debe superar una salvación de Sabiduría o perder la memoria de la última hora), `Aura de Odio` (ventaja en ataques contra celestiales y feéricos). |
| **Tótem Viviente** | Constructo | 10 | `Inmunidad a Magia` (inmune a Conjuros de nivel 3 o inferior), `Golpe Sísmico` (derriba en área), `Absorción de Elementos` (recupera PV al recibir cierto tipo de daño elemental). |
| **Bestia del Velo** | Monstruosidad | Varía | Aplica la plantilla El velo gris#Plantilla de Criatura Tocado por el Velo. Gana resistencia psíquica, vulnerabilidad a fuerza, y `Paso Velado` (teletransporte). |