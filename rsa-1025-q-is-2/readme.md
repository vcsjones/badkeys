# RSA-1025 Q is 2

This key uses a `q` value of 2, which has the interesting property of being the only
even prime number. Software like openssl actually considers this key "OK", and passes
all prime checks. This results in the modulus (`n`) being even, which is of course
trivial to factor. 
