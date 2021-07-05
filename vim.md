# `vim/vi` Editor:

### 1. `vimrc` Setup:
```
user@machine~$: touch ~/.vimrc # If doesn't exist ~/.vimrc, then create it.
```
```
set nu ic ai et ts=4 sw=4 hlsearch
```

&nbsp;

#### Individual Setup (Optional):
> Set Tab Space/Shift Wifth to 4: `:set ts=4 sw=4` <br/>
> Line Number: `:set nu` (active) and `:set nu!` (deactive) <br/>
> Highlight Search Results: `:set hlsearch` (active) and `:set hlsearch!` (deactive) <br/>
> Autometic Indentation: `:set ai` <br/>
  
> **Note:** ic --> ignore case; et --> expandtab; ts --> tabstop; sw--> shiftwidth; nu --> number <br/>

&nbsp;


### 2. Two Basic Modes:
1. Insert Mode/Insert Text: `a`, or `o`
1. Command Mode: `escape + : + <command>`

> **Note-1:** `:` implies `shift +`.
> **Note-2:** Write `:` by using `escape + shift + :`. <br/>
> **Note-3:** Write any command by using `escape` first. <br/>
> **Note-4:** The `+` sign denotes `press one after another button`. (e.g., `eacape + p` means press the `ESC` button and then `p`.) <br/>

&nbsp;

### 3. Open, Close, Save:
1. Save and Quit Together: `:x`, or `:wq` (Only Save: `:w`, Only Quit: `:q`)
1. Force Quit (without saving the file): `:q!`

&nbsp;

### 4. Delete Options:
1. Delete a Line: `eacape + dd`
1. Delete Till End of a Line: `eacape + d + $`
1. Delete Till Start of a Line: `eacape + d + 0`
1. Delete Multiple Line (in a range): `:4,8d` # Delete 4 to 8 lines

&nbsp;

### 5. Copy, Paste, Undo, Redo:
1. Copy a Single Line: `eacape + yy`
2. Copy Multiple Line (in a range): `4,8y`
3. Paste a Line: `eacape + p`
4. Cut and Paste Together: `eacape + dd` then `eacape + p`
5. Undo Text: `eacape + u`
6. Redo Text: `eacape + control + r`

&nbsp;

### 6. Moving Cursor:
1. Go to the Specific Line Number: `:n` (e.g.,: `:5`, `:11`)
1. Go to the Beginning of a File: `:0`, or `:1`, or `eacape + [[`
1. Go to the Ending of a File: `:$`, or `eacape + ]]`

1. Forward a Word: `eacape + w`
1. Backword a Word: `eacape + b`

&nbsp;

### 7. Pattern Search:
1. Ignore Case (Before Search): `:set ic`
1. Search: `:/<pattern>` (e.g., `:/password`, `:/yes`, `:/no`)
1. Search Text and Replace: `:%s/<oldText>/<newText>/g` (e.g., `:%s/today/tomorrow/g`)
2. Remove Highligh Text: `:noh`

&nbsp;

### 8. Run Programming from vi/vim:
1. Python Script: `:!python anyName.py`

&nbsp;

### End Notes:

#### Download the vim on Ubuntu:
> [1]. [Downloading Process](https://itsfoss.com/vim-8-release-install/)

#### References:
> [1]. [Richard's](https://vim.rtorr.com/) <br/>
> [2]. [Core/Basic Commands](https://linuxhandbook.com/basic-vim-commands/) <br/>
> [3]. [All Commands](https://www.keycdn.com/blog/vim-commands) <br/>
> [4]. [Chris Toomey Talk on YouTube](https://www.youtube.com/watch?v=wlR5gYd6um0) <br/>
> [5]. [Default Parameters Setting](https://askubuntu.com/questions/264258/changing-vim-editor-settings) <br/>
> [6]. [Downloading vim Editor](https://phoenixnap.com/kb/how-to-install-vim-ubuntu) <br/>
