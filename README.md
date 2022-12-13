# Recursive-chmod-folders

To recursively chmod directories only:

```find /your/folder -type d -exec chmod 755 {} \;```

To recursively chmod files only:

```find /your/folder -type f -exec chmod 644 {} \;```
