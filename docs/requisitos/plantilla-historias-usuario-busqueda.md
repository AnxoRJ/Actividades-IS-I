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

Como paciente, quiero buscar recetas aplicando filtros en la búsqueda, visualizar los resultados y organizarlos, para obtener una receta adecuada.

**Estado:** descompuesta en US-01, US-02 y US-03. Conserva la necesidad conjunta.

## Justificación de la división

[Justificación de los resultados útiles que separa la división.]

## US-01

**Título:** Búsqueda mediante palabra clave.

Como paciente, quiero buscar recetas mediante palabras clave o frases, para obtener una receta adecuada.

**Fuentes:** UR-08; UC-21; FR-085; acta, [apartado pertinente].

### Criterios de aceptación

- **CA-01.** Dado que introduzco una palabra clave, cuando realizo la búsqueda, entonces obtengo recetas que incluyen dicha palabra.
- **CA-02.** Dado que introduzco una palabra clave y no existe ninguna receta con dicha palabra, cuando realizo la búsqueda, entonces recibo un mensaje avisando de que no hay ninguna receta con dicha palabra.
- **CA-03.** Dado [situación], cuando [acción], entonces [resultado observable].

## US-02

**Título:** Excluir ingredientes.

Como paciente, quiero excluir ingredientes, para obtener recetas que no contengan dicho ingrediente.

**Fuentes:** UR-08; UC-21; [FR]; acta, [apartado pertinente].

### Criterios de aceptación

- **CA-01.** Dado que he excluido un ingrediente, cuando realizo una búsqueda, entonces obtengo las recetas que no contienen dicho ingrediente.
- **CA-02.** Dado [situación], cuando [acción], entonces [resultado observable].
- **CA-03.** Dado [situación], cuando [acción], entonces [resultado observable].

## US-03

**Título:** Búsqueda por idioma.

Como paciente, quiero realizar una búsqueda por idiomas de receta, para obtener una receta en mi idioma.

**Fuentes:** UR-08; UC-21; FR-003; acta, [apartado pertinente].

### Criterios de aceptación

- **CA-01.** Dado que introduzco un idioma, cuando realizo la búsqueda, entonces obtengo recetas solo en el idioma indicado.
- **CA-02.** Dado que introduzco un idioma y no existen retas en ese idioma, cuando realizo la búsqueda, entonces recibo un mensaje de que no hay ninguna receta en dicho idioma..
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
