<!--v-->
### Showing DIR size

<!-- .element: class="lefty" -->DIR Size command:
```bash
du -shc * | sort -h | head -5
du -shc lib/* | sort -rh | head -5
```
## IP ROUTE
```ruby
ip route get 172.25.17.203
```

## TCP DUMP
```bash
tcpdump -i eth0 -nnn host 172.25.17.203 or 172.25.17.204
tcpdump -i eth1 -nnn -t -c 200 | cut -f 1,2,3,4 -d '.' | sort | uniq -c | sort -nr | head -n 20
```

## Kafka commands

# Kafka topic list
```bash
kafka-topics --list --zookeeper localhost:2181

```
