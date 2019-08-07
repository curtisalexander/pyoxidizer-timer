# pyoxidizer-timer

Experiments with [PyOxidizer]().

## Get & Use

Download, decompress, and run.

### Download

| Platform            | Download                |
| --------------------| ------------------------|
| macOS               | [.zst][rl-macos]        |

[rl-macos]: https://github.com/curtisalexander/pyoxidizer-timer/releases/download/v0.1-beta/pyoxidizer-timer-osx-x64.zst


### Decompress

Requires [`zstd`](https://facebook.github.io/zstd/).

```sh
brew install zstd
```

Decompress, renaming binary to `timer`.

```sh
zstd -d pyoxidizer-timer-osx-x64.zst -o timer
```


### Run

```sh
./timer --timer 20 --unit seconds
```
