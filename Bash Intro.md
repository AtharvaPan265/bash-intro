# 00.sh
Simple "Hello, World!" in bash
- file is not executable as seen if you run `ls -l`  giving output 
   ```-rw-rw-r-- 1 <user name> <group name> <file size> <Last modification time MM DD hour:min>  <file name>```
   here we just need to  worry about `rw-rw-r--` that is just read, write, execute as rwx, and it is 3 times for Owner, Group, Others
- To make it executable we can just type
  ```sh
  chmod +x 00.sh
```

# 01.sh
## Shebang
This tells the System how to execute