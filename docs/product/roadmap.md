# Development Roadmap

## Phase 0 — Product and Simulation Design

Goal: establish the rules before implementation.

- define fictional league structure
- define team and roster data models
- define player attributes and archetypes
- define coaching and scheme model
- define chemistry/context model
- define possession-level simulation inputs and outputs
- define validation metrics

## Phase 1 — Core Domain Model

Goal: represent a complete league in code.

- league
- conference / division
- team
- player
- coach
- scheme
- contract
- roster
- depth chart
- schedule
- game / result

Deliverable: generate and serialize a fictional league with complete rosters.

## Phase 2 — Roster Management

Goal: make the GM role playable without game simulation.

- roster moves
- depth chart
- contracts
- trades
- free agency
- draft order
- prospect generation
- draft selection

Deliverable: complete an offseason and produce valid opening-day rosters.

## Phase 3 — Game Simulation

Goal: simulate believable games from team construction.

- effective player values
- unit strength calculations
- matchup model
- scheme fit
- coaching modifiers
- chemistry/context modifiers
- possession outcomes
- scoring
- basic statistics
- deterministic random seeds

Deliverable: simulate individual games and large batches of games.

## Phase 4 — Season Engine

Goal: run complete seasons.

- schedule execution
- standings
- tiebreaking rules
- playoffs
- injuries and recovery
- fatigue
- seasonal variance
- awards / leaderboards where useful

Deliverable: simulate a complete season and postseason automatically.

## Phase 5 — Franchise Progression

Goal: support multi-season play.

- player development
- aging and decline
- retirement
- contract expiration
- coaching changes
- team chemistry evolution
- offseason progression
- future draft classes

Deliverable: stable multi-season franchise simulation.

## Phase 6 — User Experience

Goal: make the simulation usable as a game.

- franchise dashboard
- roster and depth-chart screens
- player/coach detail screens
- transactions
- draft interface
- free-agency interface
- trade interface
- standings and schedule
- game simulation presentation
- save/load

## Phase 7 — Calibration and Balance

Goal: make results believable and management choices meaningful.

Use Monte Carlo simulation to calibrate:

- scoring distribution
- win probabilities
- home-field effect
- positional value
- scheme-fit effect
- coaching effect
- chemistry effect
- injury/depth value
- aging curves
- development curves
- parity across seasons

## Later Possibilities

- scouting uncertainty
- staff beyond coordinators
- owner expectations
- franchise finances
- relocation / expansion
- custom leagues
- mod/import support
- multiplayer
- play-level simulation
- historical league generation
- richer news/story systems