***Get All URLs

<mark style="background: #FF5582A6;">Scope</mark> : Fetch known URLs from AlienVault's Open Threat Exchange, the Wayback Machine, and Common Crawl..

<mark style="background: #FF5582A6;">Source</mark>:   https://github.com/lc/gau
Environment:  Go

<mark style="background: #FF5582A6;">Installation</mark>:  

```
go install github.com/lc/gau/v2/cmd/gau@latest
```

OR

```
git clone https://github.com/lc/gau.git
```

```
cd gau/cmd
```

```
sudo mv gau /usr/local/bin/
```

```
gau --version
```


## <mark style="background: #FF5582A6;">Example usages</mark>

```
gau -h
```

```
printf domain.com | gau
```

```
cat domains.txt | gau --threads 5
```

```
gau yahoo.com google.com
```

```
gau domain.com --o domain-urls.txt
```

```
gau domain.com --blacklist png,jpg,gif 
```