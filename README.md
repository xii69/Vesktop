# Vesktop

This is a fork of Vesktop using default icons
You can download the `.pacman` file from Actions in [here](https://github.com/xii69/Vesktop/actions)

## Building from Source

Packaging will create builds in the dist/ folder

```sh
git clone https://github.com/xii69/Vesktop
cd Vesktop

# Install Dependencies
pnpm i

# Either run it without packaging
pnpm start

# Or package
pnpm package
# Or only build the pacman target
pnpm package --linux pacman
# Or package to a directory only
pnpm package:dir
```
