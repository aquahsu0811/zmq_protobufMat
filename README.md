# Sending mat from C++ to python with zeromq

Requirements:  
Zmq  
OpenCV  
Protobuf 


## Install zmq
```
git clone https://github.com/zeromq/libzmq.git
sudo apt-get install libtool pkg-config build-essential autoconf automake uuid-dev
sudo apt-get install checkinstall
./autogen.sh
./configure
make
sudo checkinstall
sudo ldconfig
```

## Instll cppzmq
```
git clone https://github.com/zeromq/cppzmq.git
download and unzip the lib, cd to directory
mkdir build
cd build
cmake ..
sudo make -j4 install
```

