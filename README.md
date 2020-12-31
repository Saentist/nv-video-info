# nv-video-info
Utilities to print information about video encode/decode capabilities of nvidia GPUs

For Ubuntu need:

```
apt install pkg-config libtool autoconf build-essential 
git clone https://github.com/FFmpeg/nv-codec-headers.git
cd nv-codec-headers
make
make install
cd ..
git clone https://github.com/Saentist/nv-video-info
cd nv-video-info
./autogen.sh
make 
make install
```
