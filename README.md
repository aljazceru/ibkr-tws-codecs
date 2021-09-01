# Interactive brokers audio video codec support for TWS


```
git clone https://github.com/FFmpeg/FFmpeg.git
cd FFmpeg
# latest minor for of 56:
git checkout b94ec30428b9696f99b08055735689623fe63954 
./configure --enable-shared --disable-static --prefix=/usr --disable-yasm
make -j
make install
```
