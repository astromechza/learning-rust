# learning-rust

Playground and resources as I learn Rust

## Step One : Install Rust

```
$ curl https://sh.rustup.rs -sSf | sh
$ rustc -V
rustc 1.41.1 (f3e1a954d 2020-02-24)
```

Remember the standard lib is much smaller and not tied directly into the language version.

## Step Two : Offline docs and references

Access https://doc.rust-lang.org/book/, and see:

```
The HTML format is available online at https://doc.rust-lang.org/stable/book/ and offline with installations of Rust made with rustup; run rustup docs --book to open.
```

So we'll always have that available.

Secondly:

- [A half-hour to learn rust](references/amos - A half-hour to learn Rust.html) is pretty good and has useful examples. Probably read this first!

## Step Three : Cargo vs just `rustc`

Use `rustc` for single file scripts and experiments. Use `cargo` for pretty much everything else.

## Step Four : IDE

IntelliJ plugin seems a little sketchy for now, so the best second bet is vscode + plugin.

Rust (rls) is the most used one.
