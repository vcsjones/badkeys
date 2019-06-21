Bad Keys
========

This is a project like [BadSSL](https://badssl.com) that contains bad keys.
These keys are flawed in some kind of way that compromises the security of
the key.

These keys were "hand made" to include these flaws, they were not found in the
wild anywhere.

These keys exist for researchers, enthusiasts, and testers to understand the affects
and properties of using a bad key. Such uses could be, but are not limited to:

* Determining how software handles being given bad a bad key. A tester may wish to know
how a particlar peice of software works or behaves when it has been configured with a
weak or broken key, such as a web server.

* Learning properties of bad keys. You may wish to see if you can recover the private
parameters of a key when the "public" (modulus) portion of the key has been created using
flawed parameters, such as a bad public exponent, or composite (non-prime) numbers.

# Never Use These Keys In Production

As the description above states, all of the keys in this repository are flawed in some
way. They offer no security.

Actually don't use any random key you find on the internet. 
