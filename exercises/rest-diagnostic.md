# REST Diagnostic

This file is a markdown file. Markdown is a special way of formatting text, and one that's used by GitHub in its README files.

### Question 1

In your own words, define what REST is. In your answer, be sure to cite any
relevant sources you consulted in your search.

```md
REST is Representational State Transfer. A set of principles that describe how networked resources are accessed and manipulated. There are 7 major REST routes
```

### Question 2

Imagine you are designing an API that will deal with a resource called
`movies`, what would the appropriate RESTful routes be for sending requests to
that API? Please list the path next to the HTTP verb it would be associated
with.

```md
app.get("/movies/:id", (req, res) => {
    res.send("show the movies!")
})
```

## Question 3

What are some of the benefits of using an architectural style like REST when
developing an API? When might you NOT want to use the RESTful style?

```md
*Follow a set of prefined routes already set up by others
*Use codes that are already made by other so codes can be similiar or unified
*When when we need codes or something speficy for our personal project.

```