# REST Diagnostic

This file is a markdown file. Markdown is a special way of formatting text, and one that's used by GitHub in its README files.

### Question 1

In your own words, define what REST is. In your answer, be sure to cite any
relevant sources you consulted in your search.

```md
<!-- your answer here -->
REST describes how resources are interacted with between the server and the client
```

### Question 2

Imagine you are designing an API that will deal with a resource called
`movies`, what would the appropriate RESTful routes be for sending requests to
that API? Please list the path next to the HTTP verb it would be associated
with.

```md
<!-- your answer here -->
localhost:3000/movies/:id/edit - 
create: '/' - post
get: /movies/:id/edit - index, show, edit
update/delete: /movies/:id - patch/delete


```

## Question 3

What are some of the benefits of using an architectural style like REST when
developing an API? When might you NOT want to use the RESTful style?

```md
<!-- your answer here -->
The benefit is that REST is standardized as well as cleaner than creating multiple pages to access with an HTML/CSS file each time.
I figure one might not use REST with a customized API that would need specific coding or security.
```