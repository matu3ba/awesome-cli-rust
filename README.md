# awesome-rust-cli

 This list provides an overview of CLI tools, where Rust shines. &#127774;
 It is intended for __non-language__ specific use cases, where either **correctness** *inclusive or* **performance** is essential.
 *todos* and *in progress* may be added below.
 Installation instructions after [searching](https://doc.rust-lang.org/cargo/commands/cargo-search.html) are [here](https://doc.rust-lang.org/cargo/getting-started/installation.html) and [here](https://doc.rust-lang.org/cargo/commands/cargo-install.html).

 Feel free to send pull requests.

Credits to [@kreteshq](https://zaiste.net/posts/shell-commands-rust/)
for zoxide, rmesg, bandwhich
and [@ghuls](https://github.com/zaiste/zaiste.net/issues/7) for broot, git-interactive-rebase-tool.

## Daily usage

| Name      | crates.io | Explanation                                                  | Source                                                | Command |
| --------- | --------- | ----------------                                             | ----------------------------------------------------- | ------- |
| bat       | bat       | `cat`                                                        | [bat](https://github.com/sharkdp/bat)                 |  bat    |
| bottom    | bottom    | `htop`                                                       | [bottom](https://github.com/ClementTsang/bottom)      |  btm    |
| dust      | du-dust   | `du`                                                         | [dust](https://github.com/bootandy/dust)              |  du     |
| exa       | exa       | `ls`                                                         | [exa](https://github.com/ogham/exa)                   |  exa    |
| fd        | fd-find   | `find`                                                       | [fd](https://github.com/sharkdp/fd)                   |  fd     |
| hyperfine | hyperfine | cli benchmarking                                             | [hyperfine](https://github.com/sharkdp/hyperfine)     |hyperfine|
| kalk      | kalk_cli  | formula calculator with types and type conversions           | [kalk](https://github.com/PaddiM8/kalk)               | kalk    |
| procs     | procs     | `top`                                                        | [procs](https://github.com/dalance/procs)             |  procs  |
| rink      | rink      | unit-aware calculator with dimensionality analysis           | [rink](https://github.com/tiffany352/rink-rs)         |  rink   |
| ripgrep   | ripgrep   | `grep`                                                       | [ripgrep](https://github.com/BurntSushi/ripgrep)      |  rg     |
| sd        | sd        | `sed`                                                        | [sd](https://github.com/chmln/sd)                     |  sd     |
| starship  | starship  | shell customization                                          | [starship](https://github.com/starship/starship)      |use shims|
| tokei     | tokei     | LOC counting                                                 | [tokei](https://github.com/XAMPPRocky/tokei)          |  tokei  |
| watchexec | watchexec | Executes commands in response to file modifications          | [watchexec](https://github.com/watchexec/watchexec)   |watchexec|
| zellij    | zellij    | `tmux` with WASM plugins                                     | [zellij](https://github.com/zellij-org/zellij)        |  zellij |
| zoxide    | zoxide    | autojumper                                                   | [zoxide](https://github.com/ajeetdsouza/zoxide)       |  z      |


## Frequent usage

| Name       | crates.io           | Explanation                                       | Source                                                | Command |
| ---------- | ------------------- | ------------------------------------------------  | ----------------------------------------------------- | ------- |
| bandwhich  | bandwhich           | network utizilation                               | [bandwhich](https://github.com/imsnif/bandwhich)      |bandwhich|
| grex       | grex                | regex building tool                               | [grex](https://github.com/pemistahl/grex)             |  grex   |
| mdBook     | mdBook              | Markdown -> book (other backends: pdf,latex,epub.)| [mdBook](https://github.com/rust-lang-nursery/mdBook) |  mdbook |
| rmesg      | rmesg               | dmesg Kernel logs                                 | [rmesg](https://github.com/polyverse/rmesg)           |  rmesg  |
| tin-summer | tin-summer          | rm build artefcats                                | [tin-summer](https://github.com/vmchale/tin-summer)   |  **sn** |
| haku       | haku                | `make` alternative                                | [haku](https://github.com/VladimirMarkelov/haku)      |  haku   |
| just       | just                | `make` alternative                                | [just](https://github.com/casey/just)                 |  just   |
| xsv        | xsv                 | csv swiss army knife                              | [xsv](https://github.com/BurntSushi/xsv)              |  xsv    |
| unf        | unf                 | replace anti-unix characters                      | [unf](https://github.com/io12/unf)                    |  unf    |
| navi       | navi                | cheatsheet+launcher cli                           | [navi](https://github.com/denisidoro/navi)            |  navi   |
| skim       | skim                | fuzzy finder                                      | [skim](https://github.com/lotabout/skim)              |use shims|

[gisht](https://github.com/Xion/gisht) - running gists from shell
[uutils/coreutils](https://github.com/uutils/coreutils) - Crossplatform rewrite for GNU coreutils. However the usage antipatterns of coreutils are not documented.

## in progress/not polished yet

[fselect](https://github.com/jhspetersson/fselect) - `find` with SQL syntax(bad luck: breaks everytime I compile it)
[LuminS](https://github.com/wchang22/LuminS) - parallized `rsync`,`cp` and `rm` for local files(no preserve ownership, dry-run, symlink and no RAM-awareness)

## todos*

[Prettifying csv tables](https://github.com/phsym/prettytable-rs)  [LICENSE]
csv converter framework(best would be type-dependant) to all sorts of tables and back (author of **kalk** will implement the conversion)

### No hard to fulfill correctness inclusive or speed requirement

| Name       | crates.io           | Explanation                                       | Source                                                | Command |
| ---------- | ------------------- | ------------------------------------------------  | ----------------------------------------------------- | ------- |
| broot      | broot               | directory navigation                              | [broot](https://github.com/Canop/broot)               | br      |
| hexyl      | hexyl               | `hexdump`                                         | [hexyl](https://github.com/sharkdp/hexyl)             | hexyl   |
| Git Interactive Rebase Tool      | git-interactive-rebase-tool      | `git rebase -i`| [git-interactive-rebase-tool](https://github.com/MitMaro/git-interactive-rebase-tool)                     | used by git rebase |
