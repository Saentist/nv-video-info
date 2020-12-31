# nv-video-info
Utilities to print information about video encode/decode capabilities of nvidia GPUs

For Ubuntu need:

```
apt install pkg-config libtool autoconf build-essential 
git clone https://github.com/FFmpeg/nv-codec-headers.git
make
make install
cd ..
git clone https://github.com/Saentist/nv-video-info
cd nv-video-info
./autogen.sh
make 
make install```
