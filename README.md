# bonsaii
Watch plants grow on the terminal

## TO DO

* Get networking going using [Boost](https://www.boost.org)
* Have basic terminal rendering

## Some Questions to Answer...

* Do we want peer-to-peer? or client-server communication (I think the client-server architecture is a lot more useful to learn... maybe we should do that)
* if we want client-server communication... how are we going to host this server? (it'd be cool to learn how to mantain a server)


## Basic Starting Elements

* server (maybe raspberryPi) running a sshd that will display the tui of the game. also using websockets for web access (both should maybe work using the same request? directly using TCP or serializing requests using JSON? (all of which come in [Boost.Beast](https://www.boost.org/doc/user-guide/task-networking.html))
