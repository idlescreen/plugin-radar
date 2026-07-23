# saver-radar

Official **radar** visualizer plugin for [IdleScreen](https://github.com/idlescreen/idle-core).

## Build

Requires a sibling checkout of the core daemon for `trance-api`:

```bash
git clone https://github.com/idlescreen/idle-core.git
git clone https://github.com/idlescreen/saver-radar.git
cd saver-radar
cargo build --release
```

## Install

After adding the IdleScreen package repository:

```bash
sudo apt install trance-saver-radar
# or: sudo dnf install trance-saver-radar
```

See [idlescreen.github.io/packages](https://idlescreen.github.io/packages/).

## License

Apache-2.0. See [LICENSE](LICENSE).
