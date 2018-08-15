# Rafi's dotfiles

This is largely based off of https://github.com/mathiasbynens/dotfiles

To update your shell, `cd` into local `dotfiles` repository and then:

```bash
source bootstrap.sh
```

Alternatively, to update while avoiding the confirmation prompt:

```bash
set -- -f; source bootstrap.sh
```

Also...some general

#Bash Terminal Notes

commands: 
```bash
ls
```
-l
-a
-la
```bash
cd
```
with nothing takes you home!
```bash
pushd [dir_to_go_to]
```
takes you to the new directory you want to work in!
```bash
popd
```
returns you to the old directory you were in
```bash
file
```
tells you what kind of file you're looking at
```bash
history
```
shows you your previous bash commands