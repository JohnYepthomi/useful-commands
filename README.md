# Handy commands
### List all Global NPM Packages:
```
npm list -g --depth 0
```
*Can be really helpful in finding unused global packages to save memory.*

---

### Command to clean caches and buffers: 
```
free -h && sudo sysctl -w vm.drop_caches=3 && sudo sync && echo 3 | sudo tee /proc/sys/vm/drop_caches && free -h
```
[Source](https://askubuntu.com/questions/1060118/how-to-free-up-the-memory-in-the-best-way)

---
