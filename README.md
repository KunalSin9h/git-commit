# commit
Git commit simulator using [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) conventions.

![demo](https://user-images.githubusercontent.com/82411321/188562957-5b54ac73-ae61-43a0-9735-233bcb1405c3.gif)

## Installation
### Debian/Ubuntu
```bash
curl -fsSL https://kunalsin9h.dev/commit | bash
```
After Installing, add the following to your `.bashrc` file
```bash
export COMMIT_INSTALL="$HOME/.commit"
export PATH="$COMMIT_INSTALL/bin:$PATH"
```

## Usage
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

