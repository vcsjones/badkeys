# RSA-2048 N not P*Q

This RSA key contains a validate private key, however the modulus (N)
does not equal `P*Q`. Software may handle this differently. Some
software when supplied with P and Q, will recompute N and throw away
the supplied N value, thus "fixing" the bad modulus that was supplied.

Other software will compute the modulus from P and Q, and check it against
the supplied modulus. If the modulus does not match the computed one, the
software will produce an error.