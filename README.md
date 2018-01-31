# my-vimrc

Some custom settings with spf13 vim (http://vim.spf13.com/).
Those are listed in .vimrc.local file.

.vimrc.local and .ctags files should be placed in the root directory. Need to run "ctags -R" command to generate tags file
in the project directory.


### Find text
Put .aliases file in the root directory, add **source ~/.aliases** into *~/.zshrc or ~/.bashrc* file
Run *source ~/.zshrc* in the terminal to get updated

Now we can use the like the following to find text in the project folder:
> findjs project/appFolder searchText

> findfiles project/appFolder "*.js" searchText

This is just a sample example, we can add more aliases like that
