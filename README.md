# Erlang Echo Server
This is a super simple TCP echo server written in Erlang. Once a
client connects it will echo the lines that the client sends to the
server back to the client.

## Compiling and Running
Start the Erlang shell

    erl

Then use the following command in the Erlang shell to compile the program.

    c("echo").

To start the server listening on port 6000 use execute the following
command in the Erlang shell.

    echo:accept(6000).
