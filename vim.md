# `vim/vi` Editor:

### 1. `vimrc` Setup:
```
user@machine~$: touch ~/.vimrc # If doesn't exist ~/.vimrc, then create it.
```
```
set nu ic ai et ts=4 sw=4 hlsearch
```

#### Individual Setup (Optional):
> Set Tab Space/Shift Wifth to 4: `:set ts=4 sw=4` <br/>
> Line Number: `:set nu` (Set) and `:set nu!` (Hide) <br/>
> Highlight Search Results: `:set hlsearch` (Set) and `:set hlsearch!` (Hide) <br/>
> Autometic Indentation: `:set ai` <br/>
  
> **Note:** ic --> ignore case; et --> expandtab; ts --> tabstop; sw--> shiftwidth; nu --> number <br/>
&nbsp;


### x. Two Basic Modes:
1. Insert Mode/Insert Text: `a` or, `i`
1. Command Mode: `escape + : + ...`   # : --> shift + ;
 
&nbsp;

### x. Open, Close, Save:
1. Save and Quit: `:wq` (Save: `:w`, Quit: `:q`)
1. Force Quit (without save the file): `:q!`


&nbsp;

### x. Delete Option:
1. Delete a Line: `eacape + dd`, or `:d`
1. Delete Till End of a Line: `eacape + d$`
1. Delete Till Start of a Line: `eacape + d0`
1. Delete Multile Line (in a range): `:4,8d` # Delete 4 to 8 lines

&nbsp;

### x. Copy, Paste, Undo, Redo:
1. Copy a (single) Line: `eacape + yy`
1. Paste a Line: `eacape + p`
2. Cut and Paste (together): `eacape + dd` then `eacape + p`
3. Undo Text: `eacape + uu`, or `:u`
4. Redo Text: `eacape + control + r`

&nbsp;

### x. Moving Cursor:
1. Go to Beginning of a File: `eacape + [[`, or `:1`, or, `:0`
1. Go to Ending of a File: `eacape + ]]`, or, `:$`
1. Go to a Specific Line Number: `:n` (e.g: `:5`, `:11`)

1. Forward a Word: `eacape + w`
1. Backword a Word: `eacape + b`

&nbsp;

### x. Pattern Search:
1. Ignore Case (Before Search): `:set ic`
1. Search: `:/pattern` (e.g: `:/password`, `:/yes`, `:/no`)
1. Search Text and Replace: `:%s/oldText/newText/g`

&nbsp;

### x. Run Programming from vi/vim:
1. Python Script: `:!python anyName.py`

&nbsp;

#### End Notes:
> **Note-1:** Write `:` by using `escape + shift + :`. <br/>
> **Note-2:** Write any command by using `escape` first. <br/>
> **Note-3:** The `+` sign denotes `press one after another button`, e.g. `eacape + p` means press the `Esc` button and then `p`. <br/>

&nbsp;

#### Download the vim on Ubuntu:
> [1]. [Downloading Process](https://itsfoss.com/vim-8-release-install/)

#### References:
> [1]. [web-1: Core/Basic Commands](https://linuxhandbook.com/basic-vim-commands/) <br/>
> [2]. [web-2: All Commands](https://www.keycdn.com/blog/vim-commands) <br/>
> [3]. [web-3: Downloading vim Editor](https://phoenixnap.com/kb/how-to-install-vim-ubuntu) <br/>
> [4]. [Chris Toomey Talk on YouTube](https://www.youtube.com/watch?v=wlR5gYd6um0) <br/>
> [5]. [Default Parameters Setting](https://askubuntu.com/questions/264258/changing-vim-editor-settings) <br/>
