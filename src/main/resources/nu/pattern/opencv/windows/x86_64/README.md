# Windows x86_64

```shell
git clone git://github.com/Itseez/opencv.git itseez-opencv
cd itseez-opencv
git checkout 2.4
mkdir build
cd build
:: Make sure java and ant path variables are configured before steps below
:: MinGW must be 64 bit
cmake -G "MinGW Makefiles" -DBUILD_SHARED_LIBS=OFF -DCMAKE_C_FLAGS=-m64 -DCMAKE_CXX_FLAGS=-m64 .. > cmake.log
make -j8
```
