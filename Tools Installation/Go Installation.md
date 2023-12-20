- Start by open your web browser and visit
```
https://golang.org/dl/
```
  
- Download the latest version for Linux – _“gox.xx.x.linux-amd64.tar.gz”_  
![[2.png]]  

- Open your terminal and navigate to your downloads folder  
```
cd /root/Downloads
```

- Extract the files  to /usr/local/ directory
```
tar -C /usr/local/ -xzf go1.13.6.linux-amd64.tar.gz
```

- Go to /root/ directory.
- Find hidden files (.zshrc) in terminal:
```
ls -la
```

- Add variables for GO by modifying _“~/.zshrc”_  
```
mousepad .zshrc
```

- Add the following paths to the end of the file  
```
export PATH=$PATH:/usr/local/go/bin
```

- Now we need to refresh the zshrc to get the updated variables  
```
source .zshrc
```

- Now we just need to verify that everything is correct configured and we can do that by creating a simple ‘hello world’ program in Go.  

```
mousepad helloworld.go
```  

-  Add the following code to the file:  

```
package main
import "fmt"
func main() 
{   
fmt.Printf("Hello world!\n")   
}
```


-  Then save the file and try to run the program:  
```
  go run helloworld.go
```
 
- If everything was configured correctly you should see something like this:  

![[3-300x49-1.png ]] 
