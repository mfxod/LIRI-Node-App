# LIRI-Node-App
A command line node app that queries APIs to return data to the user. Users provide one of four standard commands plus their own input depending on the command. 

### APIs used:
* Spotify
* Bands in Town
* OMDB
  
### NPM packages used:
* FS
* Axios
* Node-Spotify-API
* Moment
* DotEnv

### Commands available:
* `concert-this` takes an artist/band name, searches the Bands in Town Artist Events API and returns venue name, venue location and event date
* `spotify-this-song` takes a song name, searches the Spotify API and returns the artist, song name, a preview link and the album
* `movie-this` takes a movie name, searches the OMDB API and returns title, year, IMDB rating, Rotten Tomatoes rating, country where produced, language, plot and actors
* `do-what-it-says` uses the text inside the random.txt file to supply the command and user input to run one of the three commands above

Include screenshots, gifs or videos of the app functioning


