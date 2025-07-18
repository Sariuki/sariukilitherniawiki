---
{"dg-publish":true,"permalink":"/lithernia/03-razas/gnomos/","title":"Gnomos","tags":["lithernia","raza"]}
---

# Gnomos

### Resumen de Rasgos

| Rasgo Clave | Valor |
| :--- | :--- |
| **Aumento de Característica** | +2 Inteligencia, +1 Constitución |
| **Velocidad** | 25 pies |
| **Visión** | Visión en la Oscuridad (60 pies) |
| **Competencias Clave** | Herramientas de Manitas |
| **Rasgos Únicos** | Astucia Gnoma, Saber del Artífice, Manitas |

### Contexto Mecánico

| Característica | Vinculación en Lithernia |
| :--- | :--- |
| **Reino de Origen** | [[Lithernia/02_Reinos/Valtoria\|Valtoria]] |
| **Panteón Principal** | Panteón Enano (Dioses de [[Lithernia/02_Reinos/Valtoria\|Valtoria]]) |
| **Deidad Patrona Común** | [[Lithernia/09_Personajes/01_Dioses/Rokael\|Rokael]] (Creación, invención) |
| **Rol Social Típico** | Artífice, Inventor, [[Lithernia/04_Clases/Mago\|Mago]], [[Lithernia/05_Trasfondos/Erudito\|Erudito]]. Sugiere trasfondos como Artesano Gremial o Sabio. |

### Rasgos Raciales

| Rasgo | Descripción |
| :--- | :--- |
| **Incremento de Puntuación de Característica** | Tu puntuación de Inteligencia aumenta en 2 y tu puntuación de Constitución aumenta en 1. |
| **Edad** | Alcanzan la madurez a los 40 años. Viven entre 350 y 500 años. |
| **Alineamiento Típico** | Legal Bueno, Caótico Bueno. |
| **Tamaño** | Pequeño. |
| **Velocidad** | Tu velocidad base al caminar es de 25 pies. |
| **Visión en la Oscuridad** | Puedes ver en luz tenue hasta 60 pies como si fuera luz brillante, y en la oscuridad como si fuera luz tenue. No puedes discernir colores en la oscuridad, solo tonos de gris. |
| **Astucia Gnoma** | Tienes ventaja en todas las tiradas de salvación de Inteligencia, Sabiduría y Carisma contra la magia. |
| **Saber del Artífice** | Cuando realizas una prueba de Inteligencia (Historia) relacionada con objetos mágicos, objetos alquímicos o dispositivos tecnológicos, se te considera competente y añades el doble de tu bonificador de competencia a la prueba. |
| **Manitas** | Ganas competencia con las herramientas de artesano (herramientas de manitas). Puedes crear dispositivos de relojería (ver tabla a continuación). |
| **Idiomas** | Puedes hablar, leer y escribir Común, Gnómico y Enano. |

### Habilidad Racial: Manitas

Usando herramientas de manitas, puedes gastar 1 hora y 10 po en materiales para construir un dispositivo de relojería Diminuto (CA 5, 1 PV). El dispositivo deja de funcionar después de 24 horas (a menos que gastes 1 hora reparándolo) o cuando usas tu acción para desmantelarlo, recuperando los materiales. Puedes tener un máximo de tres de estos dispositivos a la vez.

| Dispositivo | Efecto Mecánico |
| :--- | :--- |
| **Juguete de Relojería** | Al colocarlo en el suelo, el juguete se mueve 5 pies en una dirección aleatoria en cada uno de tus turnos, emitiendo sonidos apropiados a su forma (animal, monstruo, etc.). |
| **Encendedor** | Como una acción, puedes usar el dispositivo para producir una pequeña llama, suficiente para encender una vela, antorcha o hoguera. |
| **Caja de Música** | Al abrirse, reproduce una única canción a un volumen moderado. Se detiene al final de la canción o al cerrarse. |

### Sinergias de Clase

| Clase | Sinergia y Rol Sugerido |
| :--- | :--- |
| **[[Lithernia/04_Clases/Mago\|Mago]]** | **Óptima.** El +2 a INT es el atributo principal. `Astucia Gnoma` proporciona una excelente defensa mágica. Ideal para las Escuelas de Ilusión o Transmutación. |
| **Artífice / [[Lithernia/04_Clases/Gunsmith\|Gunsmith]]** | **Óptima.** El +2 a INT es clave. Las habilidades `Saber del Artífice` y `Manitas` son temáticamente perfectas y mecánicamente sinérgicas. |
| **Pícaro** | **Fuerte.** El arquetipo *Pícaro Arcano* se beneficia directamente del +2 a INT. `Astucia Gnoma` aumenta la capacidad de supervivencia contra [[Lithernia/06_Magia/Conjuros\|Conjuros]]. |
| **[[Lithernia/04_Clases/Guerrero\|Guerrero]]** | **Contextual.** Útil para un *[[Lithernia/04_Clases/Caballero\|Caballero]] Arcano*, que utiliza la Inteligencia para sus [[Lithernia/06_Magia/Conjuros\|Conjuros]]. El tamaño pequeño impone desventaja con armas pesadas. |

### PNJ de Ejemplo

```statblock
name: Inventor Gnomo
size: Pequeño
type: humanoide (gnomo)
alignment: caótico bueno
ac: 12 (Armadura de cuero)
hp: 22 (5d6 + 5)
speed: 25 ft.
stats: [8, 14, 12, 18, 10, 11]
saves:
  - Int: +6
  - Sab: +2
skills:
  - Arcanos: +6
  - Investigación: +6
senses: Visión en la oscuridad 60 ft., Percepción Pasiva 10
languages: Común, Gnómico, Enano
cr: 1
traits:
  - name: Astucia Gnoma
    desc: "El gnomo tiene ventaja en las tiradas de salvación de Inteligencia, Sabiduría y Carisma contra magia."
  - name: Lanzamiento de Conjuros Innato
    desc: "La aptitud mágica del gnomo es la Inteligencia (CD de salvación de Conjuros 14). Puede lanzar los siguientes Conjuros de forma innata:\n\nA voluntad: *Luz, Remendar, Prestidigitación*\n1/día cada uno: *Detectar magia, Alarma, Grasa*"
actions:
  - name: Daga
    desc: "Ataque de arma cuerpo a cuerpo o a distancia: +4 a impactar, alcance 5 ft. o rango 20/60 ft., un objetivo. Impacto: 4 (1d4 + 2) de daño perforante."
  - name: Desplegar Artilugio (Recarga 5-6)
    desc: "El gnomo despliega uno de sus inventos. Tira un d4 para determinar el efecto:\n**1: Araña de Choque.** La araña mecánica se mueve 20 pies hacia un enemigo y explota. La criatura debe superar una salvación de Destreza CD 14 o recibir 7 (2d6) de daño de rayo.\n**2: Humo de Distracción.** El gnomo crea una nube de humo de 10 pies de radio. El área se considera muy oscura. El humo se disipa en 1 minuto.\n**3: Nudo Mecánico.** El gnomo lanza un dispositivo que intenta apresar a una criatura Mediana o más pequeña. El objetivo debe superar una salvación de Destreza CD 14 o quedar apresado (escapar CD 14).\n**4: Cohete Inestable.** El gnomo lanza un cohete que impacta en un punto a 60 pies. Cada criatura en un radio de 5 pies debe hacer una salvación de Destreza CD 14, recibiendo 10 (3d6) de daño de fuego si falla, o la mitad si tiene éxito."
