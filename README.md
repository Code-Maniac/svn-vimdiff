# svn-vimdiff
Simple wrapper scripts for using vimdiff or nvim -d with svn

## Installation
Run the install script
```bash
sudo ./install
```

## Usage
Add the following to $HOME/.subversion/config

### For vimdiff
```
diff-cmd = /usr/local/bin/svn-vimdiff
```

### For nvim -d
```
diff-cmd = /usr/local/bin/svn-nvimdiff
```

## License
[MIT](hhttps://choosealicense.com/licenses/mit/)
