---
{"dg-publish":true,"permalink":"/lithernia/03-razas/genasi-fuego/","title":"Genasifuego","tags":["lithernia","raza"]}
---

# Genasifuego

### Resumen de Rasgos

| Rasgo Clave | Valor |
| :--- | :--- |
| **Aumento de Característica** | +2 a una, +1 a otra; o +1 a tres distintas |
| **Velocidad** | 30 pies |
| **Visión** | Visión en la Oscuridad (60 pies) |
| **Resistencias** | Daño por Fuego |
| **Rasgos Únicos** | Legado Ígneo ([[Lithernia/06_Magia/Conjuros\|Conjuros]] raciales basados en CON) |

### Contexto Mecánico

| Característica | Vinculación en Lithernia |
| :--- | :--- |
| **Reino de Origen** | [[Lithernia/02_Reinos/Galvorn\|Galvorn]] (migrados de zonas volcánicas) |
| **Panteón Principal** | Panteón Humano (Dioses de [[Lithernia/02_Reinos/Galvorn\|Galvorn]]) |
| **Deidad Patrona Común** | [[Lithernia/09_Personajes/01_Dioses/Solniria\|Solniria]], diosa del fuego y la [[Lithernia/11_Recetas/Herreria\|Herreria]] |
| **Rol Social Típico** | Herrero, [[Lithernia/04_Clases/Guerrero\|Guerrero]], Piromante. Sugiere trasfondos como Artesano, Soldado o Forastero. |
| **Alineamiento Típico** | Neutral, Caótico Neutral. |

### Rasgos Raciales

| Rasgo | Descripción |
| :--- | :--- |
| **Tipo de Criatura** | Humanoide (Genasi) |
| **Tamaño** | Mediano |
| **Velocidad** | Tu velocidad base al caminar es de 30 pies. |
| **Incremento de Puntuación de Característica** | Incrementa una puntuación de característica en 2 y otra diferente en 1, o incrementa tres puntuaciones de característica diferentes en 1. |
| **Visión en la Oscuridad** | Puedes ver en la luz tenue a menos de 60 pies de ti como si fuera luz brillante, y en la oscuridad como si fuera luz tenue. No puedes discernir colores en la oscuridad, sólo tonos de gris. |
| **Resistencia al Fuego** | Tienes resistencia al daño por fuego. |
| **Legado Ígneo** | Conoces el truco *Producir Llama*. A partir del nivel 3, puedes lanzar el conjuro *Manos Ardientes* una vez por descanso largo. A partir del nivel 5, puedes lanzar el conjuro *Acalorar Metal* una vez por descanso largo, sin necesidad de componentes materiales. La Constitución es tu aptitud mágica para estos [[Lithernia/06_Magia/Conjuros\|Conjuros]]. |
| **Idiomas** | Puedes hablar, leer y escribir en Común y en Primordial. |

### Progresión de Conjuros Raciales

| Nivel de Personaje | Conjuro Obtenido (basado en CON) | Frecuencia |
| :---: | :--- | :--- |
| **1** | *Producir Llama* (Truco) | A voluntad |
| **3** | *Manos Ardientes* (Nivel 1) | 1/Descanso Largo |
| **5** | *Acalorar Metal* (Nivel 2) | 1/Descanso Largo |

### Sinergias de Clase

| Clase | Sinergia y Rol Sugerido |
| :--- | :--- |
| **Bárbaro** | **Excelente.** Resistencia al fuego temática para furia ardiente. La Constitución es clave y potencia los [[Lithernia/06_Magia/Conjuros\|Conjuros]] raciales. |
| **[[Lithernia/04_Clases/Guerrero\|Guerrero]]** | **Fuerte.** Los [[Lithernia/06_Magia/Conjuros\|Conjuros]] raciales basados en CON ofrecen opciones tácticas sin depender de atributos mentales. La resistencia al fuego es un bono defensivo sólido. |
| **[[Lithernia/04_Clases/Hechicero\|Hechicero]]** | **Fuerte.** Un [[Lithernia/04_Clases/Hechicero\|Hechicero]] de Linaje Dracónico (Rojo/Oro) es temáticamente perfecto. La CON para los [[Lithernia/06_Magia/Conjuros\|Conjuros]] raciales ayuda a mantener la concentración. |
| **Artífice** | **Buena.** Especialmente para el Armero o Batallador. La temática del fuego y el metal encaja perfectamente. *Acalorar Metal* es un conjuro excelente para la clase. |
| **[[Lithernia/04_Clases/Mago\|Mago]]** | **Buena.** La CON es vital para la supervivencia y la concentración de cualquier [[Lithernia/04_Clases/Mago\|Mago]]. La Escuela de Evocación es una elección obvia. |

### PNJ de Ejemplo

```statblock
name: Forjador de Furia Genasifuego
size: Mediano
type: humanoide (genasi)
alignment: caótico neutral
ac: 16 (Armadura de media placa)
hp: 68 (8d8 + 32)
speed: 30 ft.
stats: [18, 12, 18, 10, 11, 14]
saves:
  - Str: +7
  - Con: +7
skills:
  - Atletismo: +7
  - Intimidación: +5
damage_resistances: Fuego
senses: Visión en la oscuridad 60 ft., Percepción Pasiva 10
languages: Común, Primordial
cr: 4
traits:
  - name: Legado Ígneo
    desc: "La aptitud mágica del Forjador es la Constitución (CD de salvación de Conjuros 15). Puede lanzar los siguientes Conjuros:\n\nA voluntad: *Producir Llama*\n1/día cada uno: *Manos Ardientes*, *Acalorar Metal*"
actions:
  - name: Multiataque
    desc: "El Forjador realiza dos ataques con su Martillo de Guerra."
  - name: Martillo de Guerra
    desc: "Ataque de Arma Cuerpo a Cuerpo: +7 a impactar, alcance 5 ft., un objetivo. Impacto: 8 (1d8 + 4) de daño contundente más 3 (1d6) de daño por fuego."
  - name: Aliento de la Forja (Recarga 6)
    desc: "El Forjador exhala una ráfaga de brasas en un cono de 15 pies. Cada criatura en esa área debe realizar una tirada de salvación de Destreza CD 15, recibiendo 14 (4d6) de daño por fuego si falla la tirada, o la mitad si tiene éxito."
