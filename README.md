A ridiculously overengineered SQL compliment database using Django and Postgres. It is very silly, designed for learning purposes, and is not intended to be used in a production environment. 

The compliment model is very simple: it contains an id, the compliment itself, and the category. 
Valid categories are skills, trait, and appearance (backhanded compliments, in other words, are not allowed).

If you want to deploy this yourself (lol), you'll need to do the following:

- Set up and deplopy a PostGres server.
  - I used Ubuntu Server: https://ubuntu.com/download/server
  - Postgres download here:https://www.postgresql.org/download/
    - Installation guide: https://www.postgresql.org/docs/current/tutorial-install.html
- Input your postgres server settings in djangocheerup/settings.py
  - Secret key on line 23
  - allowed_hosts on line 28.
  - user, password, host, and port on lines 84-87 
- Download Postman to interact with the API: https://www.postman.com/downloads/
  -   Documentation: https://learning.postman.com/docs/getting-started/overview/
- Think of some nice things to say about people
