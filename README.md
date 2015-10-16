# DihOs_MasshatLinux

Make 
cp Image utilities/linux0.01-3.5.img
cd utilities/ 
unzip hd_oldlinux.img.zip
qemu -hdb hd_oldlinux.img -fda linux0.01-3.5.img -boot a

