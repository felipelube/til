# To copy files respecting the .gitignore exclusions

```bash
rsync -av --filter=':- .gitignore' <source> <destination>
```
