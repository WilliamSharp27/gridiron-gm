# Player Model

## Principles

Players should be modeled with position-specific attributes, developmental traits, contract state, health, personality, and role fit. A single overall rating may be displayed later for usability, but it should be derived rather than drive the simulation directly.

## Common Player Fields

Every player should have:

- player ID
- name
- age
- position
- experience
- physical attributes
- technical attributes
- mental attributes
- durability
- current health
- fatigue
- development potential
- development curve / archetype
- personality traits
- leadership
- scheme preferences / archetype fit
- contract terms
- roster status and role

## Example Position Models

### Quarterback

- arm strength
- short accuracy
- intermediate accuracy
- deep accuracy
- processing
- decision making
- pocket presence
- mobility
- pressure response
- ball security
- leadership
- durability

### Wide Receiver

- speed
- acceleration
- route running by route family
- release
- separation
- catching
- contested catching
- yards-after-catch ability
- blocking
- awareness
- durability

### Offensive Line

- pass protection
- run blocking
- power
- movement ability
- awareness
- communication
- discipline
- versatility
- durability

### Defensive Front

- pass rush
- power
- speed
- run defense
- gap discipline
- pursuit
- tackling
- block shedding
- awareness
- durability

### Defensive Back

- man coverage
- zone coverage
- press ability
- speed
- acceleration
- ball skills
- tackling
- awareness
- route recognition
- durability

## Archetypes

A position can contain multiple archetypes. Examples:

- QB: pocket distributor, vertical passer, dual-threat, timing passer
- RB: power, elusive, receiving, balanced
- WR: vertical threat, possession, route technician, slot creator
- OL: power, zone/movement, balanced
- EDGE: speed rusher, power rusher, edge setter
- CB: man specialist, zone specialist, press corner

Archetypes should help determine scheme fit without hard-locking players into one system.

## Development and Aging

Development should depend on:

- age
- potential
- playing time
- coaching quality
- role stability
- injuries
- work ethic / developmental traits
- random variation

Different attributes should peak and decline at different rates. Physical traits may decline before mental or technical traits.

## Hidden Information

In later versions, true player ability and potential can differ from the GM's scouting estimate. Early development should use known values to make simulation testing easier.