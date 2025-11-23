
# daily_json

Short description: a small repository holding JSON data files.

Files:
- `daily_4K.json` — main JSON dataset (check file for actual structure).
- `xxx.json` — placeholder file; contains no data.

Usage (quick):
- View first item with `jq`: `jq '.[0]' daily_4K.json`
- Or in Python:

```python
import json

with open('daily_4K.json', 'r', encoding='utf-8') as f:
	data = json.load(f)
	print(len(data))
	print(data[0])
```

Contributing: send PRs or issues. Keep JSON valid.

License: check repo owner or add a `LICENSE` file.
