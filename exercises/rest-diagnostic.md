# REST Diagnostic

This file is a markdown file. Markdown is a special way of formatting text, and one that's used by GitHub in its README files.

### Question 1

In your own words, define what REST is. In your answer, be sure to cite any
relevant sources you consulted in your search.

```md
Rest stands for representational state transfer and it allows us to determine how to get access to and change different elements within a database (used class notes)
```

### Question 2

Imagine you are designing an API that will deal with a resource called
`movies`, what would the appropriate RESTful routes be for sending requests to
that API? Please list the path next to the HTTP verb it would be associated
with.

```md
'/' - would take us to the main API with all the data included
'/id' -  would fetch specific information about one piece of data from the api
```

## Question 3

What are some of the benefits of using an architectural style like REST when
developing an API? When might you NOT want to use the RESTful style?

```md
Rest allows us to keep information separate and have a consistent way of accessing data. YOu might not want to use REST when there is extremely specific data or a lot of data that cannot be manipulated with the seven RESTful routes.
```