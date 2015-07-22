# Gproxy
A secure proxy server, with secure SSL key exchange between client and server.

Creating keystore:

1.Goto Command prompt
2.Type
keytool -genkey -alias server -keyalg RSA -keysize 2048 -keystore <keystorename>.jks
3.Update the keystore in the program 
