# Processed Data 
This folder stores the cleaned, processed datasets saved as csv.

## Data Dictionary for (combined_games_processed)
| Column Name           | Type    | Description                                |
|-----------------------|---------|--------------------------------------------|
| `year`                | Numeric | The year the game was played               |
| `round_of`            | Numeric | The round in which the game was played     |
| `winning_team_name`  | Text    | Name of the team that won the game         |
| `winning_team_seed`  | Numeric | Seed of the winning team                   |
| `winning_team_score` | Numeric | Score of the winning team                  |
| `losing_team_name`   | Text    | Name of the team that lost the game        |
| `losing_team_seed`   | Numeric | Seed of the losing team                    |
| `losing_team_score`  | Numeric | Score of the losing team                   |

## Data Dictionary for (combined_upsets_processed)
| Column Name           | Type    | Description                                |
|-----------------------|---------|--------------------------------------------|
| `year`                | Numeric | The year the game was played               |
| `round_of`            | Numeric | The round in which the game was played     |
| `winning_team_name`  | Text    | Name of the team that won the game         |
| `winning_team_seed`  | Numeric | Seed of the winning team                   |
| `winning_team_score` | Numeric | Score of the winning team                  |
| `losing_team_name`   | Text    | Name of the team that lost the game        |
| `losing_team_seed`   | Numeric | Seed of the losing team                    |
| `losing_team_score`  | Numeric | Score of the losing team                   |

## Data Dictionary for (seeds__pct_records_processed)
| Column Name | Type    | Description                                      |
|-------------|---------|--------------------------------------------------|
| `SEED VS. SEED` | Text    | Seed matchups (e.g., 1 vs. 16)                    |
| `W-L`           | Numeric | Win-loss record for the matchup                  |
| `PCT.`          | Numeric | Win-loss percentage for the matchup              |
| `Seed_1`        | Numeric | First seed in the matchup                        |
| `Seed_2`        | Numeric | Second seed in the matchup                       |
| `Wins`          | Numeric | Number of wins for `Seed_1` against `Seed_2`     |
| `Losses`        | Numeric | Number of losses for `Seed_1` against `Seed_2`   |

## Data Dictionary for (seeds_records_processed) 
| Column Name         | Type    | Description                                              |
|---------------------|---------|----------------------------------------------------------|
| `SEED`              | Text    | Seed number (1–16)                                       |
| `OVERALL RECORD`    | Text    | Overall win-loss record for the seed                    |
| `BEST FINISH`       | Text    | Best finish achieved by the seed and how many times     |
| `WINS`              | Numeric | Total number of wins for the seed                       |
| `LOSSES`            | Numeric | Total number of losses for the seed                     |
| `BEST FINISH TYPE`  | Text    | The type of best finish (e.g., Champion, Final Four)     |
| `BEST FINISH COUNT` | Numeric | Number of times that best finish was achieved           |
