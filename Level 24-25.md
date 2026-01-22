Level 24-25

A local service requires the correct password and a 4-digit PIN. Brute-forcing all PIN combinations using a loop and netcat reveals the valid one. The correct attempt returns the next password. commands used: for i in {0000..9999}; do echo "<bandit24_password> $i" | nc localhost 30002 done

<img width="401" height="136" alt="level 24-level 25" src="https://github.com/user-attachments/assets/d2454e78-0ae1-4ba4-99dc-02f24efa266f" />

