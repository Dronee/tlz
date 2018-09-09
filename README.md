# tlz
Easy tar.lz4 compressor and decompressor
Ideal for compressing/decompressing large file and folders in super fast speed.
If file has extension as .dlz it will decompress it other wise it will compress it with extension .dlz
which is  .tar.lz4 form of file or folder.
<br />
Example usage:
<br />
to compress
```dlz LinuxImageFolder```

<br />
to decompress
```dlz LinuxImageFolder.dlz```

<br />
Installation OSX:
```
brew install lz4
sudo cp dlz /usr/local/bin/dlz
```

<br />
Installation Linux:
```
sudo apt-get install lz4
sudo cp dlz /usr/local/bin/dlz
```

<br />
Experiments on Some Linux VM Images
18GB Linux image is compressed to 6GB (obviously percentage is dependant on information amount inside VM image)
