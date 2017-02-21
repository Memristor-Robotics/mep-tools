# Creating a Linux image

## Copy image from MMC to your hard drive
```sudo dd bs=4M if=/dev/mmc0 of=image.img status=progress```
where `/dev/mmc0` is your memory card device.


## Shrink the image
```./autoresizer.sh image.img```

## Share with us
If you want to share your image with collegues from Memristor upload it to:  
https://drive.google.com/drive/u/0/folders/0B8iyR5YUITZYYVFyWHNlaDNXMVk

