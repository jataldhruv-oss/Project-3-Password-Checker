# Password Hash Cracking using Hashcat
## Cybersecurity Internship Project

## Introduction

This project demonstrates password hash cracking using Hashcat, a popular password recovery and penetration testing tool used in cybersecurity. The objective of this project is to understand how weak passwords can be cracked using dictionary attacks and why strong password practices are important.

The project was performed in a controlled lab environment for educational and ethical hacking purposes only.

---

## Objectives

- Understand password hashing concepts
- Demonstrate dictionary-based password cracking
- Identify risks of weak passwords
- Learn the basics of Hashcat usage
- Promote secure password practices

---

## Tools & Technologies Used

- Hashcat
- Windows Command Prompt
- MD5 Hash Generator

---

## Project Files

- `hashes.txt` → Contains the target password hash
- `wordlist.txt` → Contains dictionary passwords used for cracking
- `Screenshots/` → Contains Hashcat execution screenshots

---

## Hashcat Command Used

```bash
hashcat.exe -m 0 hashes.txt wordlist.txt
```

---

## Explanation

- -m 0 → MD5 hash mode
- hashes.txt → File containing password hashes
- wordlist.txt → Dictionary file for password cracking

---

## Demonstration

- The weak password hash was successfully cracked using a dictionary attack.
- Screenshots of the cracking process and recovered password are included in the project folder.

---

## Cracked Password

- hello123

---

## Learning Outcomes

Through this project, I learned:

- Basics of password hashing
- How dictionary attacks work
- Importance of strong passwords
- Usage of Hashcat for ethical hacking demonstrations
- Cybersecurity best practices

---

## Conclusion

This project demonstrates how weak passwords can be easily cracked using password recovery tools like Hashcat. It highlights the importance of creating strong and secure passwords to protect systems from unauthorized access.

---

## Disclaimer

This project was created strictly for educational and ethical hacking purposes in a controlled environment. No real-world systems or unauthorized targets were involved.
