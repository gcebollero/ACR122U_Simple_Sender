# ACR122U_Simple_Sender
Send hex streams from stdin

Needs libnfc

# Compile
gcc -o sender sender.c -lnfc
# Use
cat HEX.txt | ./sender
