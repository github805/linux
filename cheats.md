<!--v-->
### Showing DIR size

<!-- .element: class="lefty" -->DIR Size command:
```bash
du -shc * | sort -h | head -5
du -shc lib/* | sort -rh | head -5
```
## IP ROUTE
```bash
ip route get 172.25.17.203
```

## TCP DUMP
```bash
tcpdump -i eth0 -nnn host 172.25.17.203 or 172.25.17.204
```
