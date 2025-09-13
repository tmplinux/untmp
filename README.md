# untmp
Take a tmplinux container and convert it to one of the following:

1. squashfs
   1.1 put it in /srv/containers               --srv, -s
   1.2 put it in /var/lib/tmplinux             --def, -d
   1.3 put it in the current working directory (default)

2. folder
   2.1 put it in /srv/chroots                  (default)
   2.2 put it in the current working directory --cwd, -c

Syntax:
    `untmp [type] (--flags) [name]`

Examples:
```
untmp sfs --srv tmparch
untmp folder -c c-Ab23
untmp 2.2 c-Ab23
untmp 1.3 tmpdebian
```
