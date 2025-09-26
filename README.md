# OpenThread Border Router

## Getting start

```
git clone --recursive https://github.com/gl-inet/s20_thread_br_opensdk.git
cd s20_thread_br_opensdk/

git submodule update --init --recursive

# Install SDK environment
./install.sh

# Active SDK environment
. ./esp-idf/export.sh

# Build RCP
cd esp-idf/examples/openthread/ot_rcp/
idf.py --preview set-target esp32h2
idf.py build
cd -

# Build Host
idf.py --preview set-target esp32s3
idf.py build
```

