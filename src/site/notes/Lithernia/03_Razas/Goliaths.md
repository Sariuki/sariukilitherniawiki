---
{"dg-publish":true,"permalink":"/lithernia/03-razas/goliaths/","title":"Goliath","tags":["lithernia","raza"]}
---

# Goliaths

### Contexto Mecánico

| Característica | Vinculación en Lithernia |
| :--- | :--- |
| **Reino de Origen** | [[Lithernia/02_Reinos/Valtoria\|Valtoria]] |
| **Panteón Principal** | Panteón Enano (Dioses de [[Lithernia/02_Reinos/Valtoria\|Valtoria]]) |
| **Deidad Asociada** | [[Lithernia/09_Personajes/01_Dioses/Trovdor\|Trovdor]] (Fuerza, Montaña), [[Lithernia/09_Personajes/01_Dioses/Rokael\|Rokael]] (Creación) |
| **Rol Social Típico** | Guardián de fortaleza, explorador de cumbres, [[Lithernia/04_Clases/Guerrero\|Guerrero]] de élite. Sugiere trasfondos como Forastero, Soldado o Ermitaño. |

### Resumen de Rasgos

| Rasgo Clave | Valor |
| :--- | :--- |
| **Aumento de Característica** | +2 Fuerza, +1 Constitución |
| **Velocidad** | 30 pies |
| **Competencias Clave** | Atletismo |
| **Rasgos Únicos** | Resistencia de la Piedra, Nacido en la Montaña, Corpulencia |

### Rasgos Raciales

| Rasgo | Descripción |
| :--- | :--- |
| **Incremento de Puntuación de Característica** | Tu puntuación de Fuerza aumenta en 2 y tu puntuación de Constitución aumenta en 1. |
| **Edad** | Maduran al final de la adolescencia y viven menos de un siglo. |
| **Alineamiento** | La sociedad goliath, con sus roles y reglas claramente definidos, tiene una fuerte inclinación hacia la ley. Valoran la autosuficiencia y la igualdad, por lo que tienden a la neutralidad. |
| **Tamaño** | Miden entre 7 y 8 pies de altura. Tu tamaño es Mediano. |
| **Velocidad** | Tu velocidad base al caminar es de 30 pies. |
| **Atleta Natural** | Tienes competencia en la habilidad de Atletismo. |
| **Resistencia de la Piedra** | Cuando recibes daño, puedes usar tu reacción para tirar 1d12. Suma tu modificador de Constitución al resultado y reduce el daño en esa cantidad. No puedes volver a usar este rasgo hasta que termines un descanso corto o largo. |
| **Nacido en la Montaña** | Estás aclimatado a la altitud elevada, incluyendo elevaciones por encima de los 20,000 pies. También tienes resistencia al daño por frío. |
| **Corpulencia** | Cuentas como si fueras un tamaño más grande para determinar tu capacidad de carga y el peso que puedes empujar, arrastrar o levantar. |
| **Idiomas** | Puedes hablar, leer y escribir Común y Gigante. |

### Sinergias de Clase

| Clase | Sinergia y Rol Sugerido |
| :--- | :--- |
| **Bárbaro** | **Óptima.** Los aumentos a FUE y CON son perfectos. `Resistencia de la Piedra` se suma a la ya increíble capacidad de aguante del bárbaro. |
| **[[Lithernia/04_Clases/Guerrero\|Guerrero]]** | **Excelente.** Un arquetipo de luchador ideal, beneficiándose directamente de los aumentos de estadísticas. `Corpulencia` y `Atleta Natural` lo hacen un excelente luchador de agarre. |
| **Paladín** | **Fuerte.** El +2 a FUE es clave. `Resistencia de la Piedra` proporciona una valiosa reacción defensiva que complementa las auras del paladín. |
| **Clérigo** | **Contextual.** Un Clérigo del Dominio de la [[Lithernia/11_Recetas/Herreria\|Herreria]] o de la Guerra puede aprovechar el +2 a FUE para ser un combatiente en primera línea, manteniendo la temática de [[Lithernia/02_Reinos/Valtoria\|Valtoria]]. |
| **[[Lithernia/05_Trasfondos/Cazador\|Cazador]] de [[Lithernia/07_Bestias_Monstruos/Dragones\|Dragones]]** | **Fuerte.** Esta clase de Lithernia encaja perfectamente en el rol de un [[Lithernia/04_Clases/Guerrero\|Guerrero]] resistente, aprovechando su fuerza y constitución. |

### PNJ de Ejemplo

```statblock
name: Guardián de Cima Goliath
size: Mediano
type: humanoide (goliath)
alignment: legal neutral
ac: 14 (Armadura de escamas)
hp: 60 (8d8 + 24)
speed: 30 ft.
stats: [18, 12, 16, 10, 13, 11]
skills:
  - Atletismo: +6
  - Percepción: +3
damage_resistances: Frío
senses: Percepción Pasiva 13
languages: Común, Gigante
cr: 2
traits:
  - name: Nacido en la Montaña
    desc: "El guardián está aclimatado a la gran altitud y tiene resistencia al daño por frío."
  - name: Corpulencia
    desc: "El guardián cuenta como si fuera de tamaño Grande para determinar su capacidad de carga."
actions:
  - name: Multiataque
    desc: "El guardián realiza dos ataques con su Gran Hacha."
  - name: Gran Hacha
    desc: "Ataque de arma cuerpo a cuerpo: +6 a impactar, alcance 5 ft., un objetivo. Impacto: 10 (1d12 + 4) de daño cortante."
  - name: Roca
    desc: "Ataque de arma a distancia: +6 a impactar, alcance 30/120 ft., un objetivo. Impacto: 7 (1d6 + 4) de daño contundente."
reactions:
  - name: Resistencia de la Piedra (Recarga tras Descanso Corto o Largo)
    desc: "Cuando el guardián recibe daño, puede usar su reacción para tirar 1d12, añadir su modificador de Constitución (+3), y reducir el daño en esa cantidad."
