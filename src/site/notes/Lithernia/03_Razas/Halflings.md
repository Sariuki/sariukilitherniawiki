---
{"dg-publish":true,"permalink":"/lithernia/03-razas/halflings/","title":"Halflings","tags":["lithernia","raza","Galvorn"]}
---

# Halflings

### Resumen de Rasgos

| Rasgo Clave | Valor |
| :--- | :--- |
| **Aumento de Característica** | +2 Destreza, +1 Carisma o +1 Constitución (subraza) |
| **Velocidad** | 25 pies |
| **Tamaño** | Pequeño |
| **Rasgos Principales** | Suerte, Valentía, Agilidad Halfling, Paciencia de [[Lithernia/09_Personajes/01_Dioses/Taladrios\|Taladrios]] |
| **Subrazas** | Halfling de Pies Ligeros, Halfling de Hogar Robusto |

### Contexto Mecánico

| Característica | Vinculación en Lithernia |
| :--- | :--- |
| **Reino de Origen** | [[Lithernia/02_Reinos/Galvorn\|Galvorn]] |
| **Panteón Principal** | Panteón Humano (Dioses de [[Lithernia/02_Reinos/Galvorn\|Galvorn]]) |
| **Deidad Asociada** | [[Lithernia/09_Personajes/01_Dioses/Taladrios\|Taladrios]], dios del tiempo y los ciclos |
| **Rol Social Típico** | Agricultor, mercader, explorador, posadero. Sugiere trasfondos como Artesano Gremial, Plebeyo o Forastero. |

### Rasgos Raciales

| Rasgo | Descripción Mecánica |
| :--- | :--- |
| **Incremento de Característica** | Tu puntuación de Destreza aumenta en 2. |
| **Edad** | Alcanzan la madurez a los 20 años y viven hasta la mitad de su segundo siglo. |
| **Alineamiento** | Mayoritariamente Legales Buenos. Valoran la comunidad, la amabilidad y las tradiciones. |
| **Tamaño** | Tu tamaño es Pequeño. |
| **Velocidad** | Tu velocidad base al caminar es de 25 pies. |
| **Suerte** | Cuando obtienes un 1 en una tirada de ataque, prueba de habilidad o tirada de salvación, puedes volver a tirar el dado y debes usar el nuevo resultado. |
| **Valentía** | Tienes ventaja en las tiradas de salvación para no ser asustado. |
| **Agilidad Halfling** | Puedes moverte a través del espacio de cualquier criatura que sea de un tamaño mayor que el tuyo. |
| **Paciencia de [[Lithernia/09_Personajes/01_Dioses/Taladrios\|Taladrios]]** | Una vez por descanso largo, cuando falles una prueba de habilidad, puedes elegir volver a tirar el dado. Debes usar el nuevo resultado. |
| **Idiomas** | Puedes hablar, leer y escribir Común y Halfling. |

### Subrazas

#### Halfling de Pies Ligeros

| Rasgo | Descripción Mecánica |
| :--- | :--- |
| **Incremento de Característica** | Tu puntuación de Carisma aumenta en 1. |
| **Naturalmente Sigiloso** | Puedes intentar esconderte incluso cuando solo estás oculto por una criatura que es al menos un tamaño más grande que tú. |

#### Halfling de Hogar Robusto

| Rasgo | Descripción Mecánica |
| :--- | :--- |
| **Incremento de Característica** | Tu puntuación de Constitución aumenta en 1. |
| **Resistencia de Robusto** | Tienes ventaja en las tiradas de salvación contra veneno y tienes resistencia al daño por veneno. |

### Sinergias de Clase

| Clase | Sinergia y Rol Sugerido |
| :--- | :--- |
| **Pícaro** | **Óptima.** El +2 a DES es perfecto. La subraza *Pies Ligeros* complementa el sigilo. *Suerte* y *Valentía* aumentan la supervivencia. |
| **[[Lithernia/04_Clases/Guardabosques\|Guardabosques]] (Ranger)** | **Fuerte.** El +2 a DES beneficia los estilos de arquería. *Paciencia de [[Lithernia/09_Personajes/01_Dioses/Taladrios\|Taladrios]]* es útil para pruebas de Supervivencia o Naturaleza. |
| **[[Lithernia/04_Clases/Monje\|Monje]]** | **Fuerte.** El +2 a DES es un atributo clave. La movilidad del Halfling y sus defensas raciales son excelentes para un rol de hostigador. |
| **[[Lithernia/04_Clases/Bardo\|Bardo]]** | **Buena.** Especialmente para un *Pies Ligeros* con su +1 a CAR. El rol de narrador de historias encaja temáticamente. |

### PNJ Típico

```statblock
name: Defensor de la Comarca Halfling
size: Pequeño
type: humanoide (halfling)
alignment: legal bueno
ac: 15 (Armadura de cuero tachonado)
hp: 22 (4d6 + 8)
speed: 25 ft.
stats: [12, 16, 14, 10, 11, 12]
skills:
  Percepción: 2
  Sigilo: 5
senses: Percepción Pasiva 12
languages: Común, Halfling
cr: 1/2
traits:
  - name: Suerte
    desc: "Cuando el defensor saca un 1 en una tirada de ataque, prueba de habilidad o tirada de salvación, puede volver a tirar el dado y debe usar la nueva tirada."
  - name: Valentía
    desc: "El defensor tiene ventaja en las tiradas de salvación para no ser asustado."
actions:
  - name: Espada Corta
    desc: "Ataque de arma cuerpo a cuerpo: +5 a impactar, alcance 5 ft., un objetivo. Impacto: 6 (1d6 + 3) de daño perforante."
  - name: Honda
    desc: "Ataque de arma a distancia: +5 a impactar, alcance 30/120 ft., un objetivo. Impacto: 5 (1d4 + 3) de daño contundente."
reactions:
  - name: Proteger al Vecino
    desc: "Cuando un atacante que el defensor puede ver impacta a un aliado a 5 pies de él, el defensor puede usar su reacción para imponer desventaja en la tirada de daño de ese ataque."
