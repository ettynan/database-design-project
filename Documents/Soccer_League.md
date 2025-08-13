# IT125 Soccer League Database
## Overview
This database tracks a local adult soccer league
### Players
 1. register individually
 2. join teams
 3. play weekly matches across multiple seasons

### Each player
1. is tied to one team
2. must pay dues each season to participate

## Design Summary
The design includes tables for *Players, Teams, Matches, Payments, Referees, and Seasons*. 
- The Season table after realizing dues are paid per season, and matches must be grouped by season as well. 
- A challenge was figuring out how to track payments when players haven’t paid the full amount yet, while still keeping their team info accurate. 
- Another design decision was removing “home” and “away” teams since all games are held at neutral locations. 
- The EER diagram defines foreign keys, one-to-many relationships, and nullable fields such as scores for unplayed matches. 

This structure makes it easier to manage match scheduling, team rosters, referee assignments, and seasonal payments in one place. 
