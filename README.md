# LIRI-Bot

**LIRI is a Language Interpretation and Recognition Interface. LIRI will be a command line node app that takes in parameters and gives you back data. It is similar to SIRI but without voice recognition. The app will incorporate Spotify, Bands in Town, and OMDB API data to pull information about music, concerts, and movies.**

At the root of my project use npm install in order to use API data.
Use node commands to search databases:

* `node liri.js spotify-this-song` "song name"
* `node liri.js concert-this` "artist/band name"
* `node liri.js movie-this` "movie name"

_Below is a workflow of the app:_


 Go to the root of the app:
<img width="574" alt="screen shot 2018-12-13 at 2 03 07 pm" src="https://user-images.githubusercontent.com/39817046/50045677-d4e0bc00-005c-11e9-8fef-3d5e8aca43b5.png">

Install npm in command line:
<img width="571" alt="screen shot 2018-12-13 at 2 05 02 pm" src="https://user-images.githubusercontent.com/39817046/50045684-ef1a9a00-005c-11e9-9361-79fc88ea1df7.png">

<img width="572" alt="screen shot 2018-12-13 at 2 05 46 pm" src="https://user-images.githubusercontent.com/39817046/50045687-fd68b600-005c-11e9-9d47-ae45bd38dddb.png">

 Use `node liri.js spotify-this-song` "song name" for spotify information.
<img width="572" alt="screen shot 2018-12-13 at 2 07 02 pm" src="https://user-images.githubusercontent.com/39817046/50045689-078ab480-005d-11e9-84ca-c06ab480a48a.png">

 This returns artist name, song name, preview link, and album name.
<img width="572" alt="screen shot 2018-12-13 at 2 07 38 pm" src="https://user-images.githubusercontent.com/39817046/50045690-0fe2ef80-005d-11e9-8a1e-d3881d458b0e.png">

Use `node liri.js concert-this` "artist/band name" for bands in town information.
<img width="574" alt="screen shot 2018-12-13 at 2 16 03 pm" src="https://user-images.githubusercontent.com/39817046/50045699-2be69100-005d-11e9-9374-5b737a2ab593.png">

This returns name of the venue, venue location, date of the event (using moment to format date as "MM/DD/YYYY").
<img width="571" alt="screen shot 2018-12-13 at 2 17 00 pm" src="https://user-images.githubusercontent.com/39817046/50045700-2be69100-005d-11e9-809e-74869dc65aaa.png">

Use `node liri.js movie-this` "movie name" for movie information from OMDB.
<img width="573" alt="screen shot 2018-12-13 at 2 18 25 pm" src="https://user-images.githubusercontent.com/39817046/50045701-2be69100-005d-11e9-98b8-e9102e70e687.png">

This returns :
  * Title of the movie.
  * Year the movie came out.
  * IMDB Rating of the movie.
  * Rotten Tomatoes Rating of the movie.
  * Country where the movie was produced.
  * Language of the movie.
  * Plot of the movie.
  * Actors in the movie.
  
<img width="571" alt="screen shot 2018-12-13 at 2 18 51 pm" src="https://user-images.githubusercontent.com/39817046/50045702-2be69100-005d-11e9-9538-dc17281582b4.png">

<img width="572" alt="screen shot 2018-12-13 at 2 19 44 pm" src="https://user-images.githubusercontent.com/39817046/50045703-2be69100-005d-11e9-9ab9-91fd595d65db.png">

  Using 'node liri.js do-what-it-says' pulls this song title from a local random.txt file.
<img width="571" alt="screen shot 2018-12-13 at 2 20 24 pm" src="https://user-images.githubusercontent.com/39817046/50045704-2c7f2780-005d-11e9-9f6d-3444e900c3f6.png">
