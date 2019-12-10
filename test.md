Hello 

```bash
curl -X POST \
  "https://api.$PLATFORM.kpn-dsh.com/auth/v0/token" \
  -H "apikey: $API_KEY" \
  -d '{"tenant": "'$TENANT'"}' > rest-token.txt
```
<!-- .element: class="lefty" -->Showing DIR size:
...bash
# du -shc * | sort -h | head -5
# du -shc lib/* | sort -rh | head -5
...
