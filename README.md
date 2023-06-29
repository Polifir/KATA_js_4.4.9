# KATA_js_4.4.9

POST https://blog.kata.academy/api/users

Registration:

{
    "user": {
        "username": "vladimir3333",
        "email": "ulanoooov@gmail.com",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY0OWQ3YWUwNjBjNjc1MWIwMGI3OGIzNyIsInVzZXJuYW1lIjoidmxhZGltaXIzMzMzIiwiZXhwIjoxNjkzMjI2MjA4LCJpYXQiOjE2ODgwNDIyMDh9.JwG6QvzVeivZ8qKEcb_kgqmdx1Vp3-O80e1yRU9FAQ0"
    }
}

POST https://blog.kata.academy/api/users/login

Authentication:

{
    "user": {
        "username": "vladimir3333",
        "email": "ulanoooov@gmail.com",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY0OWQ3YWUwNjBjNjc1MWIwMGI3OGIzNyIsInVzZXJuYW1lIjoidmxhZGltaXIzMzMzIiwiZXhwIjoxNjkzMjI2Mjc5LCJpYXQiOjE2ODgwNDIyNzl9.__Z-mPd7YRqFdBQi64Tlza594zzhB1yHxp9LHxwiXIc"
    }
}

POST https://blog.kata.academy/api/profiles/vladimir3333

{
    "profile": {
        "username": "vladimir3333",
        "image": "https://static.productionready.io/images/smiley-cyrus.jpg",
        "following": false
    }
}
