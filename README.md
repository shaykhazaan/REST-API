# REST-API
Rest apis implemented through nodejs with two endpoints for sending and receiving data.
Data is represented inJSON format.

Endpoint to get data: http://localhost:8080/feed/posts
Endpoint to post data: http://localhost:8080/feed/post

Data can be sent in this format. 
e.g.
{
    "title": "Second Post",
    "content": "This is the second post"
}

you should get and output like this with an post created msg, id and your input data.

{
    "message": "Post created Successfully",
    "post": {
        "id": "2022-08-16T10:18:24.295Z",
        "title": "Second Post",
        "content": "This is the second post"
    }
}
