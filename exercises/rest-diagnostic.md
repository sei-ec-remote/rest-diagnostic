# REST Diagnostic

This file is a markdown file. Markdown is a special way of formatting text, and one that's used by GitHub in its README files.

### Question 1

In your own words, define what REST is. In your answer, be sure to cite any
relevant sources you consulted in your search.

```md
<!-- your answer here -->
REST is a representational state transfer - a way of formatting and accessing routes in a way that is clearly understood regardless of familiarity with a specific API. It also allows the front end and the back end (client and server) to be changed on their own terms without fundamentally messing with the connection between them, which is handled separately in REST. I used my notes and this resource: https://www.codecademy.com/article/what-is-rest.
```

### Question 2

Imagine you are designing an API that will deal with a resource called
`movies`, what would the appropriate RESTful routes be for sending requests to
that API? Please list the path next to the HTTP verb it would be associated
with.

```md
/movies/ GET
/movies/:id GET
/movies/new GET
/movies POST
/movies/:id/edit GET
/movies/:id PATCH/PUT
/movies/:id DELETE

```

## Question 3

What are some of the benefits of using an architectural style like REST when
developing an API? When might you NOT want to use the RESTful style?

```md
<!-- your answer here -->
The benefits of using REST are that you can clearly tell what the purpose of the route is based on its URL. Additionally, they're consistent in formatting - so you can use multiple resources while still following the same schema.

By using a clearly formatted style, people who are unfamiliar with your API can understand how to use it even without studying it a lot.

It would not be a good idea to use it if you want something super custom (since it is by nature standardized). I'm also not sure how authorization works with REST so maybe that's different? I suppose we'll find out!
```