---
{"dg-publish":true,"permalink":"/lithernia/03-razas/genasi-tierra/","title":"Genasitierra","tags":["lithernia","raza","genasi"]}
---

# Genasitierra

### Contexto Mecánico

| Característica | Vinculación en Lithernia |
| :--- | :--- |
| **Reino de Origen** | [[Lithernia/02_Reinos/Valtoria\|Valtoria]] |
| **Panteón Principal** | Panteón Enano (Dioses de [[Lithernia/02_Reinos/Valtoria\|Valtoria]]) |
| **Deidades Creadoras** | [[Lithernia/09_Personajes/01_Dioses/Cirkon\|Cirkon]], [[Lithernia/09_Personajes/01_Dioses/Valarios\|Valarios]] |
| **Rol Social Típico** | Guardián de enclaves, sabio de las minas, [[Lithernia/04_Clases/Guerrero\|Guerrero]] estoico, [[Lithernia/04_Clases/Druida\|Druida]] elemental. Sugiere trasfondos como Ermitaño, Forastero o Sabio. |

### Rasgos Raciales

| Rasgo | Descripción |
| :--- | :--- |
| **Incremento de Puntuación de Característica** | Tu puntuación de Constitución aumenta en 2 y tu puntuación de Fuerza aumenta en 1. |
| **Edad** | Maduran al mismo ritmo que los [[Lithernia/03_Razas/Humanos\|Humanos]] y alcanzan la edad adulta al final de su adolescencia. Viven hasta 120 años. |
| **Alineamiento** | Reflejando la estabilidad y paciencia de la montaña, los genasitierra tienden hacia la neutralidad. Valoran el equilibrio y la perseverancia. |
| **Tamaño** | Mediano. Miden entre 1,5 y 1,8 metros, con una constitución robusta. |
| **Velocidad** | Tu velocidad base al caminar es de 30 pies. |
| **Caminar por la Tierra** | Puedes moverte a través de terreno difícil hecho de tierra o piedra sin gastar movimiento adicional. |
| **Fundirse con la Piedra** | Eres capaz de canalizar la magia primordial de la tierra. La Constitución es tu aptitud mágica para estos [[Lithernia/06_Magia/Conjuros\|Conjuros]]. |
| **Idiomas** | Puedes hablar, leer y escribir en Común y Primordial. |

### Progresión de Hechizos Raciales

Tu rasgo `Fundirse con la Piedra` te otorga acceso a los siguientes [[Lithernia/06_Magia/Conjuros\|Conjuros]]:

| Nivel de Personaje | Conjuro Obtenido | Frecuencia |
| :---: | :--- | :--- |
| **1** | *Moldear Tierra* | A voluntad (Truco) |
| **3** | *Pasar sin Rastro* | 1 vez por Descanso Largo |
| **5** | *Crecimiento de Espinas* | 1 vez por Descanso Largo |

### Sinergias de Clase

| Clase | Sinergia y Rol Sugerido |
| :--- | :--- |
| **Bárbaro** | **Óptima.** El aumento a FUE y CON es perfecto. `Caminar por la Tierra` mejora la movilidad en el campo de batalla y los [[Lithernia/06_Magia/Conjuros\|Conjuros]] innatos ofrecen utilidad táctica. |
| **[[Lithernia/04_Clases/Guerrero\|Guerrero]]** | **Excelente.** Un combatiente de primera línea muy resistente. Los bonos a FUE y CON son ideales para cualquier arquetipo de [[Lithernia/04_Clases/Guerrero\|Guerrero]]. |
| **[[Lithernia/05_Trasfondos/Cazador\|Cazador]] de [[Lithernia/07_Bestias_Monstruos/Dragones\|Dragones]]** | **Óptima.** La clase se beneficia directamente del modificador de CON para sus Puntos de Maná, haciendo a esta raza una opción temática y mecánicamente poderosa. |
| **Paladín** | **Fuerte.** Aunque no aumenta el Carisma, la FUE y la CON lo convierten en un baluarte defensivo formidable, especialmente en la primera línea. |
| **[[Lithernia/04_Clases/Sacerdote\|Sacerdote]] (Clérigo)** | **Buena.** Especialmente para dominios de combate cuerpo a cuerpo como [[Lithernia/11_Recetas/Herreria\|Herreria]], Guerra o Naturaleza. El bono a CON aumenta la capacidad de supervivencia. |
| **[[Lithernia/04_Clases/Druida\|Druida]]** | **Contextual.** Un [[Lithernia/04_Clases/Druida\|Druida]] del Círculo de la Luna se beneficia del aumento de CON para su Forma Salvaje. Los [[Lithernia/06_Magia/Conjuros\|Conjuros]] raciales complementan el repertorio del [[Lithernia/04_Clases/Druida\|Druida]]. |

### PNJ de Ejemplo

```statblock
name: Guardián de Piedra Genasi
size: Mediano
type: humanoide (genasi)
alignment: legal neutral
ac: 16 (Cota de escamas)
hp: 52 (7d8 + 21)
speed: 30 ft.
stats: [16, 12, 17, 10, 14, 11]
saves:
  - Str: +5
  - Con: +5
skills:
  - Atletismo: +5
  - Percepción: +4
senses: Percepción pasiva 14
languages: Común, Primordial
cr: 2
traits:
  - name: Caminar por la Tierra
    desc: "El guardián puede moverse a través de terreno difícil hecho de tierra o piedra sin gastar movimiento adicional."
  - name: Lanzamiento de Conjuros Innato
    desc: "La aptitud mágica del guardián es la Constitución (CD de salvación de Conjuros 13). Puede lanzar los siguientes Conjuros de forma innata:\n\nA voluntad: *Moldear tierra*\n1/día: *Pasar sin rastro*"
actions:
  - name: Multiataque
    desc: "El guardián realiza dos ataques con su Martillo de Guerra."
  - name: Martillo de Guerra
    desc: "Ataque de arma cuerpo a cuerpo: +5 a impactar, alcance 5 ft., un objetivo. Impacto: 7 (1d8 + 3) de daño contundente, o 8 (1d10 + 3) si se usa a dos manos."
