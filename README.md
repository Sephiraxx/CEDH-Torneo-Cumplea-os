# Birthday cEDH Gauntlet

Proyecto de ocho mazos de **Commander competitivo** preparado para un torneo de cumpleaños con ocho jugadores.

En cada ronda se forman dos pods aleatorios de cuatro jugadores. Los mazos también se asignan al azar, llevando un registro de qué listas utilizó cada participante para intentar evitar repeticiones. Todos los mazos se entregan enfundados, con sus tokens, fichas, contadores y ayudas necesarias.

## Objetivo

La intención es mostrar distintas facetas de cEDH sin que los ocho mazos sean copias del mismo shell:

- Turbo-combo.
- Midrange interactivo.
- Storm.
- Combo de maná.
- Toolbox de artefactos.
- Tempo.
- Combo de criaturas.
- Estrategias centradas en el comandante.

Los mazos no tienen exactamente la misma velocidad de goldfish, pero todos están diseñados para competir en el mismo entorno.

## Mazos incluidos

| Mazo | Arquetipo | Dificultad | Guía | Moxfield |
|---|---|---:|---|---|
| **RogSi — Rograkh / Silas Renn** | Turbo-combo Grixis | Alta | [Abrir guía](mazos-y-guias/rogsi/) | [Moxfield](https://moxfield.com/decks/IXsn3AhZFUyHU1_cYdQIdQ) |
| **Blue Farm — Tymna / Kraum** | Midrange-combo de cuatro colores | Media–Alta | [Abrir guía](mazos-y-guias/blue-farm/) | [Moxfield](https://moxfield.com/decks/8g1Q0BFzQ0K8YbJ59cun2w) |
| **Kinnan, Bonder Prodigy** | Combo de maná Simic | Media | [Abrir guía](mazos-y-guias/kinnan/) | [Moxfield](https://moxfield.com/decks/Z3gmXrW1Q0qzAhU8lrpNvw) |
| **Magda, Brazen Outlaw** | Toolbox-combo mono rojo | Media–Alta | [Abrir guía](mazos-y-guias/magda/) | [Moxfield](https://moxfield.com/decks/TNB0MbjVWEGxmKPHl2YnEQ) |
| **Kefka, Court Mage // Kefka, Ruler of Ruin** | Midrange-combo Grixis | Media–Alta | [Abrir guía](mazos-y-guias/kefka/) | [Moxfield](https://moxfield.com/decks/ZAx-l28TG0aY1oTpYEjR1g) |
| **Ral, Monsoon Mage // Ral, Leyline Prodigy** | Turbo storm Izzet | Alta | [Abrir guía](mazos-y-guias/ral/) | [Moxfield](https://moxfield.com/decks/0dQxwvhR00KGIsQ_zKlYDQ) |
| **Yuriko, the Tiger's Shadow** | Tempo-combo Dimir | Media | [Abrir guía](mazos-y-guias/yuriko/) | [Moxfield](https://moxfield.com/decks/HOAzAjkpq0K-iEEAqnqgnA) |
| **Etali, Primal Conqueror // Etali, Primal Sickness** | Turbo creature-combo Gruul | Media | [Abrir guía](mazos-y-guias/etali/) | [Moxfield](https://moxfield.com/decks/hf8QLb7w80WGrlmPPFqDcA) |

## Filosofía de balance

- **RogSi y Ral** representan los mazos turbo y presentan los intentos más tempranos.
- **Blue Farm, Kefka y Yuriko** compiten mediante interacción, selección y resiliencia.
- **Kinnan, Magda y Etali** aprovechan motores centrados en permanentes y en el comandante.
- La diferencia buscada está en el estilo de juego, no en separar los mazos por niveles de poder.

## Formato del evento

- Dos pods aleatorios de cuatro jugadores en cada ronda.
- Pods sorteados nuevamente en cada ronda.
- Mazos asignados de manera aleatoria.
- Tracking individual para intentar evitar que un jugador repita mazo.
- Mazos entregados ya enfundados.
- Tokens, fichas, contadores y ayudas incluidos con cada lista.
- Guías disponibles para consulta durante la partida.
- Tiempo previo para leer mulligans, líneas principales y errores frecuentes.

## Contenido del repositorio

```text
README.md
index.md
_config.yml
assets/
└── css/
    └── style.scss

mazos-y-guias/
├── index.md
├── 00_README_ES.md
├── 00_All_8_Moxfield_Imports.txt
├── 01_..._Guia_de_Piloto.md
├── 01_..._Moxfield.txt
└── ...
```

Cada mazo incluye:

- Guía de piloto en español.
- Plan principal y secundario.
- Mulligan recomendado.
- Líneas de combo.
- Prioridades de tutor.
- Errores frecuentes.
- Lista completa de 100 cartas.
- Enlace a Moxfield.
- Respaldo `.txt` para importar.

## GitHub Pages

La portada del sitio se genera desde [`index.md`](index.md).

Las instrucciones de publicación están separadas en:

[`PUBLICAR_EN_GITHUB_PAGES.md`](PUBLICAR_EN_GITHUB_PAGES.md)

## Ajustes especiales

- **Ral:** se eliminó `_____ Goblin` y se reemplazó por **Baral, Chief of Compliance**.
- **Etali:** se eliminó `_____ Goblin` y se reemplazó por **Generator Servant**.
- Las cartas y secciones de stickers fueron retiradas por completo.

## Uso de las guías

Las guías pueden consultarse durante la partida. El objetivo es evaluar timing, amenazas, interacción y navegación de la pila, no memorizar una lista ajena de cien cartas.
