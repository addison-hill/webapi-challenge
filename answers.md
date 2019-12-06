## Mention two parts of Express that you learned about this week.

Express is a library or middleware that you can use functions that are built in to make things easier. It allows us to change the response or request.

## Describe Middleware?

Middleware is usually just a set of functions that are used to check something or do something and then allow it to move on. ie: logging and security.

## Describe a Resource?

In RESTful APIs everything is a resource, and each resource is available via a unique URI. Resource managements happens via HTTP methods or GET, POSTS etc.

## What can the API return to help clients know if a request was successful?

res.status(200).json({ message: "Request was successful" });

## How can we partition our application into sub-applications?

If you have say some posts that each user posted. You could split them up by dealing with "/users" in one router. And then dealing with "/users/posts" in another router maybe called postRouter.
