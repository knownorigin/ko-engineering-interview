# JSON API Exercise

## Description

We heavily utilise 3rd party APIs, we would like you to load a list of user posts, with additional
user data in a performant and scalable manner.

## Exercise

Using the endpoints on this API https://jsonplaceholder.typicode.com/ to do the following:

1. Retrieve post data API:
    * GET an array of posts

2. Retrieve user data API:
    * GET a specific users data (UserId: 3)

3. Combine the data:
    * Attach an array of relevant posts (Posts[]) to the user object
    * Return an object in this format, {...user, posts: [...posts]}

4. Testing:
    * If you haven't already, implement some tests for your code

## Notes

Things we're looking for:

* Talk us through what you’re doing and the decisions you’re making, it’s OK to think
  out loud.
* A focus on clean, testable code.
* Implement or highlight any optimisations you have identified.
* Write tests for your implementation.
