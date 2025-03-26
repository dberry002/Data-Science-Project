## 📊 Codebook

This codebook describes the variables used in this project, including those created or derived during the analysis.

| Variable Name    | Description                          | Type    | Possible Values/Units |
|-----------------|--------------------------------------|---------|---------------------|
| `Pos`           | Team's position in the league table  | Integer | 1 to 20             |
| `Team`          | Name of the Premier League team      | String  | Team names          |
| `M`             | Total matches played                 | Integer | 0 to 38             |
| `W`             | Number of matches won                | Integer | 0 to 38             |
| `D`             | Number of matches drawn              | Integer | 0 to 38             |
| `L`             | Number of matches lost               | Integer | 0 to 38             |
| `GF`            | Goals scored (Goals For)             | Integer | 0+                  |
| `GA`            | Goals conceded (Goals Against)       | Integer | 0+                  |
| `Dif`           | Goal difference (GF - GA)            | Integer | Positive/negative   |
| `Points`        | Total points so far                  | Integer | 0 to 114            |
| `GPM`           | Goals per match                      | Float   | 0+                  |
| `GAPM`          | Goals conceded per match             | Float   | 0+                  |
