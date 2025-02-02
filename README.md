# compile-python
compiling and installing python from scratch

## Compile python and create VirtualEnv

'sudo apt-get install build-essential gdb libffi-dev libbz2-dev libncurses5-dev liblzma-dev libreadline6-dev libsqlite3-dev libssl-dev lzma lzma-dev tk-dev uuid-dev zlib1g-dev lcov libgdbm-dev' 

'wget https://www.python.org/ftp/python/3.9.21/Python-3.9.21.tgz'

'tar zxvf Python-3.9.21.tgz'

'cd Python-folder'

'./configure --enable-optimizations'

compile on all 2 cores 'make -j 2'

'sudo make altinstall'

'python' exit() '/usr/local/bin/python3.9'

'nano ~/.bashrc'
'alias python="usr/local/bin/python3.9"'
'source ~/bashrc'
'python -m venv ~/.venv'
'source ~/.venv/bin/activate'