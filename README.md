# trial_of_might
## trials
### [Century 0 -> 1](https://underthewire.tech/century)
```ps
ssh -p 22 century1@century.underthewire.tech
```

### [Century 1 -> 2](https://underthewire.tech/century-1)
```ps
$PSVersionTable.BuildVersion
```

### [Century 2 -> 3](https://underthewire.tech/century-2)
[Invoke-WebRequest](https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.utility/invoke-webrequest?view=powershell-7.4)
```ps
ls C:\Users\century2\Desktop | select Name
```

### [Century 3 -> 4](https://underthewire.tech/century-3)
```ps
ls C:\Users\century3\Desktop | measure
```

### [Century 4 -> 5](https://underthewire.tech/century-4)
```ps
ls C:\Users\century4\Desktop -Recurse | select Name
```

### [Century 5 -> 6](https://underthewire.tech/century-5)
```ps
Get-ADDomain | select Name
ls C:\Users\century5\Desktop | select Name
```

### [Century 6 -> 7](https://underthewire.tech/century-6)
```ps
ls C:\Users\century6\ | measure | select Count
```

### [Century 7 -> 8](https://underthewire.tech/century-7)
```ps
ls C:\Users\century7\ -Recurse -File -Filter readme* | cat
```

### [Century 8 -> 9](https://underthewire.tech/century-8)
```ps
cat C:\Users\century8\Desktop\unique.txt | sort | unique | measure | select Count
```

### [Century 9 -> 10](https://underthewire.tech/century-9)
```ps
cat -delimiter ' ' C:\Users\century9\Desktop\Word_File.txt | select -Index 160
```

### [Century 10 -> 11](https://underthewire.tech/century-10)
```ps
Get-WmiObject win32_Service -Filter "Name = 'wuauserv'" | select Description
ls | select Name
```

### [Century 11 -> 12](https://underthewire.tech/century-11)
```ps
ls C:\Users\century11\ -Recurse -File -Hidden | where {$_.Name -ne 'desktop.ini'} | select name
```

### [Century 12 -> 13](https://underthewire.tech/century-12)
```ps
Get-ADDomainController | select Name
Get-ADComputer UTW -Properties Description | select Description
ls | select Name
```

### [Century 13 -> 14](https://underthewire.tech/century-13)
```ps
cat -delimiter ' ' C:\Users\century13\Desktop\countmywords | measure | select Count
```

### [Century 14 -> 15](https://underthewire.tech/century-14)
```ps
cat -delimiter ' ' C:\Users\century13\Desktop\countpolos | select-string -Pattern "^polo." | measure

```
