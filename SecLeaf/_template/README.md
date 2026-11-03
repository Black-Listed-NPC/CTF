# `<Challenge Name>`

| | |
|---|---|
| **Category** | `<Web / Crypto / Pwn / Reversing / Forensics / OSINT / Misc>` |
| **Points** | `<pts>` |
| **Difficulty** | `<Easy / Medium / Hard>` |
| **Solves** | `<number of teams that solved it>` |
| **Author** | `<challenge author>` |

## 📜 Description

> `<Paste the challenge description exactly as given.>`

**Files / links given:** `<file.zip>`, `<http://challenge-url:port>`

## 🔍 TL;DR

`<One or two lines: the vulnerability / trick and how you got the flag. e.g. "SQL injection in the login form → dumped the users table → admin password → flag on dashboard.">`

## 🧭 Initial recon

`<What did you look at first? File type, source code, open ports, strings, page source…>`

```bash
file challenge.bin
strings challenge.bin | grep -i flag
```

`<What you noticed and why it was interesting.>`

## 🧠 Analysis

`<Explain the vulnerability or idea. Why does it work? Add screenshots:>`

![screenshot](./images/step1.png)

## 💥 Exploitation / Solution

`<Step-by-step: what you did to get the flag.>`

1. `<step one>`
2. `<step two>`
3. `<step three>`

```python
#!/usr/bin/env python3
# solve.py
from pwn import *

r = remote("<host>", <port>)
# ...
print(r.recvall().decode())
```

Full script: [`solve.py`](./solve.py)

## 🏁 Flag

```
SecLeaf{<flag_here>}
```

## 📚 What I learned

- `<new concept / tool / trick>`
- `<what you'd do faster next time>`

## 🔗 References

- `<link to article / docs / CVE that helped>`
