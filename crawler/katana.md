<mark style="background: #FF5582A6;">Scope</mark> : Crawling and spidering framework

<mark style="background: #FF5582A6;">Source</mark>:   https://github.com/projectdiscovery/katana
Environment:  Go

<mark style="background: #FF5582A6;">Installation</mark>:  
```
go install github.com/projectdiscovery/katana/cmd/katana@latest
```
 OR
```
git clone https://github.com/projectdiscovery/katana.git
```

```
cp /root/go/bin/katana /usr/local/go/bin/
```
## <mark style="background: #FF5582A6;">Usage</mark>

#### Help 
```
katana -h
```

#### URL Input
```
katana -u https://tesla.com
```

#### Multiple URL Input (comma-separated)
```
katana -u https://tesla.com,https://google.com
```

#### List Input
```
cat url_list.txt

https://tesla.com
https://google.com
```

```
katana -list url_list.txt
```

#### STDIN (piped) Input
```
echo https://tesla.com | katana
```

```
cat domains | httpx | katana
```

### Proxy to Burp Suite

```
katana -u abc.com -proxy http://127.0.0.1:8080
```
