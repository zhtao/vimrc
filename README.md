Instruction
---
1. Install packages<br>
`sudo yum install vim git ctags`<br>
`sudo pip install pyflakes`(optional)<br>

2. Install Vundle package<br>
`git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim`<br>

3. Copy the configuration file and color schemes<br>
`cp vimrc ~/.vimrc`<br>
`cp -r vim/colors ~/.vim/`<br>

4. Install Plugins<br>
`vim +PluginInstall +qall`<br>

5. Comment out Plugins in .vimrc then Remove Plugins<br>
`vim +PluginClean +qall`<br>

6. Turn on/off paste mode by F6 when you want to disable all plugins or paste something.<br>

Screenshot
---
![image](screenshot.png)
