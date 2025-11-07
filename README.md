# Obfuscated Reverse Shell

![PoC screenshot](https://cdn.prod.website-files.com/5ff66329429d880392f6cba2/676182bc78b8b88106a17157_626822d9beb1b531fd597ae2_Reverse%2520Shell%2520in%2520action.jpeg)

> ⚠️ **Educational & Defensive Research Only**  
> This repository contains a *theoretical* and *educational* proof-of-concept (PoC) designed to help researchers and defenders understand how malware may attempt to detect sandbox or debugger environments.  
> It is **not intended for offensive or malicious use**. Never execute this code outside an isolated, authorized, and fully controlled research environment.

---

## Overview

This code implements a reverse shell using **Import Address Table (IAT) resolution** to evade static analysis detection. The technique dynamically loads required Windows APIs at runtime instead of importing them directly.

## Compilation 

```bash
gcc -o Obf_ReverseShell.exe ReverseShell.c -lws2_32
```

---

## Contact

- Contact: `28zaakypro[.]proton[.]me`
