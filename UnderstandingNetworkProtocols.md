Summary:

- SSL : Secure sockets layer.
- TLS : Transport layer security
- HTTP : Hyper text transfer protocol.
- HTTPS : Secure HTTP


HTTP:
- Uses exposed communication between the client and the server.
- This makes it unsecure to share any personal information.
- Anyone can get into the line and record the commmunication and use it against you.

HTTPS:
- Uses secure encryption alogorithms to encrypt the communication between the client and the server.
- It uses either SSL or TLS to secure the connection. TLS is the successor to SSL.
    
    How HTTPS works:
    - The server has a public key and a thrid-party provided certificate for any client who wants to communicate.
    - When the client hits the server they get the public key and the certificate which is verified against commanly available certificates and the server is trusted.
    - The client then passes his private key along with the public key to the server to establish a secure connection.
    - Once the server is able to verify the key, secure communication is setup between client and the server and now can be used to send/receive sensitive data.

Link to resources:
- https://www.youtube.com/watch?v=hExRDVZHhig
- https://www.youtube.com/watch?v=33VYnE7Bzpk
- https://www.youtube.com/watch?v=E5bSumTAHZE
