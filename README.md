# util-scripts

`util-scripts` is a collection of Linux shell scripts I've hacked together over the years for
making various tasks easier/quicker.

> [!IMPORTANT]
> Some scripts make use of a `CODE_DIR` environment variable that points to the root of your code directory. If for whatever reason you don't feel like defining this, you can simply grep for and remove it from the scripts that use. It's simply a convenience for me and my environment.

## Installing

### 1. Clone the repo

```bash
cd ~/
git clone https://github.com/jakerieger/util-scripts
```

### 2. Add the directory to your path

```bash
export PATH="$HOME/util-scripts/bin:$PATH"
```
### 3. Reload changes

```bash
source ~/.bashrc # or ~/.zshrc
```

## License

All of the scripts in this repo are licensed under the [Unlicense](LICENSE).
