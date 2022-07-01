# REST Diagnostic

This file is a markdown file. Markdown is a special way of formatting text, and one that's used by GitHub in its README files.

### Question 1

In your own words, define what REST is. In your answer, be sure to cite any
relevant sources you consulted in your search.

```md
REST is a REpresentational State Transfer is allows us basic operations for reading and manipulating data. Its a set of principles that describe how networked resources are accessed and manipulated.
```

### Question 2

Imagine you are designing an API that will deal with a resource called
`movies`, what would the appropriate RESTful routes be for sending requests to
that API? Please list the path next to the HTTP verb it would be associated
with.

```md
app.get('/movies/', (req, res) =>{
}
```

## Question 3

What are some of the benefits of using an architectural style like REST when
developing an API? When might you NOT want to use the RESTful style?

```md
When you have a template that you don't want to have to replicate over and over with code, API's make sense when you have a collection of data that you want to use in the same fashion.
```