# commit
Git commit simulator using [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) conventions.

![demo](https://user-images.githubusercontent.com/82411321/188562957-5b54ac73-ae61-43a0-9735-233bcb1405c3.gif)

## Installation
### ⚠️ ⚠️ Install [gum](https://github.com/charmbracelet/gum#installation) first.

<details>
<summary> Install gum </summary>

Use a package manager:

```bash
# macOS or Linux
brew install gum

# Arch Linux (btw)
pacman -S gum

# Nix
nix-env -iA nixpkgs.gum

# Debian/Ubuntu
echo 'deb [trusted=yes] https://repo.charm.sh/apt/ /' | sudo tee /etc/apt/sources.list.d/charm.list
sudo apt update && sudo apt install gum

# Fedora
echo '[charm]
name=Charm
baseurl=https://repo.charm.sh/yum/
enabled=1
gpgcheck=0' | sudo tee /etc/yum.repos.d/charm.repo
sudo yum install gum
```

Or download it:

* [Packages](https://github.com/charmbracelet/gum/releases) are available in Debian and RPM formats
* [Binaries](https://github.com/charmbracelet/gum/releases) are available for Linux, macOS, and Windows

Or just install it with `go`:

```bash
go install github.com/charmbracelet/gum@latest
```
</details>

<br>

### macOS x64 & Silicon, Linux x64, Windows Subsystem for Linux
```bash
curl -s https://kunalsin9h.com/commit | bash
```

After Installing, add the following to your `.bashrc` file
```bash
export COMMIT_INSTALL="$HOME/.commit"
export PATH="$COMMIT_INSTALL/bin:$PATH"
```

## From Arch User Repository (AUR)
```bash
yay -S git-commit
```

## Usage
```bash
$ commit -h
# or
$ commit --help
```

Go to your project directory, stage your changes and run `commit` command.
> Note: commit command will also prompt to stage your changes.
```bash
$ cd my-project
$ commit
```

## Inspiration
This project is inspired by [gum](https://github.com/charmbracelet/gum)

## License
[MIT](https://github.com/KunalSin9h/commit/blob/master/LICENSE)

