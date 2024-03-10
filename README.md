## Compile
```
cd tas_client
mkdir -p build
cd build
cmake .. -G Ninja  -DCMAKE_EXPORT_COMPILE_COMMANDS=1
ninja
```

## Run
```
./tas_client  172.17.200.10 8888 1480 1000000000
// ./tas_client  ip port MTU PPS
```

