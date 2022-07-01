# REST Diagnostic

This file is a markdown file. Markdown is a special way of formatting text, and one that's used by GitHub in its README files.

### Question 1

In your own words, define what REST is. In your answer, be sure to cite any
relevant sources you consulted in your search.

```md
REST stands for Representational State Transfer. It is a set of principles that can be used to define and set up a logical "map" through a site that also enables the developers to set up templates for commonly used sites.
```

### Question 2

Imagine you are designing an API that will deal with a resource called
`movies`, what would the appropriate RESTful routes be for sending requests to
that API? Please list the path next to the HTTP verb it would be associated
with.

```md
/movies               index (GET)
/movies/:title        show (GET)
/movies/new           new (POST)
/movies               create (POST)
/movies/:title/edit   edit (PUT/PATCH)
/movies/:title        update (PUT/PATCH)
/movies               destroy (DELETE)
```

## Question 3

What are some of the benefits of using an architectural style like REST when
developing an API? When might you NOT want to use the RESTful style?

```md
The benefits of a style like REST is that it mirrors a file structure that you can navigate through using the url keywords, parameters, and queries. It becomes a bit more human-readable to understand where you are on a site and how to get somewhere else, which would be helpful for anyone trying to navigate an API or website for the information they want.

As for why not to use a RESTful style, my guess is it may make less sense in a case where you are building an internal API or dealing with external clients and only need to route them directly to their required information every time, rather than having to handle a lot of variation.
```