# Recursive-chmod-folders

To recursively chmod directories only:
find /your/site/root -type d -exec chmod 755 {} \;

To recursively chmod files only:
find /your/site/root -type f -exec chmod 644 {} \;
