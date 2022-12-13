# 221213-git-commands-TIL

## Shell command

- cd Documents/ - go to Documents/...
- mkdir dev - make directory name dev
- cd .. go to upper directory
- pwd - where am i?/print working directory
- touch readme.md - make readme.md
- mv readme.md bin/ move readme.md to bin directory
- cp readme.md bin/
- mv readme.md ./README.txt
- rm README.txt - remove README.txt

- rm -rf bin/ - remove bin
- chmod 750 readme.md - ??
- cat readme.md - show readme.md at shell
- vi readme.md - show readme.md at vim

### Markdown
- # h1
- ## h2
- ### h3
- #### h4
- ##### h5

### unordered list
- Item1
	- Item1-1
		-Item1-1-1
* Item2
+ Item3

### ordered list
1. Item1
2. Item2

### hyper link
[link text](link url)

### image
![image](image url)

<!--same as html-->

### Emphasis
*Italic*
**bold**
~line Break~
_single underscore

## Blockquote

## Commeand mode
- :q - quit
- :q! quit discarding all changes
- :w -write
- :wq - write and quit
- :{number} - jump to {number}th line

## Recap - Vim command
- h j k l - left, down, up, right
- i -insert mode
- v - visual mode
- ESC - back to normal mode
- d - delete
- dd - delete a line
- y - yank
- yy - yank a line
- p -paste
- u - undo
- a - append
- A - append from end of line
- o - open line( under )
- O - open line( upper )
- H - move to the top of the screen
- L - move to the bottom of the screen
