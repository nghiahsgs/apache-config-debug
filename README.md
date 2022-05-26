# apache-config-debug
apache config debug


## Syntax check
```
# Red Hat-based (Fedora, CentOS), Arch-based and OSX
httpd -t

# Debian-based (Ubuntu)
apache2ctl -t

# MacOS
apachectl -t
```

## List virtual hosts
```
# Red Hat-based (Fedora, CentOS), Arch-based and OSX
httpd -S

# Debian-based (Ubuntu)
apache2ctl -S

# MacOS
apachectl -S
```
