<mark style="background: #FF5582A6;">Scope</mark> : Fast golang web crawler for gathering URLs and JavaScript file locations. This is basically a simple implementation of the awesome Gocolly library.

<mark style="background: #FF5582A6;">Source</mark>:   https://github.com/hakluke/hakrawler
Environment:  Go

<mark style="background: #FF5582A6;">Installation</mark>:  
```
go install github.com/tomnomnom/waybackurls@latest
```
OR
```
git clone https://github.com/tomnomnom/waybackurls.git
```

```
cp /root/go/bin/waybackurls /usr/local/go/bin/
```


## <mark style="background: #FF5582A6;">Example usages</mark>

***Help
```
waybackurls -h
```

***Single URL
```
echo abc.com | waybackurls | tee -a urls.txt
```

***Multiple URL
```
cat url_files.txt | waybackurls | tee -a urls.txt
```

