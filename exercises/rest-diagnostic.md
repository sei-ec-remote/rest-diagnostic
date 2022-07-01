# REST Diagnostic

This file is a markdown file. Markdown is a special way of formatting text, and one that's used by GitHub in its README files.

### Question 1

In your own words, define what REST is. In your answer, be sure to cite any
relevant sources you consulted in your search.

```md
REpresentational State Transfer
Architectual style for software
```

### Question 2

Imagine you are designing an API that will deal with a resource called
`movies`, what would the appropriate RESTful routes be for sending requests to
that API? Please list the path next to the HTTP verb it would be associated
with.

```md
index -- /movies -- GET
New -- /movies/new -- GET
Create -- /movies -- POST
Show -- movies/:id -- GET
Edit -- /movies/:id/edit -- GET
Update -- /movies/:id -- PUT
Destroy -- /movies/:id -- DELETE
```

## Question 3

What are some of the benefits of using an architectural style like REST when
developing an API? When might you NOT want to use the RESTful style?

```md
It is a standardized to set up routing in a way users/developers can understand

I'm not entirely sure about when not to use it, but i think some shortcomings are complciated URL paths, oversharing data, lots of HTTP requests, and hinders fast deployment

https://blog.devgenius.io/restful-routing-vs-graphql-4646d264c306
```