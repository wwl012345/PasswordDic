### About SecLists

SecLists is the security tester's companion. It's a collection of multiple types of lists used during security assessments, collected in one place. List types include usernames, passwords, URLs, sensitive data patterns, fuzzing payloads, web shells, and many more. The goal is to enable a security tester to pull this repository onto a new testing box and have access to every type of list that may be needed.

This project is maintained by [Daniel Miessler](https://danielmiessler.com/), [Jason Haddix](https://twitter.com/Jhaddix), and [g0tmi1k](https://blog.g0tmi1k.com/).

- - -

### Install

**Zip**

```
wget -c https://github.com/danielmiessler/SecLists/archive/master.zip -O SecList.zip \
  && unzip SecList.zip \
  && rm -f SecList.zip
```

**Git (Small)**

```
git clone --depth 1 \
  https://github.com/danielmiessler/SecLists.git
```

**Git (Complete)**

```
git clone https://github.com/danielmiessler/SecLists.git
```

**Kali Linux** ([Tool Page](https://www.kali.org/tools/seclists/))

```
apt -y install seclists
```

- - -

### Attribution

See [CONTRIBUTORS.md](CONTRIBUTORS.md)

- - -

### Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md)

- - -

### Similar Projects

- [Assetnote Wordlists](https://wordlists.assetnote.io/)
- [fuzz.txt](https://github.com/Bo0oM/fuzz.txt)
- [FuzzDB](https://github.com/fuzzdb-project/fuzzdb)
- [PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings)
- [Cook](https://github.com/giteshnxtlvl/cook)
- [SamLists](
