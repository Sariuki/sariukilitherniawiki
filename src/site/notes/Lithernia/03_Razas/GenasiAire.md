---
{"dg-publish":true,"permalink":"/lithernia/03-razas/genasi-aire/","title":"Genasiaire","tags":["lithernia","raza"]}
---

# Genasiaire

### Contexto Mecánico

| Característica | Vinculación en Lithernia |
| :--- | :--- |
| **Reino de Origen** | [[Lithernia/02_Reinos/Galvorn\|Galvorn]] |
| **Panteón Principal** | Panteón Humano (Dioses de [[Lithernia/02_Reinos/Galvorn\|Galvorn]]) |
| **Deidad Patrona** | [[Lithernia/09_Personajes/01_Dioses/Quiteon\|Quiteon]] |
| **Rol Social Típico** | Marinero, Vigía, Explorador, Mensajero. |
| **Trasfondos Sugeridos** | Marinero, Forastero, Artista, Charlatán. |
| **Dote Vinculada** | Ascensión de los vientos |

### Resumen de Rasgos

| Rasgo Clave | Valor |
| :--- | :--- |
| **Aumento de Característica** | +2 Destreza, +1 Carisma |
| **Velocidad** | 35 pies |
| **Resistencias** | Relámpago, Trueno |
| **Competencias** | Herramientas de navegante, Vehículos (acuáticos) |
| **Rasgos Únicos** | Lanzamiento de [[Lithernia/06_Magia/Conjuros\|Conjuros]] innato, Velocidad aumentada, Aliento interminable |

### Rasgos Raciales

| Rasgo | Descripción |
| :--- | :--- |
| **Incremento de Puntuación de Característica** | Tu puntuación de Destreza aumenta en 2 y tu puntuación de Carisma aumenta en 1. |
| **Edad** | Maduran al mismo ritmo que los [[Lithernia/03_Razas/Humanos\|Humanos]] y viven hasta 120 años. |
| **Alineamiento Típico** | Tendencia hacia lo Caótico (Bueno, Neutral). |
| **Tamaño** | Mediano. |
| **Velocidad** | Tu velocidad base al caminar es de 35 pies. |
| **Aliento Interminable** | Puedes aguantar la respiración indefinidamente mientras no estés incapacitado. |
| **Hijo de la Tormenta** | Tienes resistencia al daño de relámpago y de trueno. |
| **Susurros de [[Lithernia/09_Personajes/01_Dioses/Quiteon\|Quiteon]]** | Conoces el truco *Ráfaga de Viento (Gust)*. A partir del nivel 3, puedes lanzar *Caída de Pluma* una vez por descanso largo. A partir del nivel 5, puedes lanzar *Levitar* (solo sobre ti mismo) una vez por descanso largo. El Carisma es tu aptitud mágica para estos [[Lithernia/06_Magia/Conjuros\|Conjuros]]. |
| **Nacido en la Cofa** | Ganas competencia con las herramientas de navegante y los vehículos (acuáticos). |
| **Idiomas** | Puedes hablar, leer y escribir Común y Primordial (dialecto Auran). |

### Progresión de Conjuros Raciales

| Nivel de Personaje | Conjuro Obtenido | Frecuencia |
| :---: | :--- | :--- |
| **1** | *Ráfaga de Viento (Gust)* | A voluntad |
| **3** | *Caída de Pluma* | 1/Descanso Largo |
| **5** | *Levitar* (solo sobre ti mismo) | 1/Descanso Largo |

### Sinergias de Clase

| Clase | Sinergia y Rol Sugerido |
| :--- | :--- |
| **Pícaro** | **Óptima.** +2 DES, velocidad de 35 pies y [[Lithernia/06_Magia/Conjuros\|Conjuros]] de movilidad son excelentes para arquetipos como *Ladrón* o *Pícaro Arcano*. |
| **[[Lithernia/04_Clases/Monje\|Monje]]** | **Excelente.** La alta Destreza y la velocidad adicional se combinan con el movimiento del [[Lithernia/04_Clases/Monje\|Monje]]. *Levitar* mejora su movilidad táctica. |
| **[[Lithernia/04_Clases/Bardo\|Bardo]]** | **Fuerte.** El aumento a Destreza y Carisma encaja en los *Colegios del Valor* o de las *Espadas*. La movilidad adicional es un gran bono. |
| **[[Lithernia/04_Clases/Hechicero\|Hechicero]] / [[Lithernia/04_Clases/Brujo\|Brujo]]** | **Buena.** El +1 a CAR es el atributo principal. La resistencia y los [[Lithernia/06_Magia/Conjuros\|Conjuros]] innatos proporcionan supervivencia y utilidad. |
| **[[Lithernia/04_Clases/Guardabosques\|Guardabosques]] (Ranger)** | **Buena.** El +2 a DES es ideal para un arquero. La movilidad y la temática del viento encajan con un rol de explorador. |

### PNJ de Ejemplo

```statblock
name: Vigía del Viento Genasiaire
size: Mediano
type: humanoide (genasi)
alignment: caótico neutral
ac: 15 (Armadura de cuero)
hp: 44 (8d8 + 8)
speed: 35 ft.
stats: [11, 18, 12, 10, 13, 14]
skills:
  - Acrobacias: +6
  - Percepción: +3
  - Sigilo: +6
damage_resistances: Relámpago, Trueno
senses: Percepción Pasiva 13
languages: Común, Primordial
cr: 2
traits:
  - name: Lanzamiento de Conjuros Innato
    desc: "La aptitud mágica del vigía es el Carisma (CD de salvación de Conjuros 12). Puede lanzar los siguientes Conjuros de forma innata:\n\nA voluntad: *Ráfaga de viento (Gust)*\n1/día: *Caída de Pluma*"
actions:
  - name: Multiataque
    desc: "El vigía realiza dos ataques con su cimitarra."
  - name: Cimitarra
    desc: "Ataque de arma cuerpo a cuerpo: +6 a impactar, alcance 5 ft., un objetivo. Impacto: 7 (1d6 + 4) de daño cortante."
  - name: Arco Corto
    desc: "Ataque de arma a distancia: +6 a impactar, alcance 80/320 ft., un objetivo. Impacto: 7 (1d6 + 4) de daño perforante."
reactions:
  - name: Ráfaga Evasiva
    desc: "Cuando un enemigo termina su movimiento a 5 pies del vigía, este puede usar su reacción para forzar al enemigo a hacer una tirada de salvación de Fuerza CD 12. Si falla, el enemigo es empujado 10 pies hacia atrás y no puede volver a acercarse al vigía en este turno."
