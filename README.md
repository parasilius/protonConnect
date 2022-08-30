# protonConnect
`protonConnect()` keeps trying to connect to protonVPN and stops after 
connection. In the first try it tries to connect to the fastest server 
available and in the following tries a random server.

- [ ] a better approach would be trying to connect to the fastest server in 
case of a first failed run and failure in $k$(say 2 or 3) tries.
