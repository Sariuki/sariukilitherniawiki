---
{"dg-publish":true,"permalink":"/lithernia/03-razas/semiorcos/","title":"Semiorcos","tags":["lithernia","raza"]}
---

# Semiorcos

### Resumen de Rasgos

| Rasgo Clave | Valor |
| :--- | :--- |
| **Aumento de Característica** | +2 Fuerza, +1 Constitución |
| **Velocidad** | 30 pies |
| **Visión** | Visión en la Oscuridad (60 pies) |
| **Competencias Clave** | Intimidación |
| **Rasgos Únicos** | Resistencia Implacable, Ataques Salvajes |

### Contexto Mecánico

| Característica | Vinculación en Lithernia |
| :--- | :--- |
| **Reino de Origen** | [[Lithernia/02_Reinos/Galvorn\|Galvorn]] (Principal), [[Lithernia/02_Reinos/Mor'dhul\|Mor'dhul]] |
| **Panteón Principal** | Panteón Korogrim (Herencia Ancestral), Panteón Humano (Dioses de [[Lithernia/02_Reinos/Galvorn\|Galvorn]]) (Cultura Adoptiva) |
| **Deidades Comunes** | [[Lithernia/09_Personajes/01_Dioses/Thyrgram\|Thyrgram]], [[Lithernia/09_Personajes/01_Dioses/Yfrit\|Yfrit]] |
| **Alineamiento Típico** | Caótico Neutral |

### Trasfondos Sugeridos

| Trasfondo | Rol Temático Sugerido |
| :--- | :--- |
| **Marinero** | Miembro robusto de la tripulación de un barco de [[Lithernia/02_Reinos/Galvorn\|Galvorn]], valorado por su fuerza. |
| **Soldado** | Un mercenario o soldado de infantería en los ejércitos [[Lithernia/03_Razas/Humanos\|Humanos]] o en un clan orco. |
| **Forastero** | Un semiorco que vive en los márgenes de la sociedad, confiando en su fuerza para sobrevivir. |
| **Gladiador** | Un luchador de las arenas, común en los enclaves más brutales de [[Lithernia/02_Reinos/Mor'dhul\|Mor'dhul]]. |

### Rasgos Raciales

| Rasgo | Descripción |
| :--- | :--- |
| **Incremento de Puntuación de Característica** | Tu puntuación de Fuerza aumenta en 2 y tu puntuación de Constitución aumenta en 1. |
| **Edad** | Maduran alrededor de los 14 años. Rara vez viven más de 75 años. |
| **Alineamiento** | Tienden al caos por su herencia orca. Valoran la libertad personal y la camaradería, siendo a menudo Caótico Neutral. |
| **Tamaño** | Mediano. Miden entre 6 y 7 pies de altura. |
| **Velocidad** | Tu velocidad base al caminar es de 30 pies. |
| **Visión en la Oscuridad** | Puedes ver en luz tenue hasta 60 pies como si fuera luz brillante, y en la oscuridad como si fuera luz tenue. Solo percibes tonos de gris en la oscuridad. |
| **Amenaza** | Ganas competencia en la habilidad de Intimidación. |
| **Resistencia Implacable** | Cuando eres reducido a 0 puntos de golpe pero no mueres directamente, puedes elegir quedar con 1 punto de golpe en su lugar. No puedes usar este rasgo hasta que termines un descanso largo. |
| **Ataques Salvajes** | Cuando obtienes un golpe crítico con un ataque de arma cuerpo a cuerpo, puedes tirar uno de los dados de daño del arma una vez más y añadirlo al daño extra del golpe crítico. |
| **Idiomas** | Puedes hablar, leer y escribir en Común y Orco. |

### Sinergias de Clase

| Clase | Sinergia y Rol Sugerido |
| :--- | :--- |
| **Bárbaro** | **Óptima.** La combinación de +2 FUE, +1 CON, `Resistencia Implacable` y `Ataques Salvajes` está perfectamente diseñada para un bárbaro. |
| **[[Lithernia/04_Clases/Guerrero\|Guerrero]]** | **Excelente.** Un combatiente de primera línea natural. `Ataques Salvajes` maximiza el potencial de daño de arquetipos como el [[Lithernia/09_Personajes/Heroes\|Heroes]]. |
| **Paladín** | **Fuerte.** Una opción muy resistente para un paladín de primera línea, donde FUE y CON son clave. `Resistencia Implacable` aumenta su durabilidad. |
| **[[Lithernia/05_Trasfondos/Cazador\|Cazador]] de [[Lithernia/07_Bestias_Monstruos/Dragones\|Dragones]]**| **Fuerte.** La clase se beneficia directamente del modificador de CON para sus Puntos de Maná, haciendo del Semiorco una opción temática y mecánicamente poderosa. |

### PNJ de Ejemplo

```statblock
name: Bruto Semiorco
size: Mediano
type: humanoide (semiorco)
alignment: caótico neutral
ac: 13 (Armadura de pieles)
hp: 45 (6d8 + 18)
speed: 30 ft.
stats: [18, 12, 16, 8, 11, 10]
skills:
  - Intimidación: +2
  - Atletismo: +6
senses: Visión en la oscuridad 60 ft., Percepción Pasiva 10
languages: Común, Orco
cr: 2
traits:
  - name: Resistencia Implacable (1/Día)
    desc: "Si el semiorco es reducido a 0 puntos de golpe pero no muere directamente, puede elegir quedar con 1 punto de golpe en su lugar."
  - name: Ataques Salvajes
    desc: "Cuando el semiorco obtiene un golpe crítico con un ataque de arma cuerpo a cuerpo, puede tirar uno de los dados de daño del arma una vez más y añadirlo al daño extra del golpe crítico."
actions:
  - name: Gran Hacha
    desc: "Ataque de arma cuerpo a cuerpo: +6 a impactar, alcance 5 ft., un objetivo. Impacto: 10 (1d12 + 4) de daño cortante."
  - name: Jabalina
    desc: "Ataque de arma a distancia: +6 a impactar, alcance 30/120 ft., un objetivo. Impacto: 7 (1d6 + 4) de daño perforante."
