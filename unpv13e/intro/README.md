# Learnings

* Daytime protocol is essentially deprecated

* Mac hosts no longer implement the daytime protocol, so ./daytimetcpcli cannot run with `127.0.0.1`

* There are some Colorado/Maryland public servers that do support daytime server
  * https://tf.nist.gov/tf-cgi/servers.cgi
  * I used 128.138.140.44, many of the servers are not reachable by ping
