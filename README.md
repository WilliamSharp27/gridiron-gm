# Gridiron GM

Gridiron GM is a professional-football franchise management and simulation game. The player acts as a general manager responsible for building and sustaining a championship roster through the draft, free agency, trades, contracts, coaching decisions, and long-term roster planning.

The game is designed around one central idea:

> The best roster is not necessarily the team with the highest-rated players. The best team is the organization whose talent, scheme, coaching, chemistry, depth, and circumstances combine most effectively.

## Core Gameplay

The GM manages:

- roster construction and depth charts
- amateur draft strategy
- free agency
- player trades
- contracts and salary constraints
- coaching hires and scheme selection
- player development and aging
- team chemistry and roster continuity
- injuries, fatigue, and seasonal effects
- multi-season franchise strategy

Games and seasons are simulated from the interaction of player talent, positional matchups, scheme fit, coaching quality, chemistry, roster depth, injuries and fatigue, environmental effects, home-field advantage, and controlled randomness.

## Product Direction

The initial release will use a fictional professional football league, fictional teams, stadiums, coaches, and players. Real geographic locations may be used where appropriate, but the project should not depend on NFL club names, logos, uniforms, stadium branding, or proprietary player data.

The first simulation target is possession-level game simulation. This provides enough football structure to generate meaningful scores and statistics without requiring a full play-by-play physics engine. The model can later evolve toward drive-level and play-level simulation.

## Repository Structure

```text
docs/
  product/
    game-concept.md
    gameplay-loop.md
    roadmap.md
  simulation/
    simulation-model.md
    player-model.md
    coaching-and-scheme-model.md
    chemistry-and-context.md
  league/
    league-design.md
    fictional-content-policy.md
src/
data/
tests/
```

Folders such as `src/`, `data/`, and `tests/` will be added as implementation begins; Git does not track empty directories.

## Initial Development Phases

1. Define the league and franchise data model.
2. Define player, coach, scheme, chemistry, and team-strength models.
3. Build roster management: depth chart, transactions, contracts, draft, free agency, and trades.
4. Build the game simulation engine.
5. Add season scheduling, standings, playoffs, player development, aging, injuries, and offseason progression.
6. Build the user interface and persistence layer.
7. Balance and validate simulation outcomes across large Monte Carlo runs.

## Design Principles

- Football outcomes should emerge from interacting systems rather than a single overall rating.
- Scheme fit should materially change player and team performance.
- Coaching should influence development, tactical efficiency, culture, and adaptability.
- Chemistry should reward continuity and coherent roster construction without overwhelming talent.
- Randomness should create uncertainty without making roster-building decisions irrelevant.
- Every major simulation modifier should be explainable and testable.
- Game balance should be driven by simulation evidence rather than intuition alone.

## Status

Pre-development: product and simulation design.