### <mark style="background: #FF5582A6;">Scope</mark>  GF Patterns For the following parameters grep:
- ssrf
- RCE
- Lfi
- sqli
- ssti
- idor
- url redirection
- debug_logic
- interesting Subs

<mark style="background: #FF5582A6;">Source</mark>:   https://github.com/1ndianl33t/Gf-Patterns
Environment:  Go

<mark style="background: #FF5582A6;">Requirement</mark>:  
***go language 1.17 (go1.17) or above (latest)**
```
go version
```

<mark style="background: #FF5582A6;">Installation</mark>
**Downloading/Installing the GF Tool:**
```
go install github.com/tomnomnom/gf@latest
```

```
git clone https://github.com/1ndianl33t/Gf-Patterns
```

**Configuring the GF Tool:**
```
cp /root/go/bin/gf /bin/
```

```
cd Gf-Patterns
```

```
mkdir .gf
```

```
mv *.json .gf
```


## <mark style="background: #FF5582A6;">Example usages</mark>

```
cat subdomains.txt | waybackurls | sort -u >> waybackdata | gf ssrf | tee -a ssfrparams.txt
```

```
cat waybackdata | gf redirect | tee -a redirect.txt
```

