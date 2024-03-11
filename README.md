# Data Engineer Demo

This project scrapes player and team data from basketball-reference.com and baseball-reference.com. The scraped data is then written to a MySQL database.

NBA game logs are scraped on a daily level while the MLB stats and records are brought in by season. The NBA data in manipulated in SQL to be aggregated to a season level.

Because game logs have team results, team results are aggregated by season. The top 8 seeds in each conference are then labeled as "Playoff Contenders" while the other teams are labeled as "Missed Playoffs". This however, does not account for any tie-breakers.
