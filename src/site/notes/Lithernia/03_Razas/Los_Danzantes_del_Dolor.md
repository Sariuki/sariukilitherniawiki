---
{"dg-publish":true,"permalink":"/lithernia/03-razas/los-danzantes-del-dolor/","title":"Los danzantes del dolor","tags":["lithernia","criatura"]}
---

# Los danzantes del dolor

### Tabla de Identificación

| Atributo | Descripción |
| :--- | :--- |
| **Tipo de Criatura** | Humanoide (Hobgoblin) |
| **Alineamiento Típico** | Legal Maligno |
| **Deidad Patrona** | [[Lithernia/09_Personajes/01_Dioses/Kromagul\|Kromagul]], Dios del Dolor |
| **Facción Principal** | Clan [[Lithernia/09_Personajes/01_Dioses/Kromagul\|Kromagul]] |
| **Nivel de Desafío** | 3 |
| **Rol Táctico** | Escaramuzador, Debilitador |
| **Entorno Común** | Zonas de tortura, campos de batalla, guarniciones en Fuempillos, ruinas de [[Lithernia/02_Reinos/Mor'dhul\|Mor'dhul]]. |

### Tabla de Conocimiento (Prueba de Habilidad)

| CD | Habilidad | Conocimiento Revelado |
| :--- | :--- | :--- |
| **10** | Historia | Identifica a la criatura como un hobgoblin de una secta militar de [[Lithernia/02_Reinos/Mor'dhul\|Mor'dhul]], conocida por su disciplina y crueldad táctica. |
| **15** | Religión o Arcanos | Los vincula al culto de [[Lithernia/09_Personajes/01_Dioses/Kromagul\|Kromagul]]. Sabe que canalizan el dolor (propio y ajeno) en poder. Conoce el efecto de su `Aura de Sufrimiento` y su rasgo `Danza de la Agonía`. |
| **20** | Investigación o Religión | Conoce sus tácticas precisas: se exponen al daño deliberadamente para activar su `Danza de la Agonía` y usan `Ventaja Marcial` para eliminar objetivos clave. Entiende que `Susurros de Tormento` busca romper formaciones. |

### Tácticas y Comportamiento

| Estrategia | Descripción |
| :--- | :--- |
| **Prioridad de Objetivo** | Aislan a un único enemigo para maximizar el efecto de `Ventaja Marcial`. Se centran en personajes con baja salvación de Sabiduría. |
| **Apertura de Combate** | Usan `Susurros de Tormento` si el grupo enemigo está agrupado para desorganizarlo. |
| **Posicionamiento** | Se mantienen cerca de sus aliados para activar `Ventaja Marcial`. No temen recibir un golpe si eso activa su `Danza de la Agonía`. |
| **Sinergias** | Trabajan en grupos de 3 o más. Su `Aura de Sufrimiento` y la habilidad de `Ventaja Marcial` se potencian mutuamente. Son escoltas perfectos para brutos más grandes como los Semiogros. |
| **Debilidades** | Dependen de sus aliados para `Ventaja Marcial`. El daño que los elimina en un solo golpe (one-shot) evita que activen su `Danza de la Agonía`. |

### Ganchos de Encuentro

| d6 | Situación del Encuentro |
|:--:|---|
| **1** | Un grupo de 3 Danzantes "entrena" torturando a un prisionero en un sótano abandonado. |
| **2** | Actúan como guardia de élite para un [[Lithernia/04_Clases/Sacerdote\|Sacerdote]] de alto rango del Clan [[Lithernia/09_Personajes/01_Dioses/Kromagul\|Kromagul]]. |
| **3** | Una patrulla de Danzantes busca supervivientes en un campo de batalla reciente para prolongar su agonía. |
| **4** | Lideran una banda de [[Lithernia/03_Razas/Goblins\|Goblins]] en una incursión para capturar nuevos "sujetos de prueba". |
| **5** | Realizan una danza ritual en la ciudad de Fuempillos, infligiendo dolor a la multitud para invocar el favor de su dios. |
| **6** | Un Danzante solitario, y malherido, ofrece información a cambio de una "muerte digna en combate". |

### Tesoro y Recolección

| Componente | CD de Recolección | Usos Potenciales |
| :--- | :--- | :--- |
| **Hojas Dentadas** | — | Un par de dagas o espadas cortas de diseño cruel. Funcionan como armas marciales. |
| **Símbolo de [[Lithernia/09_Personajes/01_Dioses/Kromagul\|Kromagul]]** | 10 (Religión) | Un amuleto de hierro retorcido. Componente para rituales que buscan infligir o resistir el dolor. |
| **Corazón Afligido** | 18 (Arcanos) | Ingrediente para pociones que infligen daño psíquico o para fabricar un pergamino de conjuro de *Miedo*. |

---
```statblock
name: Danzante del Dolor
size: Mediano
type: humanoide (hobgoblin)
alignment: legal maligno
ac: 15 (armadura de cuero tachonado)
hp: 52 (8d8 + 16)
speed: 30 ft.
stats: [14, 16, 14, 12, 12, 13]
saves:
  - Dex: +5
  - Con: +4
skills:
  - Acrobacias: +5
  - Intimidación: +3
  - Actuación: +3
senses: Visión en la oscuridad 60 ft., Percepción pasiva 11
languages: Común, Goblin
cr: 3
traits:
  - name: Aura de Sufrimiento
    desc: "Cualquier criatura hostil que comience su turno a 10 pies del danzante debe superar una tirada de salvación de Sabiduría CD 12 o tendrá desventaja en sus tiradas de ataque hasta el comienzo de su próximo turno."
  - name: Danza de la Agonía
    desc: "Cuando el danzante recibe daño de un ataque, sus ataques con arma infligen 3 (1d6) de daño psíquico adicional hasta el final de su siguiente turno."
  - name: Ventaja Marcial
    desc: "Una vez por turno, el danzante puede infligir 7 (2d6) de daño adicional a una criatura que golpee con un ataque de arma si esa criatura está a 5 pies de un aliado del danzante que no esté incapacitado."
actions:
  - name: Multiataque
    desc: "El danzante realiza dos ataques con sus Hojas Dentadas."
  - name: Hoja Dentada
    desc: "Ataque de arma cuerpo a cuerpo: +5 a impactar, alcance 5 ft., un objetivo. Impacto: 7 (1d8 + 3) de daño cortante."
  - name: Susurros de Tormento (Recarga 5-6)
    desc: "El danzante emite encantamientos enloquecedores. Cada criatura a su elección en un radio de 30 pies que pueda oírlo debe realizar una tirada de salvación de Sabiduría CD 12. Si falla, una criatura recibe 10 (3d6) de daño psíquico y debe usar su reacción, si está disponible, para moverse hasta su velocidad en una dirección aleatoria determinada por el DM. Si tiene éxito, la criatura recibe la mitad del daño y no tiene que moverse."
