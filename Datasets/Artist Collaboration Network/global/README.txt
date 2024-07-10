
+-------------------------------------------------+
|    Artist Collaboration Network - Global  	  |
+-------------------------------------------------+

The networks of collaborating artists obtained from Spotify Charts for each considered market and year. Artists are linked when they collaborate on a hit song (i.e. this song appears on a Spotify Top 200 Chart). As genres are linked to artists, these networks are used as an intermediate step to generate the final Genre Collaboration Networks. 

+-----------------------------------------------------------------------------------+

╔══════════════════════════════════════════════════════════════════════════════════╗
║                                       FILES                                      ║
╠════════════════════════════╦═════════════════════════════════════════════════════╣
║ au-artist_network-2017.csv ║ Artist Network (edge list) for all markets in 2017. ║
╠════════════════════════════╬═════════════════════════════════════════════════════╣
║ au-artist_network-2018.csv ║ Artist Network (edge list) for all markets in 2018. ║
╠════════════════════════════╬═════════════════════════════════════════════════════╣
║ au-artist_network-2019.csv ║ Artist Network (edge list) for all markets in 2019. ║
╚════════════════════════════╩═════════════════════════════════════════════════════╝

+-----------------------------------------------------------------------------------+

╔════════════════════════════════════════════════════════════════════╗
║                         DATASET DESCRIPTION                        ║
╠══════════╦═════════════════════════════════════════════════════════╣
║ artist_1 ║                       Artist name.                      ║
╠══════════╬═════════════════════════════════════════════════════════╣
║ artist_2 ║                       Artist name.                      ║
╠══════════╬═════════════════════════════════════════════════════════╣
║   count  ║ Number of hit songs in which both artists collaborated. ║
╠══════════╬═════════════════════════════════════════════════════════╣
║ song_ids ║  Spotify ID for each hit song containing both artists.  ║
╚══════════╩═════════════════════════════════════════════════════════╝