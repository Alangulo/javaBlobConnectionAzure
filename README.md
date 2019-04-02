# Quick Start with Azure Storage SDK V10 for Java
## How to run this project


### Set credentials in environment variables 

Linux
```
export AZURE_STORAGE_ACCOUNT="<youraccountname>"
export AZURE_STORAGE_ACCESS_KEY="<youraccountkey>"
```

Windows
```
setx AZURE_STORAGE_ACCOUNT "<youracountname>"
setx AZURE_STORAGE_ACCESS_KEY "<youraccountkey>"
```

At this point, you can run this application using maven: `mvn compile exec:java`. It creates its own file to upload and download, and then cleans up after itself by deleting everything at the end. 

```
mvn compile exec:java
```



