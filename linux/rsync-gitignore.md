# To copy files respecting the .gitignore exclusions

```bash
rsync -av --filter=':- .gitignore' <source> <destination>
```

Source: https://stackoverflow.com/questions/13713101/rsync-exclude-according-to-gitignore-hgignore-svnignore-like-filter-c
