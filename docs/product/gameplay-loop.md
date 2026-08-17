# Gameplay Loop

## Franchise Loop

The game alternates between roster-building decisions and simulated football outcomes.

```text
Evaluate Team
    ↓
Set Strategy
    ↓
Acquire / Release / Develop Talent
    ↓
Set Depth Chart + Scheme
    ↓
Simulate Games
    ↓
Review Results + Injuries + Development
    ↓
Adjust
    ↓
Complete Season
    ↓
Offseason
    ↓
Draft / Free Agency / Trades / Coaching
    ↓
Next Season
```

## Weekly Loop

Before each game the GM reviews:

- injuries and fatigue
- depth chart
- opponent strengths and weaknesses
- offensive and defensive scheme fit
- recent player performance
- chemistry and morale indicators
- home/away context and environmental effects

The GM can adjust personnel and strategic emphasis, but the head coach and coordinators determine much of the tactical execution.

## Seasonal Loop

During the season:

- simulate weekly games
- manage injuries and roster replacements
- evaluate trade opportunities
- monitor player development and regression
- track team chemistry and coaching performance
- manage playoff positioning and roster priorities

## Offseason Loop

The offseason is the primary team-building phase:

1. review season performance
2. evaluate coaches and staff
3. process retirements and aging
4. manage expiring contracts
5. conduct free agency
6. scout and conduct the draft
7. make trades
8. assign roster roles and depth chart
9. establish schemes
10. begin preseason / next season

## Decision Tension

The game should repeatedly force tradeoffs between:

- current talent vs future assets
- star power vs roster depth
- raw talent vs scheme fit
- continuity vs roster churn
- veteran stability vs young upside
- expensive certainty vs inexpensive development
- coach continuity vs system change
- short-term contention vs long-term cap flexibility

## Information Model

Not every rating must be perfectly known. Scouting accuracy can eventually create uncertainty around prospects and unfamiliar players. The first implementation may expose exact ratings to simplify validation, then introduce scouting uncertainty after the simulation engine is stable.