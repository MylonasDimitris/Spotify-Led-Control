# Controls led strips depending on the currently playing song on spotify

A Python server is running on the PC which extracts the name of the
currently playing song from the active spotify window. Through spotify's
API, it then downloads the song's cover, analyzes the most occured colors 
and then send them through serial communication to an arduino. Then with a
costume made led controller the arduino passes the given colors to the strip.
