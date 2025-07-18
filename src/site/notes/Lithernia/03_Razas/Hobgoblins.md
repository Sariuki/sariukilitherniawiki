---
{"dg-publish":true,"permalink":"/lithernia/03-razas/hobgoblins/","title":"Hobgoblin","tags":["lithernia","raza"]}
---

# Hobgoblins

### Resumen de Rasgos

| Rasgo Clave | Valor |
| :--- | :--- |
| **Aumento de Característica** | +2 Constitución, +1 Inteligencia |
| **Velocidad** | 30 pies |
| **Visión** | Visión en la Oscuridad (60 pies) |
| **Competencias Clave** | Intimidación |
| **Rasgos Únicos** | Disciplina de [[Lithernia/09_Personajes/01_Dioses/Kromagul\|Kromagul]], Tácticas del Dolor, Legado del Sufrimiento |

### Contexto Mecánico

| Característica | Vinculación en Lithernia |
| :--- | :--- |
| **Reino de Origen** | [[Lithernia/02_Reinos/Mor'dhul\|Mor'dhul]] |
| **Panteón Principal** | Panteón Korogrim |
| **Deidad Patrona** | [[Lithernia/09_Personajes/01_Dioses/Kromagul\|Kromagul]], Dios del Dolor |
| **Rol Social Típico** | Estratega, soldado de élite, comandante, torturador. Sugiere trasfondos como Soldado, Gladiador o Inquisidor. |
| **Facción Asociada** | Clan [[Lithernia/09_Personajes/01_Dioses/Kromagul\|Kromagul]] |

### Rasgos Raciales

| Rasgo | Descripción |
| :--- | :--- |
| **Incremento de Puntuación de Característica** | Tu puntuación de Constitución aumenta en 2 y tu puntuación de Inteligencia aumenta en 1. |
| **Edad** | Maduran al mismo ritmo que los [[Lithernia/03_Razas/Humanos\|Humanos]] y tienen una esperanza de vida ligeramente más larga. |
| **Alineamiento** | Moldeados por su dios [[Lithernia/09_Personajes/01_Dioses/Kromagul\|Kromagul]] y su sociedad militarista, tienden hacia Legal Maligno. |
| **Tamaño** | Mediano. Miden entre 1,5 y 1,8 metros de altura (5 a 6 pies). |
| **Velocidad** | Tu velocidad base al caminar es de 30 pies. |
| **Visión en la Oscuridad** | Puedes ver en luz tenue hasta 60 pies como si fuera luz brillante, y en la oscuridad como si fuera luz tenue. No puedes discernir colores en la oscuridad, sólo tonos de gris. |
| **Disciplina de [[Lithernia/09_Personajes/01_Dioses/Kromagul\|Kromagul]]** | Si fallas una tirada de ataque, una prueba de habilidad o una tirada de salvación, puedes elegir obtener un bonificador a la tirada igual al número de aliados que puedas ver en un radio de 30 pies (máximo de +3). Puedes usar este rasgo un número de veces igual a tu bonificador de competencia y recuperas todos los usos tras un descanso largo. |
| **Tácticas del Dolor** | Puedes usar la acción de Ayudar como una acción adicional. Cuando usas la acción de Ayudar para asistir a un aliado a atacar a una criatura, el aliado atacante también gana puntos de golpe temporales iguales a tu bonificador de competencia. |
| **Legado del Sufrimiento** | Tienes ventaja en las tiradas de salvación contra ser asustado. Además, ganas competencia en la habilidad de Intimidación. |
| **Idiomas** | Puedes hablar, leer y escribir en Común y en Goblin. |

### Sinergias de Clase

| Clase | Sinergia y Rol Sugerido |
| :--- | :--- |
| **[[Lithernia/04_Clases/Guerrero\|Guerrero]]** | **Óptima.** El arquetipo *Maestro de Batalla* se beneficia de la INT. `Disciplina de [[Kromagul]]` asegura golpes clave y `Tácticas del Dolor` (acción adicional) permite atacar y comandar en el mismo turno. |
| **Artífice** | **Excelente.** Un *Bélico* se beneficia de la alta CON para la primera línea y la INT para sus infusiones y [[Lithernia/06_Magia/Conjuros\|Conjuros]]. `Tácticas del Dolor` complementa su rol de apoyo en combate. |
| **[[Lithernia/04_Clases/Mago\|Mago]]** | **Buena.** La alta CON es vital para mantener la concentración. Un *[[Lithernia/04_Clases/Mago\|Mago]] de Guerra* se beneficia de la resistencia y de las opciones tácticas raciales. |
| **Paladín** | **Contextual.** Un *Juramento de Conquista* es temáticamente perfecto. La competencia en Intimidación de `Legado del Sufrimiento` potencia directamente su Canalizar Divinidad: Presencia Conquistadora. |
| **Pícaro** | **Buena.** El arquetipo *Mente Maestra* utiliza la acción de Ayudar como acción adicional, y esta raza se la concede de base, liberando el arquetipo para otras opciones o apilando sus beneficios. |

### PNJs y Monstruos

```statblock
name: Legionario Hobgoblin
size: Mediano
type: humanoide (goblin)
alignment: legal maligno
ac: 18 (Cota de malla, escudo)
hp: 11 (2d8 + 2)
speed: 30 ft.
stats: [13, 12, 12, 10, 10, 9]
senses: Visión en la oscuridad 60 ft., Percepción Pasiva 10
languages: Común, Goblin
cr: 1/2
traits:
  - name: Ventaja Marcial
    desc: "Una vez por turno, el hobgoblin puede infligir 7 (2d6) de daño adicional a una criatura que golpee con un ataque de arma si esa criatura está a 5 pies de un aliado del hobgoblin que no esté incapacitado."
actions:
  - name: Espada Larga
    desc: "Ataque de arma cuerpo a cuerpo: +3 a impactar, alcance 5 ft., un objetivo. Impacto: 5 (1d8 + 1) de daño cortante, o 6 (1d10 + 1) de daño cortante si se usa a dos manos."
  - name: Arco Largo
    desc: "Ataque de arma a distancia: +3 a impactar, alcance 150/600 ft., un objetivo. Impacto: 5 (1d8 + 1) de daño perforante."

```statblock
name: Capitán del Dolor
size: Mediano
type: humanoide (goblin)
alignment: legal maligno
ac: 17 (Armadura de Placas)
hp: 65 (10d8 + 20)
speed: 30 ft.
stats: [15, 14, 14, 14, 12, 15]
saves:
  - Int: +4
  - Sab: +3
  - Car: +4
skills:
  Intimidación: +6
  Percepción: +3
senses: Visión en la oscuridad 60 ft., Percepción Pasiva 13
languages: Común, Goblin
cr: 4
traits:
  - name: Aura de Disciplina
    desc: "Cualquier aliado que comience su turno a 10 pies del capitán y pueda verlo u oírlo, gana 5 puntos de golpe temporales. Estos puntos de golpe duran 1 minuto."
  - name: Ventaja Marcial
    desc: "Una vez por turno, el capitán puede infligir 10 (3d6) de daño adicional a una criatura que golpee con un ataque de arma si esa criatura está a 5 pies de un aliado del capitán que no esté incapacitado."
actions:
  - name: Multiataque
    desc: "El capitán realiza dos ataques con su Mangual Dentado."
  - name: Mangual Dentado
    desc: "Ataque de arma cuerpo a cuerpo: +4 a impactar, alcance 5 ft., un objetivo. Impacto: 6 (1d8 + 2) de daño contundente más 7 (2d6) de daño psíquico."
  - name: Grito Táctico (Recarga 5-6)
    desc: "El capitán elige hasta tres criaturas aliadas que pueda ver en un radio de 30 pies. Cada una puede usar su reacción para moverse hasta la mitad de su velocidad sin provocar ataques de oportunidad y realizar un ataque con arma."
reactions:
  - name: Castigo por Debilidad
    desc: "Cuando un enemigo a 5 pies del capitán falla un ataque contra él, el capitán puede realizar un ataque de oportunidad con su Mangual Dentado contra esa criatura."
