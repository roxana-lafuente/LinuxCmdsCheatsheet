# Linux command line commands cheat-sheet







## FIND

#### Find “text-to-find-here” in the content of files in the whole disk
```find / -type f -exec grep -H 'text-to-find-here' {} \;```

#### Find filenames which contain “text-to-find-here” in the whole disk
```find / -name '*text-to-find-here*'```







## NETWORK INTERFACES

#### See all available network interfaces
```ip link show```

#### See status of “network-interface-here”
```ethtool network-interface-here```







## DATABASES

#### Connect to MySQL “YOUR_DB_HERE” with “YOUR_USER_HERE”
```mysql -u YOUR_USER_HERE -p YOUR_DB_HERE```







## KERNEL MODULES

#### Load kernel module named “KERNEL_MODULE_HERE”
```modprobe KERNEL_MODULE_HERE```

#### Unload kernel module named “KERNEL_MODULE_HERE”
```modprobe -r KERNEL_MODULE_HERE```