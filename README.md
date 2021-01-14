# configs

### make use of awesome vimrc
```sh
# save or delete your old vimrc
rm ~/.vimrc

git clone https:/github.com/JochenMan/configs.git
cd configs

# create softlinks to configs
sudo ln -s $(pwd)/vimrc ~/.vimrc
sudo ln -s $(pwd)/tmux.conf ~/.tmux.conf
```
