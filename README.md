# eos1.8-ubuntu-18.04-toolchain
EOSIO eos 1.8.x / eosio.cdt 1.6.3 toolchain image

# build 
```
cd eos1.8-ubuntu-18.04-toolchain
docker build --rm --tag eos1.8-ubuntu-18.04-toolchain .
```

# run 
```
docker run --rm -v $PWD -ti eos1.8-ubuntu-18.04-toolchain /bin/bash
```
