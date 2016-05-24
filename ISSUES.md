On Mac system, if you use git with the configured vim options, you may be this error:
```
error: There was a problem with the editor 'vi'.
Please supply the message using either -m or -F option.
```

The fix is to run the following command to set the default editor from 'vi' to 'vim'
```
git config --global core.editor /usr/bin/vim
```
