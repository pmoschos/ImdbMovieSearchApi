# ImdbMovieSearchApi

This is an app witch implements an API from https://www.imdb.com/ and allows users to **search using movie title**.

It represents into **RecyclerView** using **CardView** all the movies the IMDB API (https://imdb-api.com/) returns!

Attention!
Inside the MainActivity at line 65: String url = "https://imdb-api.com/en/API/SearchMovie/YOUR_KEY_VALUE/" + editText.getText().toString().trim(); 

repclace the YOUR_KEY_VALUE with your API_JKEY after you complete the registration in (https://imdb-api.com/).

Each item in CardView containts:
- movie title
- movie image
- movie short details

![image](https://github.com/pmoschos/ImdbMovieSearchApi/assets/133533759/0f009dd0-d75f-4096-8807-3969637722c8)
