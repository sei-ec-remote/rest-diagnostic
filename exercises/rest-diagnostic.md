# REST Diagnostic

This file is a markdown file. Markdown is a special way of formatting text, and one that's used by GitHub in its README files.

### Question 1

In your own words, define what REST is. In your answer, be sure to cite any
relevant sources you consulted in your search.

```md
<!-- your answer here -->

REST is a type of style language that is used for designing web pages with API's. 
```

### Question 2

Imagine you are designing an API that will deal with a resource called
`movies`, what would the appropriate RESTful routes be for sending requests to
that API? Please list the path next to the HTTP verb it would be associated
with.

```md
<!-- your answer here -->

app.get('/movies', (req, res) => {
    res.send(....)
}
app.get('/movies/:id', (req, res) => {
    res.send(....)
}
```

## Question 3

What are some of the benefits of using an architectural style like REST when
developing an API? When might you NOT want to use the RESTful style?

```md
<!-- your answer here -->
It helps with separation between client and server, it is flexible, and allows a variety of data forms.

you might not want to use it if you need to use your API for something specific on your site. 
```