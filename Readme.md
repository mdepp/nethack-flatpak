# nethack-flatpak

An unofficial NetHack distribution. In most cases you probably want to use the
version of nethack provided by your distribution, but you may wish to use this
flatpak bundle if you want to avoid a system-wide install, or if you want to
run a more recent nethack version.

## Usage

Fetch the `nethack.flatpak` bundle from the releases:

```
wget https://github.com/mdepp/nethack-flatpak/releases/download/<release>/nethack.flatpak
```

Install it:

```
flatpak install nethack.flatpak  # add `--user` for a per-user install
```

You may also want to add an alias to `flatpak run dev.mdepp.NetHack`. For
example, if you use Bash, you could add the following to your bashrc:

```
alias nethack='flatpak run dev.mdepp.NetHack'
```
