# Selfuse Scripts
Useful scripts. Inculding Command Prompt, Powershell, bash

# Bash

```bash
# Batch convert file encoding
find . -type f -iname "*.EXTENSION" -exec sh -c 'iconv -f windows-1252 -t utf-8 "$1" > converted && mv converted "$1"' -- "{}" \;
```

# PowerShell

# Command Prompt
