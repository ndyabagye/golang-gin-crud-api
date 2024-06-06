Based on this article [Tutorial: Developing a RESTful API with Go and Gin](https://go.dev/doc/tutorial/web-service-gin)

### What is it ?

An API service for a store selling vintage records on vinyl.

These are the endpoints that we shall create 

`/albums`

- GET – Get a list of all albums, returned as JSON.
- POST – Add a new album from request data sent as JSON.

`/albums/:id`

- GET – Get an album by its ID, returning the album data as JSON.