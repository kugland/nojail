# nojail

![AUR version](https://img.shields.io/aur/version/nojail)

**Script to execute binaries outside firejail**
## Usage

```
nojail CMD [args...]
```

You can create symlinks to this script inside `/usr/local/bin`, and then not only the program
will always run without firejail, but firecfg will refrain from creating its own symlinks.

## License

Released under the MIT license. See `LICENSE`.
