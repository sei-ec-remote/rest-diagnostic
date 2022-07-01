# REST Diagnostic

This file is a markdown file. Markdown is a special way of formatting text, and one that's used by GitHub in its README files.

### Question 1

In your own words, define what REST is. In your answer, be sure to cite any
relevant sources you consulted in your search.

```md
REST - standardized style of interfacing between different resources, designed for network-based applications (specifically client-server applications.)
source: wikipedia

```

### Question 2

Imagine you are designing an API that will deal with a resource called
`movies`, what would the appropriate RESTful routes be for sending requests to
that API? Please list the path next to the HTTP verb it would be associated
with.

```md
/photos/, /photos/:id, /photos/new, /photos/:id/edit
All HTTP GET verbs
```

## Question 3

What are some of the benefits of using an architectural style like REST when
developing an API? When might you NOT want to use the RESTful style?

```md
REST architecture is designed for internet-scale usage, allows for scalability, simplicity and modifiability.

Might not want to use RESTful routes when a request is required to hold data.
```