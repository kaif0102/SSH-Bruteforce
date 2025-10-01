# SSH-Bruteforce
SSH Bruteforce is a simple, multithreaded SSH credential tester written in Python using paramiko. It supports username lists, password wordlists, and on-the-fly password generation. The script is intended for lab use, learning, and authorized penetration testing only.
⚠️ Legal & Ethical Notice — READ BEFORE USING
This tool can be used to gain unauthorized access if misused. Do not run it against systems you do not own or for which you do not have explicit written permission. Unauthorized access is illegal and unethical. Use this only in controlled environments (your lab, VMs, or with explicit consent).

Features

Attempts SSH logins using paramiko.

Supports:

Single username or username lists.

Password lists (from file) or generated password keyspace (configurable charset and length).

Multithreaded worker queue for parallel attempts.

Basic retry/backoff behavior on some paramiko exceptions.

Saves found credentials to credentials.txt.

Suppresses noisy Paramiko stderr output during connect attempts for cleaner console output.
