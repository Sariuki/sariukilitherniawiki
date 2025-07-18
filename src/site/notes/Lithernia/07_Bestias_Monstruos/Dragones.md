---
{"dg-publish":true,"permalink":"/lithernia/07-bestias-monstruos/dragones/","title":"Dragones"}
---

# Dragones

### Perfil de la Criatura

| Atributo | Descripción |
| :--- | :--- |
| **Tipo de Criatura** | Dragón |
| **Alineamiento Típico** | Variable (Metálicos: Legales/Buenos; Cromáticos: Caóticos/Malignos) |
| **Nivel de Desafío** | 10 - 30+ (variable por edad y tipo) |
| **Rol Táctico** | Peligro Solitario, Controlador de Área, Combatiente de Élite |
| **Entorno Común** | Montañas, ruinas, volcanes, abismos, guaridas aisladas |
| **Linajes Ancestrales** | #Dragones Ancestrales ([[Lithernia/09_Personajes/02_Figuras_Historicas/Ignis\|Ignis]], Tal'vorak, [[Lithernia/09_Personajes/02_Figuras_Historicas/Fidriel\|Fidriel]], [[Lithernia/09_Personajes/02_Figuras_Historicas/Sariel\|Sariel]]) |

### Tabla de Conocimiento (Prueba de Habilidad)

| CD | Habilidad | Conocimiento Revelado |
| :--- | :--- | :--- |
| **10** | Historia / Naturaleza | Identifica a la criatura como un verdadero dragón, un ser inteligente y antiguo con un arma de aliento elemental y una fuerza formidable. |
| **15** | Arcanos / Historia | Diferencia entre los linajes principales: los Cromáticos (malignos y destructivos) y los Metálicos (nobles y a menudo benévolos). Conoce las vulnerabilidades comunes. |
| **20** | Historia | Recuerda [[Lithernia/09_Personajes/Leyendas\|Leyendas]] sobre las Guerras Dracónicas, la Caída Dragónica y cómo su dominio dio paso a la Era del Primer Rey. |
| **25** | Arcanos / Religión | Conoce la existencia de los cuatro Dragones Ancestrales (#Dragones Ancestrales ([[Lithernia/09_Personajes/02_Figuras_Historicas/Ignis\|Ignis]], Tal'vorak, [[Lithernia/09_Personajes/02_Figuras_Historicas/Fidriel\|Fidriel]], [[Lithernia/09_Personajes/02_Figuras_Historicas/Sariel\|Sariel]])) y su papel en la [[Lithernia/11_Recetas/Herreria\|Herreria]] del Mundo. |

### Plantilla de Categoría de Edad

Aplica estas modificaciones a una estadística base de Dragón **Adulto**.

| Edad | Modificador de CR | Puntos de Golpe | Ataque / Daño | CD Salvación | Acciones Legendarias |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Cría** | -12 | × 0.25 | -8 | -6 | No |
| **Joven** | -7 | × 0.5 | -4 | -3 | No |
| **Adulto** | Base | Base | Base | Base | Sí (3/turno) |
| **Anciano** | +6 | × 1.75 | +5 | +4 | Sí (3/turno) |
| **Ancestral** | +10 (Mítico) | × 3.0 | +8 | +6 | Sí (4/turno) + Acciones Míticas |

### Tabla de Componentes de Dragón

| Componente | CD de Recolección (Medicina o Supervivencia) | Usos Mecánicos |
| :--- | :--- | :--- |
| **Escamas (1d6)** | 15 | Pueden ser forjadas en una armadura que concede resistencia al tipo de daño del aliento del dragón. |
| **Sangre (1d4 viales)** | 18 | Ingrediente para pociones de resistencia elemental o tintas para pergaminos de [[Lithernia/06_Magia/Conjuros\|Conjuros]] de alto nivel. |
| **Corazón** | 20 | Componente de ritual para crear objetos mágicos legendarios o para [[Lithernia/06_Magia/Conjuros\|Conjuros]] de resurrección de alto poder. |
| **Diente o Garra** | 13 | Puede ser forjado como la punta de un arma mágica +1. |

### Dragones Ancestrales (Ignis, Tal'vorak, Fidriel, Sariel)

Estas entidades son de poder casi divino (CR 30+ o Mítico) y no pueden ser representadas por bloques de estadísticas convencionales. Sus acciones son eventos que alteran el mundo.

| Ancestro | Alineamiento | Aliento Primordial | Dominio de Influencia |
| :--- | :--- | :--- | :--- |
| **[[Lithernia/09_Personajes/02_Figuras_Historicas/Ignis\|Ignis]]** | Legal Bueno | Fuego y Creación | [[Lithernia/11_Recetas/Herreria\|Herreria]], Montañas, Volcanes, Dragones Metálicos |
| **Tal'vorak** | Caótico Maligno | Tormenta y Furia | Tempestades, Conquista, Dragones Cromáticos |
| **[[Lithernia/09_Personajes/02_Figuras_Historicas/Fidriel\|Fidriel]]** | Legal Neutral | Rayo y Sabiduría | Conocimiento, Magia, Inspiración |
| **[[Lithernia/09_Personajes/02_Figuras_Historicas/Sariel\|Sariel]]** | Neutral Maligno | Sombra y Drenaje Vital | Noche, Nigromancia, Secretos, Dragones Vampiros |

### Bloques de Estadísticas

```statblock
name: Dragón Rojo Adulto
size: Enorme
type: dragón
alignment: caótico maligno
ac: 19 (Armadura natural)
hp: 256 (19d12 + 133)
speed: 40 pies, escalar 40 pies, volar 80 pies
stats: [27, 10, 25, 16, 13, 21]
saves:
  - Dex: +5
  - Con: +12
  - Sab: +6
  - Car: +10
skills:
  - Percepción: +11
  - Sigilo: +5
damage_immunities: Fuego
senses: Vista Ciega 60 pies, Visión en la oscuridad 120 pies, Percepción Pasiva 21
languages: Común, Dracónico
cr: 17
traits:
  - name: Resistencia Legendaria (3/Día)
    desc: "Si el dragón falla una tirada de salvación, puede elegir tener éxito en su lugar."
actions:
  - name: Multiataque
    desc: "El dragón puede usar su Presencia Aterradora. Luego realiza tres ataques: uno con su mordisco y dos con sus garras."
  - name: Mordisco
    desc: "Ataque de Arma Cuerpo a Cuerpo: +13 a impactar, alcance 10 pies, un objetivo. Impacto: 19 (2d10 + 8) de daño perforante más 7 (2d6) de daño por fuego."
  - name: Garra
    desc: "Ataque de Arma Cuerpo a Cuerpo: +13 a impactar, alcance 5 pies, un objetivo. Impacto: 15 (2d6 + 8) de daño cortante."
  - name: Cola
    desc: "Ataque de Arma Cuerpo a Cuerpo: +13 a impactar, alcance 15 pies, un objetivo. Impacto: 17 (2d8 + 8) de daño contundente."
  - name: Presencia Aterradora
    desc: "Cada criatura a elección del dragón que esté a 120 pies de él y sea consciente de él debe superar una tirada de salvación de Sabiduría CD 18 o quedará asustada durante 1 minuto."
  - name: Aliento de Fuego (Recarga 5-6)
    desc: "El dragón exhala fuego en un cono de 60 pies. Cada criatura en esa área debe realizar una tirada de salvación de Destreza CD 20, sufriendo 63 (18d6) de daño por fuego si falla la tirada, o la mitad si tiene éxito."
legendary_actions:
  - name: Detectar
    desc: "El dragón realiza una prueba de Sabiduría (Percepción)."
  - name: Ataque de Cola
    desc: "El dragón realiza un ataque de cola."
  - name: Ataque de Ala (Cuesta 2 Acciones)
    desc: "El dragón bate sus alas. Cada criatura a 10 pies del dragón debe superar una tirada de salvación de Destreza CD 21 o recibirá 15 (2d6 + 8) de daño contundente y quedará tumbada. El dragón puede entonces volar hasta la mitad de su velocidad de vuelo."

```statblock
name: Dragón de las Sombras Adulto
size: Enorme
type: dragón
alignment: neutral maligno
ac: 18 (Armadura natural)
hp: 225 (18d12 + 108)
speed: 40 pies, escalar 40 pies, volar 80 pies
stats: [23, 12, 23, 18, 15, 19]
saves:
  - Dex: +6
  - Con: +11
  - Sab: +7
  - Car: +9
skills:
  - Percepción: +12
  - Sigilo: +11
damage_immunities: Necrótico
senses: Vista Ciega 60 pies, Visión en la oscuridad 120 pies, Percepción Pasiva 22
languages: Común, Dracónico, Infracomún
cr: 16
traits:
  - name: Resistencia Legendaria (3/Día)
    desc: "Si el dragón falla una tirada de salvación, puede elegir tener éxito en su lugar."
  - name: Camuflaje de Sombras
    desc: "El dragón tiene ventaja en las pruebas de Destreza (Sigilo) hechas para esconderse en penumbra u oscuridad."
actions:
  - name: Multiataque
    desc: "El dragón puede usar su Presencia Espectral. Luego realiza tres ataques: uno con su mordisco y dos con sus garras."
  - name: Mordisco Vampírico
    desc: "Ataque de Arma Cuerpo a Cuerpo: +11 a impactar, alcance 10 pies, un objetivo. Impacto: 18 (2d10 + 7) de daño perforante más 9 (2d8) de daño necrótico. El objetivo debe superar una tirada de salvación de Constitución CD 19 o su máximo de puntos de golpe se reducirá en una cantidad igual al daño necrótico recibido. El dragón recupera puntos de golpe iguales a la mitad del daño necrótico infligido."
  - name: Garra
    desc: "Ataque de Arma Cuerpo a Cuerpo: +11 a impactar, alcance 5 pies, un objetivo. Impacto: 14 (2d6 + 7) de daño cortante."
  - name: Presencia Espectral
    desc: "Cada criatura a elección del dragón que esté a 120 pies de él debe superar una tirada de salvación de Sabiduría CD 17 o quedará asustada durante 1 minuto. Una criatura asustada se siente como si su fuerza vital estuviera siendo drenada."
  - name: Aliento de Sombras (Recarga 5-6)
    desc: "El dragón exhala una ráfaga de energía de sombras en un cono de 60 pies. Cada criatura en esa área debe realizar una tirada de salvación de Constitución CD 19, sufriendo 54 (12d8) de daño necrótico si falla la tirada, o la mitad si tiene éxito. Una criatura que falle la salvación no puede recuperar puntos de golpe hasta el final del próximo turno del dragón."
legendary_actions:
  - name: Paso Sombrío
    desc: "El dragón se teletransporta mágicamente, junto con cualquier equipo que lleve puesto o transporte, hasta 120 pies a un espacio desocupado que pueda ver que esté en penumbra u oscuridad."
  - name: Ataque de Cola
    desc: "El dragón realiza un ataque de cola. (Ataque de Arma Cuerpo a Cuerpo: +11 a impactar, alcance 15 pies, un objetivo. Impacto: 16 (2d8 + 7) de daño contundente)."
  - name: Drenar Alma (Cuesta 2 Acciones)
    desc: "El dragón se enfoca en una criatura asustada que pueda ver a 120 pies. El objetivo debe superar una tirada de salvación de Carisma CD 17 o recibirá 13 (3d8) de daño psíquico, y el dragón gana puntos de golpe temporales iguales a esa cantidad."
