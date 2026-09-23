# submodule url resolution fixture B

Contains real source files (app.py, main.js) plus hostile .gitmodules URLs.
- oob -> OOB webhook canary, metadata -> 169.254.169.254,
- rfc1918 -> 192.168.1.1, unresolvable -> *.invalid (surfaces fetch attempts)
