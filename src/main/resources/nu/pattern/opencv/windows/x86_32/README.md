# Windows x86_32

```shell
git clone git://github.com/Itseez/opencv.git itseez-opencv
cd itseez-opencv
git checkout 2.4
mkdir build
cd build
:: Make sure java and ant are configured before steps below
cmake -G "MinGW Makefiles" -DBUILD_SHARED_LIBS=OFF -DCMAKE_C_FLAGS=-m32 -DCMAKE_CXX_FLAGS=-m32 .. > cmake.log
make -j8
```
