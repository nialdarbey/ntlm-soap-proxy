NTLM Authentication
===================
This is a windows protocol which involves a handshake between the http client and the server. The requirements are to pass the username, password, workstation
and the host of the resource.
A value for workstation might be the host itself.
The groovy script at the end takes the place of the http outbound and does both the authentication and the outbound dispatch.

Contact
=======
nial.darbey@mulesoft.com