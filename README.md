# toolbox
Just a bunch of tools I wrote. Everything in [shebang](shebang) runs by itself with its shebang. The install script will just create a symlink to these in /usr/local/bin/. Everything in [rust](rust) is a Cargo project that the install script will use `cargo install --path` on.

## Git Cloning
Use `--recursive` when git cloning since this repo has a submodule. If you already cloned non-recursively, that's ok, just run `git submodule init && git submodule update`
