# conn
`conn` is a simpler UNIX utility to keep track of the several SSH connections.

    $ conn             # Will print all the SSH connections stored previously.

    $ conn guru@host   # Will open a new SSH connection, upon successful connection and exit, 
                       # the program will add the user@server to the list of servers remembered.

    $ conn 1           # Will connect to the first server stored in the list. The short cut numbers
                       # are valid upto two digits (< 100)
