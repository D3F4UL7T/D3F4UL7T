```
root@D3F4ULT:~# whoami
D3F4UL7T
```

```
[ RECON → ANALYZE → BUILD ]
```

---

### toolkit

| repo | role |
|------|------|
| **[OffKit](https://github.com/D3F4UL7T/OffKit)** | modular offensive toolkit — recon · scan · shell · payload · persist · enum · listener |
| **[HostEnum](https://github.com/D3F4UL7T/HostEnum)** | local system enumeration |
| **[ShellGen](https://github.com/D3F4UL7T/ShellGen)** | reverse / bind shell generator |
| **[NetForge](https://github.com/D3F4UL7T/NetForge)** | pivot · tunnel · stage |

```
python3 offkit.py recon -t target --headers --ports
python3 hostenum.py --quick
python3 shellgen.py -t reverse -H 10.10.14.5 -p 4444 --lang bash
python3 netforge.py tunnel ssh_dynamic --jump 10.10.14.5 --lport 1080
```

---

### focus

system internals · post-exploitation · network pivots · lab tooling

authorized testing only.

---

```
$ id
uid=0(D3F4UL7T) gid=0(root) groups=0(root),1337(ops)
```
