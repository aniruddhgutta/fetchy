# fetchy

**fetchy** is a tiny posix compliant (linux-only) system fetch script.
It sacrifices portability for *minor* speed improvements, though a portable version can be found in the `portable` branch.
The portable version patches the following functions - `uptime`, `distro` and `kernel`
![](./preview.webp)

---

## Installation

Add it to any directory in $PATH, typically ~/.local/bin.
```sh
curl -fL https://codeberg.org/oceanicc/fetchy/raw/branch/main/fetchy -o ~/.local/bin/fetchy
chmod +x ~/.local/bin/fetchy
```
