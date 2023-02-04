# GO Movies CRUD

I found the meaning of CRUD is; Create, Read, Update, Delete :-)  
Always learning something new, which is the basis of what these small projects are for.

As a project manager in my current job role, I am currently enhancing my skills by learning Go. All of my projects on GitHub are a result of following tutorials and hands-on practices to grasp the fundamental concepts of this language. These projects serve as a showcase of my learning journey and are subject to the tutorials I've been using as a reference. I am eager to apply the knowledge I've gained so far and continue to learn more about this language to expand my expertise as a backend developer.

More projects will be added as and when I manage to get through them and as a beginner any and all feedback is very much welcomed.

## Acknowledgements

This most recent project was created following the awesome tutorial by Akhil Sharma.

- [Build A CRUD API with Golang](https://youtu.be/TkbhQQS3m_o)
- [Using the Mux Package from Gorilla](https://github.com/gorilla/mux)

## API Reference

#### Get all movies

Based on the code provided, I've created a couple of movies already.

```http
  GET /movies
```

#### Get movie by Id

```http
  GET /movies/{id}
```

#### Create a new movie

```http
  POST /movies
```

Provide it with a json body, such as:

```json
{
  "id": "3",
  "isbn": "43822547",
  "title": "Movie Three",
  "director": {
    "firstname": "Jamie",
    "lastname": "Mc"
  }
}
```

#### Update Movie

```http
PUT /movies/{id}
```

Provided with a json body of the updated fields

```json
{
  "isbn": "43822547",
  "title": "Movie Three",
  "director": {
    "firstname": "Jamie",
    "lastname": "McC"
  }
}
```

#### Delete Movie

```http
DELETE /movies/{id}
```
