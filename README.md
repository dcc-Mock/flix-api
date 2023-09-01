# Flix API

This repository contains static JSON data that's served up through My JSON Server as a read-only REST API. 

db.json holds an object with a movies property, containing an array of movie objects. This "movies" property becomes a GET endpoint via My JSON Server.

## /movies
These endpoints contains an array of supplemental data for the Movies API, used in the React tutorial series.

### Collection

**GET**: `my-json-server.typicode.com/dCC-Mock/flix-api/movies`
```
[
  {
      "id": "The Dark Knight",
      "poster_url": "https://image.tmdb.org/t/p/w500/1hRoyzDtpgMU7Dz4JF22RANzQO7.jpg",
      "release_date": "2008-07-18"
  },
  {
      "id": "Inception",
      "poster_url": "https://image.tmdb.org/t/p/w500/9gk7adHYeDvHkCSEqAvQNLV5Uge.jpg",
      "release_date": "2010-07-16"
  }
  ...
]
```

### Detail
**GET**: `my-json-server.typicode.com/dCC-Mock/flix-api/movies/The Dark Knight`
```
{
  "id": "The Dark Knight",
  "poster_url": "https://image.tmdb.org/t/p/w500/1hRoyzDtpgMU7Dz4JF22RANzQO7.jpg",
  "release_date": "2008-07-18"
}
```

The movies endpoint contains the following movies:
- The Dark Knight
- Inception
- Interstellar
- The Shawshank Redemption
- The Godfather
- The Matrix
- Avatar
- Titanic
- The Avengers
- The Terminator
- Star Wars: A New Hope
- Jaws
- Fight Club
- Schindler's List
