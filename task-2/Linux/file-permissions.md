# Linux File Permissions

## Commands Used

```bash
ls -l
chmod 700 filename
chmod 644 filename
chown user:user filename
```

## Permissions Type

| Symbol | Meaning |
| ------ | ------- |
| r      | Read    |
| w      | Write   |
| x      | Execute |

```bash
chmod 777 secret.txt
```

sudo ->
```bash
        r  w  x              - 4+2+1 = 7 means  rwx permissions
        ^  ^  ^              - 4+2   = 6 means  rw  permissions
        |  |  |              - 4     = 4 means  r   permissions
        4  2  1  ```         - etc.
```
## What each digit means:

777 is three digits:

    First digit (7) = Owner permissions

    Second digit (7) = Group permissions

    Third digit (7) = Other (everyone else) permissions
