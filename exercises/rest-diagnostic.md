# REST Diagnostic

This file is a markdown file. Markdown is a special way of formatting text, and one that's used by GitHub in its README files.

### Question 1

In your own words, define what REST is. In your answer, be sure to cite any
relevant sources you consulted in your search.

```md
<!-- your answer here -->
REST is REpresentational State Transfer
Rest is how network resourses are manipulated and transfered to each other.
```

### Question 2

Imagine you are designing an API that will deal with a resource called
`movies`, what would the appropriate RESTful routes be for sending requests to
that API? Please list the path next to the HTTP verb it would be associated
with.

```md
<!-- your answer here -->
app.get('/fruits/:movies', (req, res) => {
    res.send(fruits[req.params.movies]);
```

## Question 3

What are some of the benefits of using an architectural style like REST when
developing an API? When might you NOT want to use the RESTful style?

```md
<!-- your answer here -->
REST allows for enhanced Data storage and orginaztion. It provides a quick and smooth solution for accessing and manipulating data.  
```