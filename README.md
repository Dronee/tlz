# tlz
Easy tar.lz4 compressor and decompressor
Ideal for compressing/decompressing large file and folders in super fast speed.
If file has extension as .dlz it will decompress it other wise it will compress it with extension .dlz
which is  .tar.lz4 form of file or folder.
Example usage:
to compress
```dlz LinuxImageFolder```

to decompress
```dlz LinuxImageFolder.dlz```

Installation OSX:
brew install lz4
sudo cp dlz /usr/local/bin/dlz

Installation Linux:
sudo apt-get install lz4
sudo cp dlz /usr/local/bin/dlz
