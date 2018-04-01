# NEkit
a copy of https://zhuhaow.github.io/NEKit

Install Carthage
```
  
$ brew install carthage      
          
```

Check if it is installed successfull.
```
       
$ carthage version      

```

Add
```
  
github "zhuhaow/NEKit"   

```
to you Cartfile.

Use
```
     
carthage update --no-use-binaries --platform mac,ios    

```
to install all frameworks. Do not use pre-compiled binaries since some of them might be buggy.