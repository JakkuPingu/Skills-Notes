# Windows commands

## Showing contents

```
more <file>
```

## Downloading files

### CMD.exe
```
curl <url>  -o <filename.txt>
```

```
curl <url> > filename.txt
```

## Finding stuff

```
findstr <word> <filename>
```

Useful flags

- \i Ignore Case
- \v Inverse Search

## sorting text file

```
sort <file> > <file.txt>
```

## Current Processes 

```
Tasklist
```

## Connecting to Remote Services

```
ssh <user>@<machine ip>
```

## If hostkey verification is fail

```
notepad.exe <path>
delete
```

### Linux commands

## Show disc usage

```
df
```

## Downloading files

if we get an SSL certificate error

```
curl --insecure <url>
```
or
```
curl -k <url>
```

Else

```
curl <url>
```

##  Modifying Permissons

```
chmod <perms> <file>
```

## Sort in numerical order

user -r for reverse

```
./<file> | sort
```

## Find command

search root

get rid of errors

```
find / -name <filename> 2>/dev/null
```

## Search inside a file

```
cat <filepath> | grep <word>
```

## Search man for content inside

```
man -k "<word>"
```

## Show current processes

```
ps -a
ps -au
ps -aux
```

## User detials

```
id
```

```
Whoami
```

### Python

setup Virtual Enviroment

```
python3 -m venv env
```

To activate

```
source ./env/bin/activate
```

```
. ./env/bin/activate
```

## Exit Env

```
ctrl + D
```
or
```
exit
```

