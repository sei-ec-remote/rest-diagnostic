# REST Diagnostic

This file is a markdown file. Markdown is a special way of formatting text, and one that's used by GitHub in its README files.

### Question 1

In your own words, define what REST is. In your answer, be sure to cite any
relevant sources you consulted in your search.

```md
it is a design principle for websites. It standardizes how clients and servers interact and share information. 
```

### Question 2

Imagine you are designing an API that will deal with a resource called
`movies`, what would the appropriate RESTful routes be for sending requests to
that API? Please list the path next to the HTTP verb it would be associated
with.

```md
Post /movies
get /movies
get movies/:id
patch /movies/:id
delete /movies/:id
```

## Question 3

What are some of the benefits of using an architectural style like REST when
developing an API? When might you NOT want to use the RESTful style?

```md
it makes it easy to understand your code by following standard naming practices.
Perhaps you would not want to use them if your program is doing something specific that is not within the scope of the basic restful process? Maybe if you a government agency still using some old machines and language like fortran you dont want to adhere to common principles because you should only have your own people communicating on your server. 
```