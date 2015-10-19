# podcast_api_sinatra

A simple Sinatra server that returns a JSON object of podcast episodes, using the [Audiosear.ch Ruby SDK](https://github.com/popuparchive/audiosearch-client-ruby).

The server is [hosted on heroku](https://intense-forest-8107.herokuapp.com), and was built to work with the [rand(Cast) app](https://github.com/ShuflCast/randCast). It accepts the search params set with the app and returns a maximum of 300 podcast episodes from Audiosear.ch.
The lib/logic.rb file contains the sdk methods, which are documented [here](https://github.com/popuparchive/audiosearch-cookbook/wiki).
