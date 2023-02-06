# data

#link to TidyTuesday repo: https://github.com/rfordatascience/tidytuesday/blob/master/data/2022/2022-05-17/readme.md"
#link to original pre-cleaned data: https://data.world/datagraver/eurovision-song-contest-scores-1975-2019 

### Data Dictionary

|variable       |class     | Description                                          |
|:--------------|:---------| :--------- |
|host_city      |character | Host city name, e.g. Helsinki                        |
|year           |integer   | Event year, e.g. 2007                                |
|host_country   |character | Host city country, e.g. Finland                      |
|artist_country |character | Participant country, e.g. Austria                    |
|running_order  |integer   | Running order for the teams |
|total_points   |integer   | Points                                               |
|rank           |integer   | Numeric rank, e.g. 2                                 |
|rank_ordinal   |character | Ordinal rank, e.g. 2nd                               |
|winner         |logical   | Was this team the grand champion |