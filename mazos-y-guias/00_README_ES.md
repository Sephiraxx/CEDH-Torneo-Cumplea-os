# Birthday cEDH Gauntlet — Paquete de ocho mazos

Este paquete contiene ocho mazos completos de cEDH, sin límite de presupuesto y de 100 cartas, preparados para ser intercambiados entre jugadores durante el evento.

Las listas fueron construidas para representar distintos estilos competitivos, mantener planes de victoria coherentes y permitir que los jugadores puedan rotar entre mazos sin necesidad de conocerlos de memoria.

## Filosofía de balance

- **RogSi y Ral** son los verdaderos mazos turbo. Presentan los intentos de victoria más tempranos y explosivos, pero castigan mucho una mala secuencia y suelen recuperarse peor después de un intento fallido.
- **Kinnan, Magda, Najeela y Etali** son mazos proactivos centrados en su comandante. Pueden amenazar victorias rápidas mientras mantienen un plan visible sobre la mesa.
- **Tymna/Kraum y Yuriko** son los mazos interactivos y resilientes. Ceden parte de la velocidad inicial a cambio de ventaja de cartas, interacción gratuita y mejor capacidad de reconstrucción.
- Tener un nivel similar **no significa ganar en el mismo turno de goldfish**. Cada mazo busca competir por la victoria desde un eje estratégico diferente.

## Mazos incluidos

| Mazo | Rol | Dificultad de pilotaje | Final principal |
|---|---|---|---|
| RogSi — Rograkh / Silas Renn | Referencia de turbo-combo Grixis | Alta | Underworld Breach + Lion's Eye Diamond + Brain Freeze |
| Blue Farm — Tymna / Kraum | Midrange-combo de cuatro colores | Media–Alta | Thassa's Oracle + Demonic Consultation o Tainted Pact |
| Kinnan, Bonder Prodigy | Combo de maná Simic | Media | Kinnan + Basalt Monolith para generar maná incoloro infinito |
| Magda, Brazen Outlaw | Toolbox-combo mono rojo de artefactos | Media–Alta | Magda + Clock of Omens + un Enano artefacto, finalizando con Grinding Station |
| Najeela, the Blade-Blossom | Combat-combo de cinco colores | Media | Najeela + Derevi, Empyrial Tactician para generar pasos de combate repetidos |
| Ral, Monsoon Mage | Turbo storm Izzet | Alta | Underworld Breach + Lion's Eye Diamond + Brain Freeze |
| Yuriko, the Tiger's Shadow | Tempo-combo Dimir | Media | Thassa's Oracle + Demonic Consultation o Tainted Pact |
| Etali, Primal Conqueror | Turbo creature-combo Gruul | Media | Dualcaster Mage + Twinflame, Heat Shimmer, Molten Duplication o Electroduplicate |

## Validación inicial

- Cada lista contiene exactamente 100 cartas, incluyendo su comandante o pareja de comandantes.
- Se comprobó la regla singleton, permitiendo la repetición de tierras básicas.
- No se incluyeron cartas que aparecían prohibidas en Commander al momento de construir las listas.
- Los mazos que utilizan Tainted Pact mantienen nombres de tierras únicos para no interrumpir la línea.

> La lista de cartas prohibidas puede cambiar. Conviene revisarla nuevamente antes del evento.

## Formato del evento

- En cada ronda se forman **dos pods aleatorios de cuatro jugadores**.
- Los pods se vuelven a sortear en cada ronda.
- Los mazos también se asignan de forma aleatoria.
- Se lleva un registro de qué mazos utilizó cada jugador para intentar evitar repeticiones.
- Si una asignación repite un mazo que el jugador ya utilizó y existen alternativas disponibles, ese mazo se vuelve a sortear.
- Todos los mazos se entregan ya enfundados y acompañados por sus respectivos tokens, fichas, contadores y ayudas de memoria.
- La guía de piloto correspondiente permanece junto a cada mazo y puede consultarse durante la partida.
- Antes de comenzar, cada jugador dispone de unos minutos para revisar el mulligan, las líneas principales y los errores frecuentes del mazo asignado.

El desafío debería ser **decidir cuándo actuar, evaluar amenazas y navegar la pila**, no memorizar una lista prestada de cien cartas.

## Archivos incluidos

Cada mazo cuenta con:

- Una lista en texto plano lista para importar en Moxfield.
- Una guía de piloto en español.
- Indicaciones de mulligan.
- Plan principal y plan secundario.
- Líneas de combo.
- Prioridades de tutor.
- Errores frecuentes.
- Lista completa categorizada.

El paquete también incluye un archivo combinado con las ocho listas y un README general para el repositorio.

## Uso recomendado de las guías

- La guía puede consultarse durante la partida.
- Los jugadores pueden revisar la lista completa antes de hacer mulligan.
- Las líneas de combo pueden verificarse mientras se juega.
- El propietario del conjunto puede aclarar reglas, pero no tomar decisiones estratégicas por el piloto.
- Conviene anotar el maná flotante, la cantidad de hechizos lanzados durante el turno y las repeticiones de loops.
- En loops deterministas, el jugador puede declarar una cantidad de repeticiones una vez demostrado correctamente el ciclo.
