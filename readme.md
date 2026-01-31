# Plugins for the file manager fm

[fm repository](https://github.com/qkzk/fm)
[crates.io](https//crates.io/fm-tui)
[docs.rs](https://docs.rs/fm-tui)

## How to install a plugin ?

1. Clone this repo,
2. Move to the desiserd plugin,
3. Compile it in release mode `cargo build --release`
4. Add a link to the plugin with its name in your fm config file at `~/.config/fm/config.yaml` or use `fmconfig plugin add`.
5. Check if the installation is successful with `fmconfig plugin list`

## Plugin list 

- [bat_previewer](https://github.com/qkzk/bat_previewer) use bat to preview highlighted text
- [eml previewer](https://github.com/qkzk/eml_previewer) previews emails (.eml)
- [sqlite previewer](https://github.com/qkzk/sqlite_previewer_fm) preview sqlite3 databases with fm. Inspired by ranger.
