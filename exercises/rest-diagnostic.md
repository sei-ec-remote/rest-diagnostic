# REST Diagnostic

This file is a markdown file. Markdown is a special way of formatting text, and one that's used by GitHub in its README files.

### Question 1

In your own words, define what REST is. In your answer, be sure to cite any
relevant sources you consulted in your search.

```md
<!-- your answer here -->
A RESTFUL app  is an architecture for organizing and accessing data between a server and client. We use the RESTful routing is the path roganizations that we use to make it seperate all of the different methods we can use.

```

### Question 2

Imagine you are designing an API that will deal with a resource called
`movies`, what would the appropriate RESTful routes be for sending requests to
that API? Please list the path next to the HTTP verb it would be associated
with.

```md
<!-- your answer here -->
home route:
/
index route:
/movies
show route:
/movies/:movie
new route:
/movies/new
post route:
/movies
Edit route:
/movies/:movie/edit
updateroute:
/movies/movie
destroy route:
/mmovies/movie
```

## Question 3

What are some of the benefits of using an architectural style like REST when
developing an API? When might you NOT want to use the RESTful style?

```md
<!-- your answer here -->
Benefits is that you have clear seperation between the client and server, a uniform interface

Disadvantage: if you have tons of frequent large requests it could get pretty computationally heavy.
```