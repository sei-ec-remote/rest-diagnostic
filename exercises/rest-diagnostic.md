# REST Diagnostic

This file is a markdown file. Markdown is a special way of formatting text, and one that's used by GitHub in its README files.

### Question 1

In your own words, define what REST is. In your answer, be sure to cite any
relevant sources you consulted in your search.

```md
REST stands for Representational State Transfer. There are 7 major REST routes which are ways data can be accessed and changed over the network.
-https://git.generalassemb.ly/sei-ec-remote/RESTful-routing-and-liquid
```

### Question 2

Imagine you are designing an API that will deal with a resource called
`movies`, what would the appropriate RESTful routes be for sending requests to
that API? Please list the path next to the HTTP verb it would be associated
with.

```md
app.get("/movies/:id", (req, res) => {    
    res.send("Movie time!!!"})
```

## Question 3

What are some of the benefits of using an architectural style like REST when
developing an API? When might you NOT want to use the RESTful style?

```md
benfits:
-No expensive tools needed in order for interaction with web services.
-Shorter learning curve.
-More efficient (XML, used in SOAP messages, is longer than REST’s message formats).
-Faster, with less processing required.
(src: https://www.akana.com/blog/what-is-rest-api#:~:text=Why%20Are%20REST%20APIs%20Popular%3F,-REST%20APIs%20are%20popular%20because)

Thibault notices three distinct areas where REST is not a good fit: messaging, internal microservices, and performance with GraphQL and gRPC.
(src: https://nordicapis.com/is-rest-still-a-good-api-design-style-to-use/)
```