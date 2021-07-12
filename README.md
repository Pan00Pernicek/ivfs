# ivfs
shell automation, merge of https://github.com/Pan00Pernicek/dynfs and https://github.com/Pan00Pernicek/sortfs

example:

```
. /path/to/ivfs
input /home/user/
  path=/tmp/idkanymor/
    use *.wtf
```
will sort all files with `wtf` extension to /tmp/idkanymor when ran

example of timers:

```
. /path/to/ivfs
onfchange 1 wtf cat wtf
```
will print content of file `wtf` each time it changes with detection per 1 second (instant aka 0 is bit broken and extra bloato)

for now very useless creation
