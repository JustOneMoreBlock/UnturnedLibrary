# Dumb Unturned Plugin Errors

```
[root@unturned1 pve1]# grep "Could not find dependency" unturned.log
Could not find dependency: MySql.Data, Version=6.8.8.0, Culture=neutral, PublicKeyToken=c5687fc88969c44d
```
`Breaks:` PlayInfoLib
`Fix:` Restoring MySql.Data.6.8.8.0.dll resolves this error.


```
[root@unturned1 pve1]# grep "Could not find dependency" unturned.log
Could not find dependency: MySql.Data, Version=6.9.8.0, Culture=neutral, PublicKeyToken=c5687fc88969c44d
Could not find dependency: MySql.Data, Version=6.9.8.0, Culture=neutral, PublicKeyToken=c5687fc88969c44d
Could not find dependency: MySql.Data, Version=6.9.8.0, Culture=neutral, PublicKeyToken=c5687fc88969c44d
Could not find dependency: MySql.Data, Version=6.9.8.0, Culture=neutral, PublicKeyToken=c5687fc88969c44d
```
`Breaks:` GlobalBan, Zaup_Warning, ZaupLeaderboard
`Fix:` Restoring MySql.Data.6.9.8.0.dll resolves this error.

Easy Fix: Download the `Library` version required and rename it to that version or download from my directory.

I got tired of searching for compatibility on forums and Discord with no real answers.
