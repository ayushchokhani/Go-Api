# go-api

Engineering Task
Instagram Backend API

Discord link - https://discord.gg/jYbzHZwd

INTRODUCTION
The task is to develop a basic version of Instagram. You are only required to develop the API for the system. You are required to design and develop an HTTP JSON API capable of the following operations:

    1. Create a user
        a. Should be a POST request
        b. Use JSON request body
        c. URL should be ‘/users'
        d. Users should have the following attributes:
            ▪ Id
            ▪ Name
            ▪ Email
            ▪ Password

    2. Get a user using id
        a. Should be a GET request
        b. Id should be in the url parameter
        c. URL should be ‘/users/<id here>’

    3. Create a Post
        a. Should be a POST request
        b. Use JSON request body
        c. URL should be ‘/posts'
        d. Posts should have the following Attributes. All fields are mandatory unless marked optional:
            ▪ Id*
            ▪ Caption*
            ▪ Image URL*
            ▪ Posted Timestamp*

    4. Get a post using id
        a. Should be a GET request
        b. Id should be in the url parameter
        c. URL should be ‘/posts/<id here>’

    5. List all posts of a user
        a. Should be a GET request
        b. URL should be ‘/posts/users/<Id here>'

ADDITIONAL CONSTRAINTS/REQUIREMENTS
    1. The API should be developed using Go.
    2. PostgreSQL should be used for storage.
    3. Only packages/libraries listed here and this specific package for databases can be used.

SCORING CRITERIA
    1. Completion Percentage
        a. No. of working endpoints among the ones listed above.
    2. Quality of Code
        a. Reusability
        b. Consistency in naming variables, methods, functions, types
        c. Idiomatic i.e. in Go’s style
    3. Passwords should be securely stored such they can't be reverse engineered
    4. Make the server thread safe
    5. Add pagination to the list endpoint
    6. Add unit tests

RESOURCES
    • Completing the Golang tour should give one a good grip over the language. Do this well and you will complete the task with ease.
    • This book covers both the workings of web and Go based servers.

SUBMISSION
    • Please upload your final submission files in ZIP format by filling up the following form: bit.ly/codesmith-engg

- GOOD LUCK -