# Install

## Ready

- python3
  ```shell
  sudo pacman -S python3
  ```

- pip3
  ```shell
  curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
  python3 python get-pip.py
  ```
- nodejs, npm
  ```shell
  sudo pacman -S nodejs npm
  sudo npm install -g neovim
  ```

- yarn
  ```shell
  sudo pacman -S yarn
  sudo yarn global add neovim
  ```

- ripgrep
  ```shell
  sudo pacman -S ripgrep
  ```

- ctags
  ```shell
  sudo pacman -S ctags
  ```
- pynvim
  ```shell
  sudo pip3 install  Pynvim
  ```
- lazygit
  ```shell
  sudo pacman -S lazygit
  ```



## checkout

```shell
git clone https://github.com/pixb/ThinkVim.git  ~/.config/nvim
cd ~/.config/nvim
bash scripts/install.sh
```


