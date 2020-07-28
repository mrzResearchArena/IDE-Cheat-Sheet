# `vim/vi` Editor:

### A. Open, Close, Save:
1. Save and Quit: `:wq`
1. Save: `:w`
1. Quit: `:q!`
1. Insert Text: `i`

### B. Delete Option:
1. Delete a Line: `eacape + dd`, or `:d`
1. Delete Till End of a Line: `eacape + d$`
1. Delete Till Start of a Line: `eacape + d0`

### C. Copy, Paste, Undo, Redo:
1. Undo Text: `eacape + uu`, or `:u`
1. Redo Text: `eacape + control + r`
1. Copy a Line: `eacape + yy`
1. Paste a Line: `eacape + p`

### D. Moving:
1. Go to Beginning of a File: `eacape + [[`
1. Go to Ending of a File: `eacape + ]]`

1. Go to a Specific Line Number: `:n` (e.g: `:5`, `:11`)
1. Go to the First Line of the Text: `:1`, or, `:0`
1. Go to the Last Line of the Text: `:$`

### E. Parameters Setting:
1. Set Tab Space/Shift Wifth to 4: `:set ts=4 sw=4`
1. Set Line Number: `:set nu`

### F. Pattern Search:
1. Ignore Case (Before Search): `:set ic`
1. Search Text and Replace: `:%s/oldText/newText/g`

&nbsp;

### End Notes:
> **Note-1:** Write `:` by using `escape + shift + :`. <br/>
> **Note-2:** Write any command by using `escape` first. <br/>
> **Note-3:** The `+` sign denotes `press one after another button`, e.g. `eacape + p` means press the `Esc` button and then `p`. <br/>

&nbsp;

#### References:
> [1]. [web-1: Core/Basic Commands](https://linuxhandbook.com/basic-vim-commands/) <br/>
> [2]. [web-2: All Commands](https://www.keycdn.com/blog/vim-commands) <br/>
> [3]. [web-3: Downloading vim Editor](https://phoenixnap.com/kb/how-to-install-vim-ubuntu) <br/>
