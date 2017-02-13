# update-repo

## Install

Clone the repository:

```bash
git clone git@github.com:Pouli/update-repo.git ~/update-repo
```

Add `update-repo` to your `$PATH` (e.g., in `$HOME/.zshrc`):

```bash
export PATH="$HOME/update-repo/bin:$PATH"
```

Restart your shell.

## Usage

Enter your parent projects directory:

```bash
cd $PARENT_PROJECT
```

Integrate changes from a remote repository into the current branch:

```bash
update-repo
```
