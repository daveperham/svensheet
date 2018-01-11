#Spawning TTY Shells

###python
```python
python -c 'import pty; pty.spawn("/bin/sh")'
```

###system (bash?)
```bash
echo os.system('/bin/bash')
```

```
/bin/sh -i
```

###perl
```perl
perl -e 'exec "/bin/sh";'
```

```perl
perl: exec "/bin/sh";
```

###ruby
```ruby
ruby: exec "/bin/sh"
```

###lua
```lua
lua: os.execute('/bin/sh')
```

###within IRB
```
exec "/bin/sh"
```

###within vi
```
:!bash
```

###within nmap
```
!sh
```




Source: https://netsec.ws/?p=337
