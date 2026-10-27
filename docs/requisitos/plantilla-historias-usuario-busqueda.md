# Historias de usuario de búsqueda

| Campo | Valor |
| --- | --- |
| Proyecto | Proyecto Simbiosis |
| Fecha | [dd/mm/aaaa] |
| Versión | [Versión de trabajo] |
| Estado | Borrador |

## Fuentes comunes

- [Acta de UC-21 Buscar recetas](../captura/acta-acuerdos-uc-21-buscar-recetas.md), v1.1, Vigente.
- [Catálogo de requisitos](catalogo-requisitos.md), UR-08 y FR pertinentes.
- [Modelo de casos de uso](../modelos/modelo-casos-de-uso.md), UC-21.

## Épica de búsqueda

Como usuario registrado, quiero filtrar la búsqueda de recetas, para encontrar recetas acordes a las necesidades.

**Estado:** descompuesta en US-01, US-02 y US-03. Conserva la necesidad conjunta.

## Justificación de la división

Filtrar la búsqueda es muy amplio.

## US-01

**Título:** Buscar mediante una palabra o frase.

Como usuario registrado, quiero buscar recetas mediante una palabra o frase, para encontrar recetas acordes a mis necesidades.

**Fuentes:** UR-08; UC-21; [FR principal]; acta, [apartado pertinente].

### Criterios de aceptación

- **CA-01.** Dado un usuario registrado y recetas publicadas y validadas, cuando el usuario realiza una búsqueda mediante unas palabras o una frase y los filtros coincidan con una o más recetas, entonces el sistema debe de mostrar esa o esas recetas.
- **CA-02.** Dado un usuario registrado y recetas publicadas y validadas, cuando el usuario realiza una búsqueda mediante unas palabras o una frase y los filtros no coincidan con ninguna receta, entonces el sistema debe informar de que no hay recetas que cumplan los criterios.
- **CA-03.**  Dado un usuario registrado y recetas publicadas y validadas, cuando el usuario realiza una búsqueda mediante unas palabras o una frase, estos no coinciden con ninguna receta y el texto escrito pueda ser corregido ortográficamente, entonces el sistema propone aplicar dicha corrección.

## US-02

**Título:** Buscar por ingredientes incluidos.

Como usuario registrado, quiero filtrar las recetas por ingredientes, para encontrar recetas acordes a mis necesidades.

**Fuentes:** UR-08; UC-21; [FR principal]; acta, [apartado pertinente].

### Criterios de aceptación

- **CA-01.**  Dado un usuario registrado y una receta publicada y validada que contiene los ingredientes de la búsqueda, cuando el usuario selecciona los ingredientes de la búsqueda y la ejecuta, entonces el sistema muestra esa receta en los resultados.
- **CA-02.**  Dado un usuario registrado y ninguna receta publicada y validada que contenga los ingredientes de la búsqueda, cuando el usuario selecciona los ingredientes de la búsqueda y la ejecuta, entonces el sistema debe informar de que no hay recetas que cumplan los criterios.
- **CA-03.** Dado un usuario registrado y una receta publicada y validada que no contiene algunos de los ingredientes de la búsqueda, pero otros sí, cuando el usuario selecciona los ingredientes de la búsqueda y la ejecuta, entonces el sistema no debe mostrar dicha receta.
  
## US-03

**Título:** [Capacidad]

Como [rol], quiero [capacidad], para [beneficio].

**Fuentes:** UR-08; UC-21; [FR principal]; acta, [apartado pertinente].

### Criterios de aceptación

- **CA-01.** Dado [situación], cuando [acción], entonces [resultado observable].
- **CA-02.** Dado [situación], cuando [acción], entonces [resultado observable].
- **CA-03.** Dado [situación], cuando [acción], entonces [resultado observable].

## Revisión INVEST

La revisión abarca US-01, US-02 y US-03. «Aplicado» indica si se ha realizado la comprobación. «Cumple» indica si todas las historias cumplen el criterio. Si alguna no lo cumple, indicar «No» e identificar la historia y el motivo en la justificación. Si no se ha realizado la comprobación o faltan datos, indicar «Pendiente» en «Cumple».

| Criterio | Pregunta de revisión | Aplicado | Cumple | Justificación |
| --- | --- | --- | --- | --- |
| Independiente | ¿Puede implementarse cada historia y ofrecer un resultado útil sin implementar antes las otras historias del conjunto? Puede compartir infraestructura con ellas. | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Negociable | ¿Cada historia explica qué necesita la persona y deja margen para discutir los detalles de la solución, respetando los acuerdos confirmados? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Valiosa | ¿La parte «para…» de cada historia explica el beneficio que obtiene la persona al usar esa capacidad? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Estimable | ¿Están claros el alcance y los datos necesarios para estimar el trabajo de cada historia? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Pequeña | ¿Se centra cada historia en una única capacidad de alcance manejable? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Comprobable | ¿Los criterios de aceptación de cada historia describen acciones y resultados observables que permiten distinguir un comportamiento correcto de uno incorrecto? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |

## Dudas pendientes

[Cuestiones pendientes de aclaración. Si no quedan cuestiones, indicar «Ninguna».]
