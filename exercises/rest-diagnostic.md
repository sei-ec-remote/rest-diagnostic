# REST Diagnostic

This file is a markdown file. Markdown is a special way of formatting text, and one that's used by GitHub in its README files.

### Question 1

In your own words, define what REST is. In your answer, be sure to cite any
relevant sources you consulted in your search.

```md
REST is an approach/mindset for creating APIs that tries to use standardized
naming conventions and functionality patterns to make APIs easier to understand
and use.
```

### Question 2

Imagine you are designing an API that will deal with a resource called
`movies`, what would the appropriate RESTful routes be for sending requests to
that API? Please list the path next to the HTTP verb it would be associated
with.

```md
So far we've mostly used GET on paths (like "/movies") and paths with parameters
(like "/movies/:movie"). There are also POST, PATCH/PUT, and DELETE methods, but
we haven't used them yet and I don't know much about their technical details.
```

## Question 3

What are some of the benefits of using an architectural style like REST when
developing an API? When might you NOT want to use the RESTful style?

```md
Clear, preestablished naming conventions makes code both easier to write and
easier to understand, which is a very nice touch of standardization. However,
maybe it wouldn't be a great choice to use REST if we need some ultra-specific
functionality that doesn't fit neatly into any of the standardized methods or
naming conventions?
```