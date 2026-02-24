# Euphoria 3.11 日本語マニュアル (2026年改訂版)

作業中です。


``` bash
for f in *.htm; do iconv -f SHIFT_JIS -t UTF-8 "$f" | pandoc -f html -t markdown -o "${f%.htm}.md"; done
```
