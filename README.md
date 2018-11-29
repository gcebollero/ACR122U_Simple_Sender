# ACR122U_Simple_Sender
Send hex streams from stdin
# Compile
gcc -o sender sender.c -lnfc
#Use
cat HEX.txt | ./sender
