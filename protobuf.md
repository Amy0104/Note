# Protobuf

Github: [https://github.com/protocolbuffers/protobuf](https://github.com/protocolbuffers/protobuf)

Website: [https://developers.google.com/protocol-buffers](https://developers.google.com/protocol-buffers)

## Installation

### For Mac

``` shell
git clone https://github.com/protocolbuffers/protobuf.git

cd protobuf

brew install autoconf
brew install automake
brew install Libtool

autoreconf -i
./autogen.sh
./configure
make
make check
sudo make install

```
