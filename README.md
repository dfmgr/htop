## htop  
  
interactive process viewer for Unix systems  
  
Automatic install/update:

```shell
bash -c "$(curl -LSs https://github.com/dfmgr/htop/raw/master/install.sh)"
```

Manual install:
  
requires:

Debian based:

```shell
apt install htop
```  

Fedora Based:

```shell
yum install htop
```  

Arch Based:

```shell
pacman -S htop
```  

MacOS:  

```shell
brew install htop
```
  
```shell
mv -fv "$HOME/.config/htop" "$HOME/.config/htop.bak"
git clone https://github.com/dfmgr/htop "$HOME/.config/htop"
```
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/htop" target="_blank" rel="noopener noreferrer">htop wiki</a>  |  
  <a href="https://hisham.hm/htop" target="_blank" rel="noopener noreferrer">htop site</a>
</p>  
