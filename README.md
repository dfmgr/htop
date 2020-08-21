## htop  
  
interactive process viewer for Unix systems  
  
requires:    
```
apt install htop
```  
```
yum install htop
```  
```
pacman -S htop
```  
  
Automatic install/update:
```
bash -c "$(curl -LSs https://github.com/dfmgr/htop/raw/master/install.sh)"
```
Manual install:
```
mv -fv "$HOME/.config/htop" "$HOME/.config/htop.bak"
git clone https://github.com/dfmgr/htop "$HOME/.config/htop"
```
  
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/htop" target="_blank">htop wiki</a>  |  
  <a href="https://hisham.hm/htop" target="_blank">htop site</a>
</p>  
