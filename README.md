# wp_gittest
Testing out a script to setup WP with a sync system

After the first FTP Push change the 
`bitbucket-pipelines.yml` so that the   
```git ftp init --user $FTP_username --passwd $FTP_password ${FTP_host}```   
to   
```git ftp push --user $FTP_username --passwd $FTP_password ${FTP_host}```  