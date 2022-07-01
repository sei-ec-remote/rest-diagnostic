# REST Diagnostic

This file is a markdown file. Markdown is a special way of formatting text, and one that's used by GitHub in its README files.

### Question 1

In your own words, define what REST is. In your answer, be sure to cite any
relevant sources you consulted in your search.

```md
REST is a manner in which a client and server communicate with each other. RESTful systems allow a client or a server to update independently without affecting each other, as the communication of the client and the server through standardized messages are the only times where client and server are connected

Used https://www.codecademy.com/article/what-is-rest
```

### Question 2

Imagine you are designing an API that will deal with a resource called
`movies`, what would the appropriate RESTful routes be for sending requests to
that API? Please list the path next to the HTTP verb it would be associated
with.

```md
const movies = require('movies')

app.get(/movies, (req, res) => {
    res.send(movies)
})
```

## Question 3

What are some of the benefits of using an architectural style like REST when
developing an API? When might you NOT want to use the RESTful style?

```md
If you need to send larger amounts of data that a RESTful system can't handle
```