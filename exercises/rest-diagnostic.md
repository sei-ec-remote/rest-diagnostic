# REST Diagnostic

This file is a markdown file. Markdown is a special way of formatting text, and one that's used by GitHub in its README files.

### Question 1

In your own words, define what REST is. In your answer, be sure to cite any
relevant sources you consulted in your search.

```md
<!-- your answer here -->
in REpresntational state transfer:
- the server and client is separated
    -if the code is changed in the client side, this action will not affect the server side code
diffrent clients can make a request for the router
```

### Question 2

Imagine you are designing an API that will deal with a resource called
`movies`, what would the appropriate RESTful routes be for sending requests to
that API? Please list the path next to the HTTP verb it would be associated
with.

```md

<!-- your answer here -->
app.get('/movies',(req,res)=>{
    res.send(movies)
})
http//localhost:3000/movies
```

## Question 3

What are some of the benefits of using an architectural style like REST when
developing an API? When might you NOT want to use the RESTful style?

```md
<!-- your answer here -->
the benefit of REST is the serparation betewwn client and server. 

```