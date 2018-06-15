<!-- Answers to the Short Answer Essay Questions go here -->

1.  Describe Middleware, Sessions (as we know them in express), bcrypt and JWT.
    - Middleware: Between client and server, controls requests and responses to provide compatibility.
    - Sessions: By exchaging id, enables client to use secured data such as passwords in server without actually trasferring the data.
    - bcrypt: Hashing tool for secuirity.
    - JWT: Server generated token which proves valid client user.

2.  What does bcrypt do in order to prevent attacks?
    It hashes, or one way transforms password many times with secret word and time. Therefore, an attacker should spend significant time before crack into the password.
    If an attack is detected, user or system admin can change the password or add more secuirity tools with more time.

3.  What are the three parts of the JSON Web Token?
    Header, payload, signature