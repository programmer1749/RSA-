# RSA-
Here we implement how RSA is used to secure important user data
Begin
   1. Enter the message to be coded
   2. Choose two prime numbers p and q.
   3. Compute n = p*q.
   4. Calculate phi = (p-1) * (q-1).
   5. Choose an integer e such that 1 < e < phi(n) and gcd(e, phi(n)) = 1; i.e., e and phi(n) are coprime.
   6. Calculate d as d ≡ e−1 (mod phi(n)); here, d is the modular multiplicative inverse of e modulo phi(n).
   7. For encryption, c = me mod n, where m = original message.
   8. For decryption, m = c d mod n.
End
