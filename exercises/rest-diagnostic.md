# REST Diagnostic

This file is a markdown file. Markdown is a special way of formatting text, and one that's used by GitHub in its README files.

### Question 1

In your own words, define what REST is. In your answer, be sure to cite any
relevant sources you consulted in your search.

```md
REST is a way to describe how application resources are used, interact with eachother, and come together to form a full application.
```

### Question 2

Imagine you are designing an API that will deal with a resource called
`movies`, what would the appropriate RESTful routes be for sending requests to
that API? Please list the path next to the HTTP verb it would be associated
with.

```md
POST /movies
GET /movies
GET /movies/:movie
PATCH/PUT /movies/:movie
DELETE /movies/:movie 
```

## Question 3

What are some of the benefits of using an architectural style like REST when
developing an API? When might you NOT want to use the RESTful style?

```md
Using REST helps us just write code in a way that's pretty standardized when it comes to calling routes. This lets you read others' REST code and others read your REST code pretty well.

It can be bad if you want to make something special that REST would not handle very well.
```