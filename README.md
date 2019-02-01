# tail-f-Vim
Using vim like tail -f.

## Installation
```bash
git clone https://github.com/HuiaShaoChang/tail-f-Vim.git
cd tail-f-Vim
echo "alias tailf=\"vim -R -c 'source `pwd`/tailf.vim'\"" >> ~/.bash_aliases
. ~/.bash_aliases
```

## Usage
```bash
tailf /var/log/syslog
```
![](https://raw.githubusercontent.com/HuaiShaoChang/tail-f-Vim/master/image.png)
