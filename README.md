# Unified XBPS

A single XBPS command to rule them all.

## Usage

`uxbps` is a simple script that chooses which xbps program to invoke by its first argument. `uxbps program args` is equivalent to `xbps-program args`.

```bash
# Equivalent to "xbps-install bash"
uxbps install bash

# Equivalent to "xbps-query -s make"
uxbps query -s make
```

## License

uxbps is licensed 0BSD.

