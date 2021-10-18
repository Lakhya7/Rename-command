# Rename-command
Processing triggers for man-db (2.9.1-1) ...
lakhya@DESKTOP-AC8492J:~$ pwd
/home/lakhya
lakhya@DESKTOP-AC8492J:~$ cd /mnt/
lakhya@DESKTOP-AC8492J:/mnt$ ls
c  d  e
lakhya@DESKTOP-AC8492J:/mnt$ cd /mnt/e/dipu
lakhya@DESKTOP-AC8492J:/mnt/e/dipu$ ls
IMG_20180704_113318.jpg      IMG_20180826_181532.jpg      IMG_20180902_173900_HHT.jpg  IMG_20180902_193232.jpg
IMG_20180708_202954-1.jpg    IMG_20180826_232852_758.jpg  IMG_20180902_174321.jpg      IMG_20180902_221128.jpg
IMG_20180802_195228_040.jpg  IMG_20180829_213618.jpg      IMG_20180902_183230_HHT.jpg  IMG_6505.JPG.jpg
IMG_20180802_210147_739.jpg  IMG_20180830_195615.jpg      IMG_20180902_190857.jpg      IMG_6510.JPG.jpg
IMG_20180825_202058.jpg      IMG_20180902_173235-1.jpg    IMG_20180902_192607_HHT.jpg  IMG_6511.JPG.jpg
IMG_20180825_202112.jpg      IMG_20180902_173235.jpg      IMG_20180902_192757.jpg      IMG_6513.JPG.jpg
IMG_20180825_202131.jpg      IMG_20180902_173332.jpg      IMG_20180902_192817_HHT.jpg  IMG_6514.JPG.jpg
IMG_20180825_202146.jpg      IMG_20180902_173346.jpg      IMG_20180902_193025.jpg      IMG_6515.JPG.jpg
IMG_20180825_202200.jpg      IMG_20180902_173404.jpg      IMG_20180902_193029.jpg      IMG_6533.JPG.jpg
lakhya@DESKTOP-AC8492J:/mnt/e/dipu$ rename 's/IMG/lakhya/' *.jpg
lakhya@DESKTOP-AC8492J:/mnt/e/dipu$ ls
lakhya_20180704_113318.jpg      lakhya_20180830_195615.jpg      lakhya_20180902_192817_HHT.jpg
lakhya_20180708_202954-1.jpg    lakhya_20180902_173235-1.jpg    lakhya_20180902_193025.jpg
lakhya_20180802_195228_040.jpg  lakhya_20180902_173235.jpg      lakhya_20180902_193029.jpg
lakhya_20180802_210147_739.jpg  lakhya_20180902_173332.jpg      lakhya_20180902_193232.jpg
lakhya_20180825_202058.jpg      lakhya_20180902_173346.jpg      lakhya_20180902_221128.jpg
lakhya_20180825_202112.jpg      lakhya_20180902_173404.jpg      lakhya_6505.JPG.jpg
lakhya_20180825_202131.jpg      lakhya_20180902_173900_HHT.jpg  lakhya_6510.JPG.jpg
lakhya_20180825_202146.jpg      lakhya_20180902_174321.jpg      lakhya_6511.JPG.jpg
lakhya_20180825_202200.jpg      lakhya_20180902_183230_HHT.jpg  lakhya_6513.JPG.jpg
lakhya_20180826_181532.jpg      lakhya_20180902_190857.jpg      lakhya_6514.JPG.jpg
lakhya_20180826_232852_758.jpg  lakhya_20180902_192607_HHT.jpg  lakhya_6515.JPG.jpg
lakhya_20180829_213618.jpg      lakhya_20180902_192757.jpg      lakhya_6533.JPG.jpg
lakhya@DESKTOP-AC8492J:/mnt/e/dipu$
