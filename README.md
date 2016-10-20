# Linux command line commands







## FIND

### Find “text-to-find-here” in the content of files in the whole disk
```find / -type f -exec grep -H 'text-to-find-here' {} \;```







## NETWORK

### See all available network interfaces
```ip link show```

### See status of “network-interface-here”
```ethtool network-interface-here```