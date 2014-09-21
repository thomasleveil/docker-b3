Description
-----------

This [fig][2] project will put together [Docker][1] containers running:
- a Urban Terror 4.2.019 game server
- a MySQL database
- a B3 bot

Such an environment is meant to test B3.

The game server listens on port 27960 of the docker host.

The MySQL database can be connected to on port 3306 of the docker host with login `admin` and password `admin`.



Usage
-----

    fig up
    

    
Requirements
------------

- [docker][1]
- [fig][2] `pip install fig`


[1]: https://www.docker.com/
[2]: http://www.fig.sh/

