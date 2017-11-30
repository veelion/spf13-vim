# Ubuntu 16.04
16.04 has vim build with python3 (use command ‘vim --version’ to check), which makes neocomplete/neocomplcache failed with python
so, I setup jedi-vim for python completion in .vimrc.local (check the file for details)

tips:
vim in 16.04 has a build with python2 which named “vim.nox-py2”,
sudo apt install vim-nox-py2
use vim.nox-py2 to open python file, will use neocomplete to complete,
use vim(actually vim.nox) to open .py, will use jedi-vim

use different vim open the same .py, the last one will show error about neocomplete, just delete .vimviews/*the-file

