## lftp

## Download stuff
`lftp -u username,password ftp://hostname << EOF`

`set ssl:verify-certificate no`

`cd ~/../path/to/somewhere/to/say/you/can`

`mirror --parallel=4 --verbose /remote/path /local/path/`

`bye`

`EOF`