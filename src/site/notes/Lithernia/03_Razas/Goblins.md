---
{"dg-publish":true,"permalink":"/lithernia/03-razas/goblins/","title":"Goblins","tags":["lithernia","raza"]}
---

# Goblins

### Perfil de la Raza

| Atributo | Descripción |
| :--- | :--- |
| **Reino de Origen** | [[Lithernia/02_Reinos/Mor'dhul\|Mor'dhul]] |
| **Panteón Principal** | Panteón Korogrim |
| **Deidad Creadora** | Gyth'kai, diosa del sacrificio |
| **Clanes Comunes** | Clan Gyth'kai, Clan Razortooth, Clan Shadowscale |
| **Rol Social Típico** | Oportunista, ladrón, asesino, espía. Sugiere trasfondos como [[Lithernia/05_Trasfondos/Criminal\|Criminal]], Charlatán o Paria. |
| **Alineamiento Típico**| Neutral Maligno |

### Rasgos Raciales (Personaje Jugador)

| Rasgo | Descripción |
| :--- | :--- |
| **Incremento de Característica** | Tu puntuación de Destreza aumenta en 2 y tu puntuación de Inteligencia aumenta en 1. |
| **Edad** | Alcanzan la edad adulta a los 8 años y viven hasta los 60. |
| **Tamaño** | Miden entre 3 y 4 pies de altura. Tu tamaño es Pequeño. |
| **Velocidad** | Tu velocidad base al caminar es de 30 pies. |
| **Visión en la Oscuridad** | Puedes ver en luz tenue a menos de 60 pies como si fuera luz brillante, y en la oscuridad como si fuera luz tenue. Solo percibes tonos de gris en la oscuridad. |
| **Escape Audaz** | Puedes realizar la acción de Destrabarse o Esconderse como una acción adicional en cada uno de tus turnos. |
| **Astucia de [[Lithernia/02_Reinos/Mor'dhul\|Mor'dhul]]** | Ganas competencia en las habilidades de Sigilo y Engaño. |
| **Sacrificio Oportunista** | Tu devoción a Gyth'kai te recompensa en el caos de la batalla. Cuando una criatura hostil que puedes ver a 10 pies de ti es reducida a 0 puntos de golpe, puedes usar tu reacción para ganar puntos de golpe temporales iguales a tu nivel de personaje. No puedes volver a usar este rasgo hasta que termines un descanso corto o largo. |
| **Afinidad con Venenos** | Ganas competencia con el kit de envenenador. Además, tienes resistencia al daño por veneno. |
| **Idiomas** | Puedes hablar, leer y escribir en Común y en Goblin. |

### Sinergias de Clase

| Clase | Sinergia y Rol Sugerido |
| :--- | :--- |
| **Pícaro** | **Óptima.** El +2 a DES, `Escape Audaz` y las competencias en Sigilo y Engaño son perfectos para cualquier arquetipo de pícaro, especialmente el Asesino o el Ladrón. |
| **Artífice** | **Fuerte.** El +1 a INT es el atributo principal. El rol de *Armero* o *Alquimista* encaja temáticamente con la afinidad por venenos y la astucia goblin. |
| **[[Lithernia/04_Clases/Mago\|Mago]]** | **Buena.** El +1 a INT beneficia el lanzamiento de [[Lithernia/06_Magia/Conjuros\|Conjuros]]. `Escape Audaz` proporciona una movilidad defensiva crucial para un lanzador de [[Lithernia/06_Magia/Conjuros\|Conjuros]] con pocos puntos de golpe. |
| **[[Lithernia/04_Clases/Guardabosques\|Guardabosques]] (Ranger)**| **Buena.** El +2 a DES es ideal para un arquero o un luchador basado en la finura. Encaja con un rol de [[Lithernia/05_Trasfondos/Cazador\|Cazador]] de recompensas o explorador de las tierras oscuras de [[Lithernia/02_Reinos/Mor'dhul\|Mor'dhul]]. |
| **[[Lithernia/04_Clases/Guerrero\|Guerrero]]** | **Buena.** El +2 a DES es excelente para un [[Lithernia/04_Clases/Guerrero\|Guerrero]] basado en la finura o un arquero. El arquetipo *Maestro de Batalla* se beneficia de la astucia táctica. |

### Monstruos y PNJs

```statblock
name: Goblin
size: Pequeño
type: humanoide (goblin)
alignment: neutral malvado
ac: 15 (armadura de cuero, escudo)
hp: 7 (2d6)
speed: 30 ft.
stats: [8, 14, 10, 10, 8, 8]
skills:
  - Sigilo: 6
senses: Visión en la oscuridad 60 ft., Percepción pasiva 9
languages: Común, Goblin
cr: 1/4
traits:
  - name: Escape Audaz
    desc: "El goblin puede realizar la acción de Destrabarse o Esconderse como una acción adicional en cada uno de sus turnos."
actions:
  - name: Cimitarra
    desc: "Ataque de arma cuerpo a cuerpo: +4 a impactar, alcance 5 ft., un objetivo. Impacto: 5 (1d6 + 2) de daño cortante."
  - name: Arco Corto
    desc: "Ataque de arma a distancia: +4 a impactar, alcance 80/320 ft., un objetivo. Impacto: 5 (1d6 + 2) de daño perforante."

```statblock
name: Chamán Goblin de Gyth'kai
size: Pequeño
type: humanoide (goblin)
alignment: neutral malvado
ac: 14 (armadura de pieles)
hp: 27 (6d6 + 6)
speed: 30 ft.
stats: [8, 14, 12, 12, 13, 11]
skills:
  - Engaño: 2
  - Religión: 3
  - Sigilo: 6
senses: Visión en la oscuridad 60 ft., Percepción pasiva 11
languages: Común, Goblin
cr: 1
traits:
  - name: Escape Audaz
    desc: "El chamán puede realizar la acción de Destrabarse o Esconderse como una acción adicional en cada uno de sus turnos."
  - name: Lanzamiento de Conjuros
    desc: "El chamán es un lanzador de Conjuros de nivel 3. Su característica para lanzar Conjuros es la Sabiduría (salvación de Conjuros CD 11, +3 a impactar con ataques de conjuro). El chamán tiene los siguientes Conjuros de clérigo preparados:\n\nTrucos (a voluntad): *Guía, Taumaturgia, Toque Gélido*\nNivel 1 (4 espacios): *Perdición, Curar heridas, Palabra de sanación, Infligir heridas*\nNivel 2 (2 espacios): *Arma espiritual* (aparece como una daga de sacrificio ensangrentada), *Silencio*"
  - name: Favor de la Diosa del Sacrificio
    desc: "Como acción adicional, el chamán puede elegir a una criatura aliada que pueda ver a 30 pies de él. Esa criatura recibe 5 (1d10) puntos de golpe temporales. El chamán no puede volver a usar este rasgo hasta que termine un descanso corto o largo."
actions:
  - name: Daga de Sacrificio
    desc: "Ataque de arma cuerpo a cuerpo: +4 a impactar, alcance 5 ft., un objetivo. Impacto: 4 (1d4 + 2) de daño perforante, más 3 (1d6) de daño necrótico."
