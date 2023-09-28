# league-counter
Skill Test:
League Table
The LeagueTable class tracks the score of each player in a league. After each game, the player records their score with the record_result function.

The player's rank in the league is calculated using the following logic:
1. The player with the highest score is ranked first (rank 1).
     The player with the lowest rank is ranked last.
2. If two players are tied on score, then the player who has played the fewest games is ranked higher.
3. If two players are tied on score and number of games played, then the player who was first in the list of players is ranked higher.

Implement the player_rank function that returns the player at the given rank.
