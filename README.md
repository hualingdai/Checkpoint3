# Checkpoint3 
--Which songs have less than 2000  streams?
```SELECT trackname,
Streams
FROM datasets.spotify_worldwide_daily_song_ranking
WHERE streams< 2000
ORDER BY streams ASC
LIMIT 100
```
![Checkpoint3].(checkpoint1.jpg)
