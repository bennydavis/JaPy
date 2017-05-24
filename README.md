# JaPy
Remote python script execution through Java Client

abstract :- 

A sample java client which takes the python script(Only
non-interactive script) from the user and sends it to the
server side from script execution and returns the script
output back to the client side.The application is useful for
students(Beginners in python) and dynamic website who
don't want to install the python interpreter and configure
the python engine manually.The client reduce the worries
about the need for adding particular libraries as all popular
libraries like numpy and selenium can be preloaded in the
server side.The server technology enables the client user
to work from anywhere through the internet. Moreover the
client don't have to manually update the python interpreter
when some update is available. Since the client is written
in Java ; The Software is highly portable and end-user
don't have to install operating system specific Python
interpreter


Working :- 

A sample java client which takes python script(Only noninteractive
script) from the user through the Textbox ; Then
create a socket in the client and send the script to the server
side. Then in the server side - receive the incoming script from
the client side using the server sockets and store the python
script locally and Then execute the python script using either
Jython API or using the ‘ProcessBuilder’ class by creating an
object of the Process class with python script as the
parameters.Then get the output of the Process class in form
of String object and send the String object back to the client
using the socket connection which was created. 


