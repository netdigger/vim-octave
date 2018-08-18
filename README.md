# vim-octave
Highlight syntax of GUN Octave in vim

This is a [octave.vim](https://www.vim.org/scripts/script.php?script_id=3600) mirror providing syntax highlighting for [GUN Octave](https://www.gnu.org/software/octave/)

## Install plugin

### Install By Vundel
Add the follow content to *~/.vimrc*

	" Octave plugins
	Plugin 'netdigger/vim-octave'

### Install by Manual
Install plugin by manual

	mkdir -p ~/.vim/syntax 
	cp octave.vim ~/.vim/syntax/ 

## Active plugin

Add the following lines to your ~/.vimrc to get ViM to use the file 
	"Octave
	augroup filetypedetect
	  au! BufRead,BufNewFile *.m,*.oct set filetype=octave
	augroup END
