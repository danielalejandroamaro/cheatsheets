# rsync cheatsheet

Sync folder in-progress to final:

```
rsync -avz ./in-progress /final
```

Sync the content from in-progress to final:

```
rsync -avz ./in-progress/ /final
```

More examples:
- [resource](https://devhints.io/rsync)