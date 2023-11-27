# FFF

FFF is a minimal terminal file browser using fzf.

![demo video](demo/fff_demo.mp4)

## Install

Download the scripts. And execute with:
```sh
. fff
```

The dot in front make cd works in current shell instead of subshell.

`fff` will attempt using `open` and `preview` scripts to open / preview file, but you can run without these.

## Usage

Execute with:
```sh
. fff
```

Recommend added alias like;
```sh
alias a='. fff'
```

In the fzf menu, select a directory will cd to that directory, when select other file, `fff` will attempt open the file with `open` (you should create your own!).

Few keybinds are:
| Keys                 | Actions               |
|----------------------|-----------------------|
| Right / C-l / return | Select the file       |
| Left / C-h           | Go to upper directory |
