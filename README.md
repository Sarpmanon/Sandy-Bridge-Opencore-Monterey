# Sandy-Bridge-Opencore-Monterey

![about section](https://preview.redd.it/asus-n53sn-monterey-sandy-bridge-v0-7xdurdbbbnxc1.png?width=640&crop=smart&auto=webp&s=c914627c06cf8cf55f9ab815a058efce546cf38e)

Reddit post: [Here](https://www.reddit.com/r/hackintosh/comments/1cgxisy/asus_n53sn_monterey_sandy_bridge/)

This was tested on an Asus N53SN, with Intel Core i5-2410M Sandy Bridge CPU and NVidia Geforce GT 550M GPU (which doesn't work due to macOS' limitations). The device had 16GB of RAM, Realtek 8111 Gigabit Ethernet and an Atheros AR9285 Wi-Fi card which doesn't work above **macOS 11 Big Sur**. Bluetooth also doesn't work for the same reason.

You **HAVE** to use openCore Legacy Patcher in order the activate the integrated graphics (Intel HD 3000). If not, the OS will be extremely buggy, laggy and almost un-usable.

Put **-wegnoegpu** in boot arguments, otherwise it won't boot correctly.

You'll have to enable “FixupAppleEfiImages” in config.plist to prevent boot problems after the installation.

![desktop image dark]([https://github.com/tograh/testrepository/3DTest.png](https://preview.redd.it/asus-n53sn-monterey-sandy-bridge-v0-ggte5ebbbnxc1.png?width=1080&crop=smart&auto=webp&s=b78dd78e99419559c994c861fea12e1c4f38ec99))
