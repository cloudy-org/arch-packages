## Maintainers Notice
Please use `aurpublish` for publishing:

```sh
# Like so...

aurpublish roseate
```

To add an AUR package use the `-p` command like so:

```sh
aurpublish -p roseate
```
> More information at their man page: https://man.archlinux.org/man/aurpublish.1#EXAMPLES

To skip pre-commit hooks (in rare scenarios) you can use `--no-verify`:

```sh
git commit -m "good commit message" --no-verify
```