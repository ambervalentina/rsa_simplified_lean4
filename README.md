# RSA proof(lean4)

This is my first lean4 project. To make the project simpler, I made two additional assumptions to the theorem. Firstly, I removed the totient condition $pb<\varphi(n)$ while in  real RSA, $e$ is typically chosen before computing $d$.
Also I assumed $m$ is coprime to $p$ and $q$ to reduce difficulties and length of the project.\\
Also some other improvements can be done to make the verification more realistic, lile adding Padding Scheme. The theorem assumes $m < pq$, meaning no padding (e.g., OAEP) is used to prevent small message attacks.Real-world implementations include padding to secure encryption against partial decryption attacks.

reference: [lean-rsa](https://github.com/aronerben/lean-rsa/)

