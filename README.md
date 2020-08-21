## mpd  
  
flexible, powerful, server-side application for playing music  
  
requires:    
```
apt install mpd mpc ncmpcpp
```  
```
yum install mpd mpc ncmpcpp
```  
```
pacman -S mpd mpc ncmpcpp
```  
  
Automatic install/update:
```
bash -c "$(curl -LSs https://github.com/dfmgr/mpd/raw/master/install.sh)"
```
Manual install:
```
mv -fv "$HOME/.config/mpd" "$HOME/.config/mpd.bak"
git clone https://github.com/dfmgr/mpd "$HOME/.config/mpd"
mkdir -p $HOME/.ncmpcpp 
ln -sf $HOME/.config/mpd/ncmpcpp.conf $HOME/.ncmpcpp/config
```
  
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/mpd" target="_blank">mpd wiki</a>  |  
  <a href="https://www.musicpd.org" target="_blank">mpd site</a>
</p>  
