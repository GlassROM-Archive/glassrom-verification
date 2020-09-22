# Instructions to use signify to verify
# Make sure you trust the gpg key and that the .pub is legitimate
# FYI you can run this as a shell script. bash signify.md works
signify -V -p glassrom-signify.pub -x sha512sums.sig -m sha512sums;
signify -V -p glassrom-signify.pub -x sha3-512sums.sig -m sha3-512sums;
