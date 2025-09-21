# practice--hu
6. Next-gen crypto solution.
main.py
`python
#!/usr/bin/env python3
"""airdrophub: simple airdrop checklist demo"""
CHECKS = [
    "wallet connected",
    "profile complete",
    "social tasks done"
]

def status():
    for i, c in enumerate(CHECKS, 1):
        print(f"{i}. {c} — TODO")

if name == "main":
    print("airdrophub status:")
    status(
