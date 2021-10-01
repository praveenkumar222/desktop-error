# desktop-error

sometimes vnc viwer appears to black screen.
This occurs when the icons pack is not installed .
To Fix this error copy it and paste on termux ...

```
git clone https://github.com/praveenkumar222/desktop-error.git
cd desktop-error
mv datar.tar.xz $HOME
cd $HOME
tar -xvf ./datar.tar.xz
rm ./datar.tar.xz
wget https://github.com/Yisus7u7/termux-desktop-xfce/releases/download/kde/breeze-cursor-theme_5.20.5-4_all.deb
apt install ./breeze-cursor-theme_5.20.5-4_all.deb
rm breeze-cursor-theme_5.20.5-4_all.deb
wget https://github.com/Yisus7u7/termux-desktop-xfce/releases/download/arc/termux-arc-gtk-theme_20210412_all.deb
apt install ./termux-arc-gtk-theme_20210412_all.deb
rm termux-arc-gtk-theme_20210412_all.deb
rm ~/.vnc/*.pid
rm ~/.vnc/*.log
rm ~/.vnc/passwd 

```

This commends fix the blackscreen issue. 

