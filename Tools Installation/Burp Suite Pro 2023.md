-  Go to /root/

-  Create a new folder, suppose "Burp Suite pro 2023"

-  Now paste "Burp(Cyber71)-20230726T032814Z-001.zip" file in it.

-  Create a new folder (Burp Bounty) inside "Burp Suite pro 2023".

-  And paste the zip "BurpBountyPro_v2.7.0.zip" file in it.

- Now go back to "Burp Suite pro 2023" folder and open terminal.

- Check java version:
```
java -version
```

```
update-alternatives --config java
```

![[Pasted image 20231218211119.png]]

-  Press Enter  to exit.

- Give all permissions:
```
chmod 777 *
```

- Run "BurpLoaderKeygen.jar" in Java
```
java -jar BurpLoaderKeygen.jar 
```

-  Check "Ignore Update" and change license name (optional)
![[Pasted image 20231218212320.png]]

Click Run, then "Don't show..." and then OK
![[Pasted image 20231218212612.png]]

Click on "I Accept"
![[Pasted image 20231218212845.png]]

Copy License and paste to "Enter License key" , and then Next.
![[Pasted image 20231218213235.png]]

Click on Manual activation.
![[Pasted image 20231218213420.png]]

Copy and paste in the following order and the click on Next
![[Pasted image 20231218213920.png]]

If succeeded, then click on Finish.
![[Pasted image 20231218214030.png]]

Exit and check again whether the license is activated.
![[Pasted image 20231218214221.png]]

Click on Run again.
![[Pasted image 20231218214259.png]]

License is successfully activated.
![[Pasted image 20231218214452.png]]

Now Close Burp Suite Pro

Go to the previous terminal and run BurpLoaderkeygen.jar again.
```
java -jar BurpLoaderKeygen.jar
```
![[Pasted image 20231218214903.png]]

But opening like this is not comfortable to use. So we have to create a shortcut.

Copy/cut the Loader command and close Burp suite
![[Pasted image 20231218215532.png]]

Create a file named 'anything.sh" and paste the Loader Command.
![[Pasted image 20231218215853.png]]

Give Executable permission to anything.sh and run.
```
chmod +x Burp2023.sh
```

```
./Burp2023.sh
```
![[Pasted image 20231218221247.png]]
![[Pasted image 20231218221446.png]]

Go to browser and download any Burp suit icon.

Now Go to desktop and create a launcher.

In Launcher, name the program, click on command and choose the anything.sh file.
![[Pasted image 20231218222528.png]]

Choose Burp Suite directory as Working Directory.
![[Pasted image 20231218222801.png]]

 Now Click on No icon > select icon from: Image Files > Choose burp Icon location and Create.
 ![[Pasted image 20231218223203.png]]