# REST Diagnostic

This file is a markdown file. Markdown is a special way of formatting text, and one that's used by GitHub in its README files.

### Question 1

In your own words, define what REST is. In your answer, be sure to cite any
relevant sources you consulted in your search.

```md
REST is a style for designing web based APIs. It gives you a nice naming
pattern for your routes so that other developers can see your intent and would
know how to consume your API without needing to dig into the code.
```

### Question 2

Imagine you are designing an API that will deal with a resource called
`movies`, what would the appropriate RESTful routes be for sending requests to
that API? Please list the path next to the HTTP verb it would be associated
with.

```md
POST '/movies'
GET '/movies'
GET '/movies/:id'
PATCH '/movies/:id'
DELETE '/movies/:id'
```

## Question 3

What are some of the benefits of using an architectural style like REST when
developing an API? When might you NOT want to use the RESTful style?

```md
Some of the benefits are that you can spend less time deciding how to name your
routes and just follow the conventions that other people have agreed upon.

It also makes your code base a bit more familiar to other developers without
even needing to dig into your actual code.

You might want to not use the RESTful style if you need something specifically
custom about your API, or for doing something like authentication which
requires slightly different types of requests than the normal CRUD ones.
```