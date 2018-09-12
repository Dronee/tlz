# dlz
Easy ```.tar.lz4``` compressor and decompressor script
Ideal for compressing/decompressing large file and folders in super fast speed.
If file has extension as .dlz it will decompress it other wise it will compress it with extension .dlz
which is  .tar.lz4 form of file or folder.
<br />
Example usage:<br />

# to compress <br />
```dlz LinuxImageFolder``` <br />


# to decompress <br />
```dlz LinuxImageFolder.dlz```


# Installation OSX: <br />
```
brew install lz4
sudo cp dlz /usr/local/bin/dlz
```

# Installation Linux: <br />
```
sudo apt-get install liblz4-tool
sudo cp dlz /usr/local/bin/dlz
```

<br />
Experiments on some  VM Images <br />
18GB Linux image is compressed to 6GB in less than a min (obviously percentage is dependant on information amount inside VM image)
